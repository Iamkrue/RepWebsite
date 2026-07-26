# Reputable Solutions LLC website

This folder is the static GitHub Pages edition of the Reputable Solutions website.
It does not require Node.js, npm, a build command, or a server.

## Publish with GitHub Pages

1. Upload the contents of this folder to the root of the repository.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose the `main` branch and the `/ (root)` folder, then save.
5. Wait for the Pages deployment to finish before changing any DNS records.

The repository root must contain `index.html`. Do not upload this entire folder
as another nested folder.

## Make common edits

- Main page text and links: `index.html`
- Colors, spacing, and layout: `styles.css`
- Main brand image: `assets/reputable-business-card.png`

Search for the existing phone number, email address, or wording in `index.html`,
replace it, and commit the change. GitHub Pages will publish the update.

## Service requests

The service-request feature is intentionally hidden and is not included in this
static edition. A secure external form or serverless endpoint can be added later.
