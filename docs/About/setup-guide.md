# Installing and setting up MkDocs-Material

!!! tip
    For full documentation visit [mkdocs.org](https://www.mkdocs.org)

## Setup MkDocs

1. Install MkDocs Material using pip: `pip install mkdocs-material`. If you don't have pip, [see this page for alternative installation methods](https://squidfunk.github.io/mkdocs-material/getting-started/).
2. Set up a new MkDocs project: `mkdocs new .`
3. When you want to see your changes, run `mkdocs serve` and go to the link it gives you. It will automatically update when you save changes to the files.

By default you the site will start with the basic MkDocs theme. To change it to the Material theme, and enable all the other cool features, you need to edit the `mkdocs.yml` file in the root of the project. Here is a basic example of what you might want to include:

``` YAML
site_name: Boilerplate
site_description: |
  This is a boilerplate for a MkDocs site.
repo_url: https://example.com/username/repo
repo_name: username/repo

# copyright: Copyright &copy; PLACEHOLDER
  # uncomment and change to add a copyright message

nav:
  - Home: index.md

theme:
  name: material

extra:
  generator: true  # false: hides 'Generated with MkDocs' message in footer
```

You can also see the `mkdocs.yml` file in the root of this repository for an example:

??? example "Current version of the `mkdocs.yml` file in this repo"

    ``` title="mkdocs.yml"
    --8<-- "./documentation/mkdocs.yml"
    ```




## Host your site on GitHub Pages

1. In the repository root, create the file: `.github/workflows/ci.yml` with the content from [the project site](https://squidfunk.github.io/mkdocs-material/publishing-your-site/).
2. Commit and push the changes to GitHub. This will trigger the GitHub Action to run through the steps in the file you just created (installing dependencies, building, and pushing the site to the `gh-pages` branch).
3. On GitHub, go to `Actions` and wait for the action to finish. You can check the logs to see if there are any errors.
4. On GitHub, go to `Settings` -> `GitHub Pages` and change the `Source` to  `Deploy from a branch` if it isn't already. You can then set the `Branch` to `gh-pages` and save. 
5. After everything is completed, you should see a link to your website either at the top of the `GitHub Pages` section or on the homepage of the repo under `Deployments`. 

The link should follow the format: `https://<username>.github.io/<repository-name>/`. If you don't see it, wait a few minutes and refresh the page.