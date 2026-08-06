# Launch instructions

This folder is ready to publish as the root of `VeredKurtz/veredkurtz.github.io`.

## Before replacing the current site

1. Download a ZIP backup of the existing repository from GitHub.
2. Keep the current repository name unchanged: `veredkurtz.github.io`.

## Publish through the GitHub website

1. Open the repository on GitHub.
2. Delete the current site files, while keeping the repository itself.
3. Upload every file and folder from this package, including `.nojekyll`.
4. Commit the changes to the branch currently used by GitHub Pages.
5. In **Settings → Pages**, confirm that the site deploys from the repository branch and the root folder.
6. Wait a few minutes, then visit `https://veredkurtz.github.io` and hard-refresh the page.

The `.nojekyll` file tells GitHub Pages to serve this static site directly rather than process it through the previous Jekyll theme.
