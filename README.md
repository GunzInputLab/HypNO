# HypNO — Hypnatiq Network Observatory

Private website-review repository for the current HypNO prototype.

## What this repository contains

- `index.html` — the current website prototype, unchanged from the approved HTML
- `.nojekyll` — tells GitHub Pages to serve the static files directly
- `robots.txt` — asks search engines not to index the prototype
- `NOTICE.md` — ownership and private-review notice for the website
- `REVIEW_FEEDBACK.md` — a structured review form
- `.github/ISSUE_TEMPLATE/website-review.md` — an optional GitHub issue template for reviewer feedback
- `SHA256SUMS.txt` — file-integrity hashes

This repository contains the **website prototype only**. It does not contain the HypNO application source code, provider credentials, signing keys, gateway credentials, or private investigation evidence.

## Upload to GitHub

1. Create a new GitHub repository.
2. Keep the repository **Private** while the site is under review.
3. Upload the **contents of this folder** to the repository root. Do not upload only the ZIP file.
4. Confirm that `index.html` appears at the top level of the repository.
5. Invite only the reviewers who need access.
6. Do not add an open-source license while the commercial and application licensing review is unresolved.

## Review without publishing a website

The safest private-review method is:

1. Keep the repository private.
2. Add the reviewer as a repository collaborator.
3. Ask the reviewer to download the repository or `index.html`.
4. Use `REVIEW_FEEDBACK.md` or the included GitHub issue template for comments.

## Optional GitHub Pages preview

To test the site through a real browser:

1. Open the repository's **Settings**.
2. Open **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the repository root.
5. Save and wait for the Pages address.

### Important privacy warning

A private repository does **not** automatically make a normal GitHub Pages website private. Standard Pages sites may be publicly reachable even when their source repository is private. GitHub's access-controlled private Pages sites require an eligible GitHub Enterprise Cloud organization.

The `noindex` meta tag and `robots.txt` discourage search indexing, but they are not passwords or access controls. Do not enable Pages if the site must remain strictly private.

Official GitHub references:

- GitHub Pages publishing source: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- GitHub Pages site visibility: https://docs.github.com/enterprise-cloud@latest/pages/getting-started-with-github-pages/changing-the-visibility-of-your-github-pages-site

## Current product status

This is a private development prototype.

- No public application download
- No working beta submission
- No provider-key entry
- No account system
- Pricing and licensing are not final
- Network Collector and Sensor features remain development work

## Before a public launch

- Re-verify every competitor comparison against current official documentation.
- Replace prototype forms with secure server-side handling.
- Publish a privacy policy and support contact.
- Complete product signing, licensing, and release acceptance.
- Remove `noindex` and revise `robots.txt` only when the site is ready to be discoverable.
