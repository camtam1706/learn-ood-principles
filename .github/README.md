# GitHub Workflows

This directory contains automated workflows for the project.

## Deploy to GitHub Pages

The `workflows/deploy.yml` file defines a workflow that automatically deploys the website to GitHub Pages whenever a commit is pushed to the `main` branch.

### How it works

1. When a new commit is pushed to the `main` branch, the workflow is automatically triggered.
2. The GitHub Action will build and deploy all content from the root directory to GitHub Pages.
3. The website can be accessed at: `https://<username>.github.io/<repository-name>/`

### Additional setup

To make the workflow work, you need to:

1. Go to Settings > Pages > Build and deployment
2. Select "GitHub Actions" as the Source
3. Make sure your repository is public, or you have GitHub Pro to use GitHub Pages with a private repository 