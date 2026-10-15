# Fuverse

Interactive personal-future tools built with React + Vite — Life tracker, Time Machine, Mind Mode and more.

[![Vite](https://img.shields.io/badge/Vite-Ready-brightgreen)](https://vitejs.dev/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> A small suite of reflective and planning experiences to help you design, track and imagine your future self.

Why Fuverse?
- Lightweight, approachable UI for journaling and goal tracking
- Visualizations (charts) to measure progress
- Print/export options and a playful time-machine UX

Quick Start
1. Install Node.js (v18+ recommended).
2. From the project root run:

```powershell
cd fuverse
npm install
```

3. Start the dev server:

```powershell
npm run dev
```

4. Build for production:

```powershell
npm run build
```

5. Preview the production build locally:

```powershell
npm run preview
```

Project layout
- `fuverse/` — front-end app (source code, build scripts)
- `fuverse/src` — React components and pages
- `fuverse/src/firebase` — Firebase config and utilities

Notes & Troubleshooting
- PowerShell `npm` execution policy error: run `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser -Force`.
- If the dev server reports a port (e.g. `http://localhost:5174/`), open that exact URL. Use `npm run dev -- --host` to expose on the LAN.
- If you see an embedded repository warning when committing, that means `fuverse/` was previously a nested Git repo — the top-level repo now contains the subfolder content.

Contributing
- PRs welcome. For UI changes include screenshots and a short description of the UX impact.

License
This project is released under the MIT License.

Maintainer
- Roshan Ejaz — roshanejaz786@gmail.com

---

Want me to add a GitHub Action that builds on push and deploys previews? Reply and I'll scaffold it.
