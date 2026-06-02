# Artemis Website Scaffold

This folder contains the inert static website scaffold for Sprint 19A, Sprint 19B, Sprint 19C, and Sprint 19D.

Boundaries:

- Static HTML and CSS only.
- No JavaScript.
- No npm, package manager, bundler, or build step.
- No external assets, fonts, scripts, iframes, analytics, or tracking pixels.
- No server, listener, deployment config, auth, payment, or waitlist service.
- No action buttons, command execution, remote control, memory mutation, project mutation, or settings changes.

Open `index.html` directly in a browser to view the local scaffold.

## Sprint 19B Visual Contract

The scaffold includes:

- A stronger hero and CTA area.
- Feature sections for voice, terminal, dashboard, memory/project continuity, app-shell direction, and the safe action roadmap.
- Local HTML/CSS demo placeholders for terminal UI, dashboard status, app shell, voice flow, local memory/project continuity, and safe action flow.
- Roadmap, privacy/safety, GitHub/get-started, and footer sections.
- Responsive CSS media queries for tablet and mobile layouts.

The demo cards are placeholders only. They are not product screenshots, copied competitor screenshots, remote images, or generated assets.

## Sprint 19D Dark Premium Redesign

Sprint 19D redesigns the page as a dark premium landing page while keeping it static and original. The page now emphasizes:

- Dark high-contrast hero treatment.
- Local-first AI command center identity.
- Voice, terminal, dashboard, memory/project continuity, app-shell direction, and safe action roadmap.
- Static terminal/dashboard/app-shell/voice preview cards.
- Original Artemis field notes instead of fake corporate testimonials.
- A short story section explaining why Artemis exists.

Odysseus is treated as high-level inspiration for polish and structure only. Do not copy its code, text, assets, branding, exact layout, or product identity.

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

## Public Site Copy

After validation in this private Artemis repo, copy these files to the public `peotnilsson/artemis-site` repo:

- `website/index.html`
- `website/styles.css`
- `website/.nojekyll`
- `website/README.md`

The public site repo is the public-facing website surface. The Artemis core repo remains private while the project is under development.

## Disabling Deployment

To disable deployment, turn off GitHub Pages in the repository settings or disable the `Deploy static website to GitHub Pages` workflow in GitHub Actions. Removing or renaming `.github/workflows/pages.yml` also stops future workflow deployments.
