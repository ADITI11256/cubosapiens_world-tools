# Contributing to CuboSapiens Tools & Games

Thank you for contributing to the CuboSapiens ecosystem 

This document explains how to contribute browser based:
- tools
- games
- UI improvements
- standalone applications

---

# Project Philosophy

CuboSapiens focuses on:
- lightweight browser tools
- HTML5 games
- open source collaboration
- beginner friendly contributions
- modular project architecture
- atmost privacy with no data collected from the user (**except few cookies for google AdSense **)

Most tools and games are intentionally kept standalone and simple for easier community participation.

---

# Tools & Games Directory Structure

Tools and games are located inside:

```txt
Applications/
 ├── Tools/
 ├── Games/
```

Example:

```txt
Applications/Games/cubosapiens-games-snake
Applications/Games/cubosapiens_HP_quiz

Applications/Tools/cubosapiens_qr_generator
Applications/Tools/cubosapiens_markdown_editor
```

---

# Standard Project Structure

Most standalone tools and games should follow this structure:

```txt
index.html
style.css
script.js
README.md
assets/
```

### Structure Explanation

| File/Folder | Purpose |
|---|---|
| `index.html` | Main application/game structure |
| `style.css` | Styling and responsiveness |
| `script.js` | Logic and functionality |
| `README.md` | Project description and usage |
| `assets/` | Images, icons, sounds, fonts, etc |

---

# Running Projects Locally

We recommend using:
- VS Code
- Live Server Extension

## Steps

1. Open the project folder
2. Right click `index.html`
3. Click `Open with Live Server`

---

# Allowed Technologies

Preferred technologies:

- HTML5
- CSS3
- JavaScript
- Tailwind CSS
- Font Awesome

Avoid:
- unnecessary frameworks for small projects
- heavy dependencies for simple tools/games

---

# UI & Design Guidelines

Contributors should maintain:
- responsive design
- clean layouts
- accessibility
- smooth interactions
- modern UI/UX
- dark mode compatibility where possible

Please avoid:
- cluttered interfaces
- excessive animations
- inconsistent color schemes

---

# Icon Guidelines

Use:
- Font Awesome icons

Avoid:
- emojis inside UI components

---

# Tool Contribution Guidelines

Tools should:
- provide useful browser functionality
- remain lightweight
- work properly across browsers
- maintain responsive design
- avoid unnecessary complexity
- if needed use local persistent storage or cache for user preferences

Examples:
- calculators
- converters
- editors
- generators
- developer tools
- AI utilities

---

# Game Contribution Guidelines

Games should:
- work directly in the browser
- support proper keyboard/mouse interactions
- remain optimized
- avoid malicious scripts or ads
- provide responsive layouts where possible

Examples:
- puzzle games
- arcade games
- quiz games
- multiplayer browser games
- strategy games

---

# Pull Request Rules

## IMPORTANT

- Raise PRs only against the `dev` branch
- Link the PR with the related issue
- Keep PRs focused and modular
- Avoid unrelated changes

---

# Required PR Attachments

Every PR must include:
- screenshots
- demo video/GIF for UI changes
- issue reference

PRs without proper proof may be closed until updated.

---

# package-lock.json Rules

Avoid unnecessary modifications to:
- `package-lock.json`

Only update it when:
- adding dependencies
- updating packages
- dependency fixes are required

---

# Asset Guidelines

Assets should:
- remain optimized
- be properly organized inside `/assets`
- avoid copyrighted material

Preferred formats:
- SVG
- WebP
- optimized PNG

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

# Repository

https://github.com/rk192324217/cubosapiens_world-tools

If you find this project useful, consider starring the repository ⭐

Thank you for contributing to CuboSapiens