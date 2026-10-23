# Static deployment

The site is plain HTML, CSS, JavaScript, and local media; it has no build step.

## GitHub Pages

1. Push the site and `.github/workflows/pages.yml` to the `main` branch.
2. In the repository, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source.
3. The workflow deploys the site on each push to `main`; it can also be started manually from **Actions**.

## Netlify

1. Import the repository in Netlify.
2. Leave the build command empty and set the publish directory to `.`.
3. The included `netlify.toml` already sets the publish directory.

## Before publishing

Confirm the public contact details, WhatsApp number, email address, room rates and amenities. Verify that ratings, review quotes, and reviewer names are genuine and authorized for publication; replace or remove any that are not.
