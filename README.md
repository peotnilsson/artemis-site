# Artemis Website Scaffold

This folder contains the inert static website scaffold for Sprint 19A, Sprint 19B, and Sprint 19C.

Boundaries:

- Static HTML and CSS only.
- No JavaScript.
- No npm, package manager, bundler, or build step.
- No external assets, fonts, scripts, iframes, analytics, or tracking pixels.
- No server, listener, deployment config, auth, payment, or waitlist service.
- No action buttons, command execution, remote control, memory mutation, project mutation, or settings changes.

Open `index.html` directly in a browser to view the local scaffold.

## Sprint 19B Visual Contract

The current scaffold includes:

- A stronger hero and CTA area.
- Feature sections for voice, terminal, dashboard, memory/project continuity, app-shell direction, and the safe action roadmap.
- Local HTML/CSS demo placeholders for terminal UI, dashboard status, app shell, voice flow, local memory/project continuity, and safe action flow.
- Roadmap, privacy/safety, GitHub/get-started, and footer sections.
- Responsive CSS media queries for tablet and mobile layouts.

The demo cards are placeholders only. They are not product screenshots, copied competitor screenshots, remote images, or generated assets.

## GitHub Pages Deployment

Expected public URL:

`https://peotnilsson.github.io/artemis/`

Deployment path:

- Source folder: `website/`
- Workflow: `.github/workflows/pages.yml`
- Artifact path: `website`
- Build step: none
- Runtime/server step: none
- Secrets: none

The workflow checks out the repository, configures GitHub Pages, uploads `website/` as the static Pages artifact, and deploys that artifact. It does not run npm, install dependencies, build assets, start a server, call a backend, or use secrets.

GitHub repository settings still need to enable Pages with GitHub Actions as the source before the public URL will serve the site.

## Updating The Site

Edit the static files in `website/`, then push to `dev` or `main`. The workflow only runs when `website/**` or `.github/workflows/pages.yml` changes, or when manually started from GitHub Actions.

Keep updates within the same safety boundary: no scripts, no analytics, no tracking pixels, no remote assets, no external fonts, no package manager, no build system, and no app/action controls.

## Disabling Deployment

To disable deployment, turn off GitHub Pages in the repository settings or disable the `Deploy static website to GitHub Pages` workflow in GitHub Actions. Removing or renaming `.github/workflows/pages.yml` also stops future workflow deployments.
