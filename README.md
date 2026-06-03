# Artemis Website Scaffold

This folder contains the inert static website scaffold for Sprint 19A, Sprint 19B, Sprint 19C, Sprint 19D, Sprint 22B, and Sprint 25B.

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
- Full-page navy/charcoal background with no white or cream section/card backgrounds.
- Muted cyan primary accents and muted pink secondary accents.
- Dark glass panels for terminal, dashboard, app-shell, voice, feature, roadmap, and get-started cards.
- Local-first AI command center identity.
- Voice, terminal, dashboard, memory/project continuity, app-shell direction, and safe action roadmap.
- Static terminal/dashboard/app-shell/voice preview cards.
- Original Artemis field notes instead of fake corporate testimonials.
- A short story section explaining why Artemis exists.

Odysseus is treated as high-level inspiration for polish and structure only. Do not copy its code, text, assets, branding, exact layout, or product identity.

## Sprint 22B Brand Mark Consistency

Sprint 22B brings the app-shell Artemis mark direction into the static website source. The header and hero use an inline SVG/CSS mark: dark rounded field, muted cyan crescent moon, simple terminal cursor, and one tiny dampened crimson safety node. The nav wordmark uses `ARTEMIS` with the local Space Mono / JetBrains Mono fallback stack.

This is still static website source only. It adds no logo files, raster files, external images, remote assets, external fonts, scripts, analytics, tracking, build tooling, backend behavior, and no copied competitor branding.

## Sprint 25B Unified Dark Interface Visual System

Sprint 25B redesigns the website around the same interface language as the Tauri app shell: near-black/navy background, CSS-only dotted grid, subtle contour lines, soft purple/cyan glow, dark glass cards, inline Artemis mark, and `ARTEMIS` wordmark. The primary accent is purple, the technical accent is cyan, and the dampened crimson mark remains a tiny safety/action node.

The page structure now focuses on a polished local AI product surface: centered hero, sticky nav with Features/About/How it works/Docs/GitHub, Chat/Memory/Voice/Models/Files/Settings cards, static interface panels, story terminal, field notes/design principles, roadmap, docs/resources, get-started panel, and footer.

This is still HTML/CSS only. Sprint 25B adds no scripts, generated image assets, raster assets, logo files, external images, remote assets, external fonts, dependencies, build tooling, backend behavior, analytics, tracking, app action controls, runtime controls, model calls, microphone/screen behavior, settings writes, installer, updater, or copied competitor branding.

## Public Site Deployment

Expected public URL:

`https://peotnilsson.github.io/artemis-site/`

Deployment path:

- Source repo: private `peotnilsson/artemis`
- Source folder: `website/`
- Public deployment repo: `peotnilsson/artemis-site`
- Public Pages source: the static copy in `artemis-site`
- Build step: none
- Runtime/server step: none
- Secrets: none
- Private repo Pages workflow: none required

The private Artemis repo remains the source of truth for website files, docs, and tests. The public-facing site is deployed from the separate public `peotnilsson/artemis-site` repo after manually copying the static files listed below. Do not make the private Artemis repo public just for Pages. Do not re-add a private repo `.github/workflows/pages.yml` workflow unless the deployment strategy changes.

## Updating The Site

Edit the static files in `website/`, validate them in the private Artemis repo, then manually copy the approved files to the public `peotnilsson/artemis-site` repo.

Keep updates within the same safety boundary: no scripts, no analytics, no tracking pixels, no remote assets, no external fonts, no package manager, no build system, and no app/action controls.

## Public Site Copy

After validation in this private Artemis repo, copy these files to the public `peotnilsson/artemis-site` repo:

- `website/index.html`
- `website/styles.css`
- `website/.nojekyll`
- `website/README.md`

The public site repo is the public-facing website surface. The Artemis core repo remains private while the project is under development.

## Disabling Deployment

To disable deployment, turn off GitHub Pages or pause publishing in the public `peotnilsson/artemis-site` repo. The private Artemis repo has no Pages workflow to disable.
