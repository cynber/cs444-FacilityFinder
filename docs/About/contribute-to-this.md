# Contribute to this site

## Run locally

1. Clone or fork this repository.
2. Open the repository in your code editor and in the terminal, navigate to the root of the repository.
3. Run `pip install mkdocs-material` to install MkDocs Material.
4. Run each of the following to install the plugins that are being used:

    ``` bash
    pip install mkdocs-glightbox
    pip install "mkdocs-material[imaging]"
    pip install mkdocs-git-revision-date-localized-plugin
    ```

5. Run `mkdocs serve` to start the live-reloading docs server.

For common commands that you can use, see [this page](config-guide.md#commands).

For the project layout, see [this page](config-guide.md#project-layout).

## Make a blog post


1. Create a new file in the `docs/blog/posts` folder.
2. You will need to add metadata to the top of the file. See the [documentation here](https://squidfunk.github.io/mkdocs-material/plugins/blog/#metadata) for more information.
    - The `author` field must match the `name` field in the `.authors.yml` file.
    - The `categories` field can include anything, but it would be better to stay consistent with the other posts.
    - The `date` field should be in the format `YYYY-MM-DD`.
    - The `draft` field should be `false` if you want the post to be published.
    - The `slug` field should be a unique identifier for the post. It will appear in the URL for the post.
3. Write your post in Markdown below the metadata. Be sure to include a title (`# Title`) and the `<!-- more -->` tag to indicate where the preview should end.

!!! note "Optional Metadata"
    - The `links` field can be used to link to other pages, but I couldn't get it to work.
    - The `readtime` field can be used to override the default calculation. It shouldn't be necessary since the site should calculate it automatically.


### Example

This is an example how to structure a blog post file.

``` markdown
---
authors:
  - john
  - jane
  - jessica
  - james

categories:
 - Updates
 - 2024

date: 2024-01-25

draft: false

slug: sample-blog-post

---

# This is the title of the blog post

This is the body of the blog post. It is written in Markdown.

<!-- more -->

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod, nisl...
```