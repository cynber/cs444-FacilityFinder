# Setting up a blog on your MkDocs site

See the [documentation here](https://squidfunk.github.io/mkdocs-material/plugins/blog/).

1. Enable the plugin by adding `- blog` to the `plugins` section of your `mkdocs.yml` file.
2. Add an `index.md` file to the `docs/blog` folder.
3. Add a `.authors.yml` file to the `docs/blog` folder to define the authors of the blog. You MUST do this before adding posts, or else the build will fail.

The folder structure for the blog should look like this:

``` bash
.
├─ docs/
│  └─ blog/
│     ├─ posts/
│     │  └─ post1.md   # Sample post
│     └─ index.md
│     └─ .authors.yml
└─ mkdocs.yml
```

The `index.md` file is the landing page for the blog, and future posts will be added to the `posts` folder. The `.authors.yml` file defines the authors of the blog. See the files in this repository for an example.

