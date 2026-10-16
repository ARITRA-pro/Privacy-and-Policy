# Radhe Discord Music Bot — Legal Pages

This folder contains a simple GitHub Pages website with:
- `index.html` — landing page
- `terms.html` — Terms of Service
- `privacy.html` — Privacy Policy

## Before publishing
1. Replace `[YOUR CONTACT EMAIL]` in `terms.html` and `privacy.html` with an email address you control.
2. Check the Privacy Policy against the actual bot code, database, logs, music providers, and hosting provider. Remove any data category that the bot does not process, and add anything it does process.
3. Confirm the terms fit your actual bot and intended use. These are starter templates, not legal advice or government certification.
4. Do not put bot tokens, passwords, or API keys in this repository.

## Publish with GitHub Pages
1. Sign in to GitHub and create a **public** repository named `radhe-legal-pages`.
2. Upload `index.html`, `terms.html`, and `privacy.html` to the repository's top level.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then click **Save**.
6. Wait for GitHub Pages to publish the site. The Pages section will show the live website URL.
7. Open the live URL and check that all three pages work.

Your links will follow this pattern (replace `YOUR-GITHUB-USERNAME` with your exact GitHub username):
- Home: `https://YOUR-GITHUB-USERNAME.github.io/radhe-legal-pages/`
- Terms: `https://YOUR-GITHUB-USERNAME.github.io/radhe-legal-pages/terms.html`
- Privacy: `https://YOUR-GITHUB-USERNAME.github.io/radhe-legal-pages/privacy.html`

These are URL patterns, not live links until you publish the repository.

## Add to Discord Developer Portal
Open your application in the Discord Developer Portal and place:
- Terms URL in **Terms of Service URL**
- Privacy URL in **Privacy Policy URL**

Save changes and test both links while signed out of GitHub, so you confirm they are public.
