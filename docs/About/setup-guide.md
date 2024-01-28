# Guide: Setting up a new MkDocs site

!!! note "Note"

    This guide is for setting up a new MkDocs site from scratch. 
    
    If you want to add a blog post, add a page, or otherwise modify this site, see the other guides in the sidebar.


## Setup MkDocs

1. Install MkDocs Material using pip: `pip install mkdocs-material`. If you don't have pip, [see this page for alternative installation methods](https://squidfunk.github.io/mkdocs-material/getting-started/).
2. Set up a new MkDocs project: `mkdocs new .`
3. When you want to see your changes, run `mkdocs serve` and go to the link it gives you. It will automatically update when you save changes to the files.

## Setup GitHub Pages

1. In the repository root, create the folders and file for this path: `.github/workflows/ci.yml`
2. While you can copy the contents of the file from this repository, you're better off grabbing the latest version of the code from [the project site](https://squidfunk.github.io/mkdocs-material/publishing-your-site/).
3. Commit and push the changes to GitHub. This will trigger the GitHub Action to run through the steps in the file you just created. This includes installing the dependencies, building the site, and pushing the site to the (likely new) `gh-pages` branch.
4. Go to the 'Actions' tab in your repository and wait for the action to finish. If it fails, you can click on the action to see the logs and figure out what went wrong. Assuming it succeeds, continue to the next step.
5. Go to the 'Settings' tab in your repository and scroll down to the 'GitHub Pages' section. Change the 'Source' to  `Deploy from a branch`, and then set 'Branch' to `gh-pages` and click 'Save'. 
6. After it finishes saving (and possibly building again), you should see a link to your website, either at the top of the 'GitHub Pages' section or on the homepage of the repo under 'Deployments'. It likely will follow the format: `https://<username>.github.io/<repository-name>/`. If you don't see it, wait a few minutes and refresh the page.

