# Loot Containers Documentation

Official documentation website for **Loot Containers**, a Minecraft mod that gives server owners control over loot tables, rarity tiers, reward chances, and container assignments.

🌐 **[Visit the Documentation Website](https://firetiger369.github.io/LootContainers-Docs/)**

## About

This repository contains the source code for the Loot Containers documentation website.

The documentation covers:

- Getting Started and Installation
- Custom Loot Tables
- Rarity System
- Reward Odds and Pity
- Container Assignments
- Permissions
- Configuration Reference

## Website

The website is built using [Astro](https://astro.build/) and hosted through **GitHub Pages**.

It features a custom dark interface with translucent glass styling, blue-to-pink gradients, and responsive layouts.

## Project Structure

```text
LootContainers-Docs/
├── public/
│   └── images/
│       └── loot-containers-wordmark.png
├── src/
│   ├── layouts/
│   │   └── DocsLayout.astro
│   └── pages/
│       ├── index.astro
│       └── docs/
│           ├── getting-started/
│           ├── installation/
│           ├── loot-tables/
│           ├── rarities/
│           ├── odds-pity/
│           ├── container-assignments/
│           ├── permissions/
│           └── configuration-reference/
├── .github/
│   └── workflows/
│       └── deploy.yml
├── astro.config.mjs
└── package.json
```

## Running Locally

### Requirements

- [Node.js](https://nodejs.org/)
- npm

### Installation

Clone the repository:

```bash
git clone https://github.com/FireTiger369/LootContainers-Docs.git
```

Navigate into the project:

```bash
cd LootContainers-Docs
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local website at `http://localhost:4321`.

## Available Commands

| Command | Description |
|---|---|
| `npm run dev` | Start the local development server |
| `npm run build` | Build the production website |
| `npm run preview` | Preview the production build locally |
| `npm run astro ...` | Run Astro CLI commands |

## Deployment

The website is hosted using GitHub Pages.

Deployment is automated through GitHub Actions whenever changes are pushed to the `main` branch.

Production website:

**https://firetiger369.github.io/LootContainers-Docs/**

## Links

- **Documentation:** https://firetiger369.github.io/LootContainers-Docs/
- **GitHub Repository:** https://github.com/FireTiger369/LootContainers-Docs
- **Astro:** https://astro.build/

---

© 2026 Loot Containers. All rights reserved.