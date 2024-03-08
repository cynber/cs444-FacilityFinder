# Customizing MkDocs Material

!!! tip
    For full documentation visit [mkdocs.org](https://www.mkdocs.org)

## Commands

When editing the project locally, you can use the following CLI commands:

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Plugins & Extensions

!!! warning "Some plugins have extra steps"

    Some plugins need to be installed. If you see a step in the documentation like this:

    > pip install mkdocs-glightbox

    This will affect the setup in a few different ways:

    - You will need to install the plugin using the command provided on any local machine you are using to edit the project. If you don't you will see an error when you try to build the site with `mkdocs serve` or `mkdocs build`.

    - You will need to modify the `.github/workflows/ci.yml` file to include the installation of the plugin for the live site. You can add the command near the end, above the `- run: pip install mkdocs-material` line.


### **Recommended plugins:**

You can paste this in if you'd like. Refer to the official documentation for each plugin to see what it does and how to use it. Some plugins are custom (ex. `git-revision-date-localized`), and you will need to find documentation for them.

```yaml
plugins:
  - git-revision-date-localized:
      type: custom
      custom_format: "Last updated: %B %d, %Y"
      fallback_to_build_date: true
      exclude:
        - index.md
  - glightbox
  - privacy
  - search
  - social:
      cards_layout_options:
        font_family: Noto Sans
      enabled: !ENV [CI, false]
```


### **Recommended Markdown extensions:**

You can paste this in if you'd like:

```yaml
markdown_extensions:
  - admonition
  - attr_list
  - md_in_html
  - pymdownx.details
  - pymdownx.highlight:
      anchor_linenums: true
      line_spans: __span
      pygments_lang_class: true
  - pymdownx.inlinehilite
  - pymdownx.snippets
  - pymdownx.superfences
  - pymdownx.tabbed:
      alternate_style: true
  - sane_lists
```

### **Recommended theme options:**

You can paste this in if you'd like:

```yaml
theme:
  name: material
  language: en
  palette:
    - media: "(prefers-color-scheme)"
      toggle:
        icon: material/link
        name: Switch to light mode
    - media: "(prefers-color-scheme: light)"
      scheme: default
      primary: indigo
      accent: indigo
      toggle:
        icon: material/weather-sunny
        name: Switch to dark mode
    - media: "(prefers-color-scheme: dark)"
      scheme: slate
      primary: black
      accent: indigo
      toggle:
        icon: material/weather-night
        name: Switch to system preference
  features:
    - navigation.instant
    - navigation.instant.progress
    - navigation.tabs
    - navigation.sections
    - navigation.indexes
    - search.suggest
    - search.highlight
    - content.code.copy
    - content.code.select
  icon:
    repo: fontawesome/brands/github
```