# CUBOSAPIENS — Free Tools, Games & AI

> One platform. Free tools, games and AI for everyone.
> No signup. No cost. Always free.

🌐 **Live:** [cubosapiens.world](https://cubosapiens.world)

## What is CUBOSAPIENS?

A growing collection of free browser-based tools, games and AI
built for everyone on the internet. All processing happens in
your browser — we never upload or store your files.

## Tech Stack

| Layer     | Technology                    |
|-----------|-------------------------------|
| Frontend  | Next.js 15, TypeScript        |
| Styling   | Tailwind CSS v4, Custom CSS   |
| Backend   | Hono.js on Cloudflare Workers |
| Database  | PostgreSQL (Supabase)         |
| ORM       | Prisma 6                      |
| Hosting   | Cloudflare Pages + Workers    |
| Monorepo  | Turborepo                     |

## Live Tools

| Tool            | URL                                    |
|-----------------|----------------------------------------|
| GPS CAM         | gps-cam.cubosapiens.world              |
| QR Generator    | qr.cubosapiens.world                   |

## Project Structure

\`\`\`
cubosapiens/
├── apps/
│   ├── web/        ← Next.js frontend
│   └── api/        ← Hono.js REST API
└── packages/
    └── shared/     ← Shared TypeScript types
\`\`\`

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md)

## GirlScript Summer of Code 2025

This project is participating in GSSoC 2025.
Check [Issues](https://github.com/rk192324217/cubosapiens_world-tools/issues)
for tasks labeled `gssoc`.

## License

MIT License — see [LICENSE](./LICENSE)
## Browser Based Tools & Games Ecosystem

CuboSapiens also includes a growing ecosystem of standalone browser based:

- Tools
- Games
- AI Experiments
- Productivity Applications
- Developer Utilities

These projects are designed to be:
- lightweight
- beginner friendly
- modular
- contribution friendly

Most projects are built using:
- HTML5
- CSS3
- JavaScript

---

## Applications Structure

```txt
Applications/
 ├── Tools/
 │    ├── cubosapiens_qr_generator/
 │    ├── cubosapiens_markdown_editor/
 │    ├── cubosapiens_password_gen/
 │
 ├── Games/
 │    ├── cubosapiens-games-snake/
 │    ├── cubosapiens-games-chess/
 │    ├── cubosapiens_HP_quiz/
```

Each project is generally structured as:

```txt
index.html
style.css
script.js
README.md
assets/
```

---

## Running Standalone Tools & Games Locally

Most standalone tools and games can be run locally using VS Code Live Server.

### Steps

1. Open the specific tool/game folder
2. Right click `index.html`
3. Click `Open with Live Server`

---

## Contributing to Tools & Games

Contributors can:
- improve existing tools
- redesign UIs
- optimize responsiveness
- improve accessibility
- create entirely new browser based tools and games

Please read:
- `CONTRIBUTING.md`
- `CONTRIBUTING_TOOLS.md`

before contributing.

---

## GSSoC 2026 Labels & Contribution System

This repository follows the GSSoC 2026 label system.

### Core Labels

| Label | Purpose |
|---|---|
| `gssoc:approved` | Approved PR |
| `level:beginner` | Beginner friendly issues |
| `level:intermediate` | Moderate complexity |
| `level:advanced` | Advanced contributions |
| `level:critical` | Core/high impact contributions |

### Type Labels

| Label | Purpose |
|---|---|
| `type:bug` | Bug fixes |
| `type:feature` | New features |
| `type:design` | UI/UX changes |
| `type:performance` | Performance optimization |
| `type:security` | Security related improvements |

---

## Contribution Rules

- Raise PRs only against the `dev` branch
- Attach screenshots/videos for UI changes
- Use Font Awesome icons instead of emojis in UI components
- Avoid unnecessary changes to `package-lock.json`
- Keep contributions modular and focused

---

## Support the Project

If you find this project useful, consider starring the repository ⭐

https://github.com/rk192324217/cubosapiens_world-tools