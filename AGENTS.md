# AGENTS.md

## Cursor Cloud specific instructions

### Product overview

This repository is a **static marketing site** for **Innere Souveränität** (German landing page). There is no backend, database, package manager, or build step. Production entry point is `index.html`; alternate React-in-browser drafts live at `dasdg.html`, `dsad.html`, `dsadas.html`, and `dsadasadd.html`.

### Services

| Service | Required | How to run |
|---------|----------|------------|
| Static HTTP server | Yes | `cd /workspace && python3 -m http.server 8080` |
| Outbound HTTPS | Yes (full UI) | Tailwind and (on draft pages) React/Lucide load from CDNs |

Use tmux for long-running dev servers (see cloud agent shell guidance). Open `http://localhost:8080/index.html` for the production-like page.

### Lint / test / build

There are **no** project-defined lint, test, or build commands (no `package.json`, ESLint, or bundler). CI only deploys the repo root to GitHub Pages via `.github/workflows/static.yml`.

Manual smoke checks on `index.html`:

1. Hero stats animate after load (`#stat-users`, `#stat-satisfaction`, `#stat-days`).
2. Scroll updates `#scroll-progress` width.
3. `#toggle-modules` expands/collapses `#modules-content`.
4. `#plan-basic` and `#plan-complete` update border/shadow/scale on click.
5. In-page anchors (`#pricing`, `#curriculum`) scroll smoothly.

Hotmart checkout links are external; purchase flow is out of repo scope.

### Secrets / environment

No `.env` or local secrets. GA4 measurement ID and Hotmart URLs are hardcoded in HTML. `GITHUB_TOKEN` is only used in GitHub Actions for Pages deploy.

### VM update script

No dependency install is required on startup. The registered update script is a no-op (`true`).
