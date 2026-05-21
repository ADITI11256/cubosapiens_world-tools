# Contributing to CUBOSAPIENS

Thank you for helping improve CUBOSAPIENS! This is a community-driven monorepo with a Next.js frontend, Cloudflare Workers API, and shared TypeScript packages.

---

## Code of Conduct

By participating, you agree to our [Code of Conduct](CODE_OF_CONDUCT.md). Be kind, constructive, and inclusive.

---

## Project Structure

The repository is a turborepo monorepo:

- `apps/web/` — Next.js frontend application
- `apps/api/` — Hono API running on Cloudflare Workers
- `packages/shared/` — shared TypeScript types and utilities

Root scripts are managed by Turbo.

---

## Local Setup

1. Install dependencies from the repo :

- Frontend:
  ```bash
  cd apps/web
  npm install
  npm run dev
  ```

- API:
  ```bash
  cd apps/api
  npm install
  npm run dev
  ```

---
## How to Contribute

1. **Find an issue**: browse [Issues](https://github.com/rk192324217/cubosapiens_world-tools/issues) or create one describing what you want to build.
2. **Comment** on the issue to claim it before starting, to avoid duplicate work.
3. **Fork** the repo and create a branch:
```bash
git checkout -b your-feature-or-issue-name
```
4. Make your changes in a focused branch.
5. **Test** your changes locally, including running the app and verifying any TypeScript or build errors.
6. **Open a PR** against `dev` and reference the issue.

---

## Pull Request Process

1. Test the changes locally before opening a PR.
2. Keep PRs focused: **one feature or fix per PR**.
3. Describe what changed, why it changed, and how to test it.
4. Link the PR to the related issue.
5. Respond to review feedback and update the same branch.
6. Attach screenshots/videos for UI changes
7. Use Font Awesome icons instead of emojis in UI components
8. Avoid unnecessary changes to `package-lock.json`
9. Keep PRs modular and focused

---

## Code Style and Quality

- Use TypeScript for new code where appropriate.
- Keep the existing project conventions: React/Next.js conventions in `apps/web`, and functional route handlers in `apps/api`.
- Keep changes small and easy to review.
- Avoid commit of blank lines.
- If you add new dependencies, ensure they are necessary.

---

## Testing

This repository does not currently include a dedicated test suite, so the best practice is to verify the app manually and confirm it builds.

Recommended checks before opening a PR:

- `npm install`
- `npm run dev` (for development)
- `npm run build` (to confirm the monorepo builds cleanly)

---

## Branch Naming

Use descriptive branch names, for example:

- `add-new-tool`
- `api-auth-bug`
- `update-contributing`

---

## Good First Contributions

Look for issues labeled `good first issue` or `gssoc`.

---

## Commit Style

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```bash
feat: add new tool card component
fix: correct API route response code
docs: update contributing guide
test: add unit tests for utility function
chore: bump dependency versions
```

---

## Tool & Game Contributions

This repository also contains standalone browser based tools and games inside:

```txt
Applications/
 ├── Tools/
 ├── Games/
```

Most projects follow this structure:

```txt
index.html
style.css
script.js
README.md
assets/
```

For tool/game specific contribution guidelines, please read:

`CONTRIBUTING_TOOLS.md`
[CONTRIBUTING_TOOLS.md](CONTRIBUTING_TOOLS.md)


---
---

# GSSoC 2026 Labels & Contribution System

This repository follows the GSSoC 2026 contribution label system.

## Core Labels

| Label | Purpose |
|---|---|
| `gssoc:approved` | Approved PR |
| `level:beginner` | Beginner friendly issues |
| `level:intermediate` | Moderate complexity |
| `level:advanced` | Advanced contributions |
| `level:critical` | Core/high impact contributions |

---

## Quality Labels

| Label | Purpose |
|---|---|
| `quality:clean` | Well structured implementation |
| `quality:exceptional` | Outstanding implementation |

---

## Type Labels

| Label | Purpose |
|---|---|
| `type:docs` | Documentation |
| `type:bug` | Bug fixes |
| `type:feature` | New features |
| `type:testing` | Testing improvements |
| `type:design` | UI/UX improvements |
| `type:refactor` | Code refactoring |
| `type:accessibility` | Accessibility improvements |
| `type:performance` | Performance optimization |
| `type:devops` | DevOps/CI/CD |
| `type:security` | Security related improvements |

---

# Important Note About Labels

Initially, every merged PR will receive:
- `gssoc:approved`

Additional:
- level
- quality
- type

labels may be added after maintainer review.

---
## Need Help?

If you are unsure how to proceed, ask in the issue thread or open a draft PR and mention the maintainers.

Thank you for contributing!

---