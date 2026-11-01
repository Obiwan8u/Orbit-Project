# Orbit

Orbit is a frontend-only Education & Institute Management System prototype. It is designed to run from VS Code with Live Server and uses HTML5, CSS3, vanilla JavaScript, and `localStorage` only.

## Current phase

Phase 2 establishes the reusable CSS system and mock authentication. The role-aware dashboard is intentionally deferred until Phase 3 is approved.

## Planned entry points

- `index.html` — startup route and authenticated-session redirect
- `login.html` — mock authentication
- `register.html` — mock account sign-up
- `pages/` — protected application views

Open `index.html` with Live Server. Demo accounts use the password `Orbit@123`; this is mock browser-only data, never real authentication.

## Repository layout

```text
Orbit/
├── assets/                 # Local images, icons, and optional web fonts
├── css/                    # Design tokens, shared components, layouts, responsiveness
├── docs/                   # Architecture and visual-system decisions
├── js/                     # Framework-free modules grouped by responsibility
├── pages/                  # Application pages after authentication
├── README.md
└── index.html              # Added in Phase 2
```

Detailed decisions are in [docs/architecture.md](docs/architecture.md) and [docs/design-system.md](docs/design-system.md).
