# React Portfolio

![Status](https://img.shields.io/badge/status-coursework-blue)
[![License: MIT](https://img.shields.io/badge/license-MIT-green)](LICENSE)

Coursework portfolio prototype with project navigation, a skills section, and contact-form validation.

**Built with:** React, JavaScript, Vite, CSS.

## What I built

- Built a React portfolio with routed pages, reusable navigation, and project components.
- Implemented contact-form input state and validation.
- Created skills and resume views; the current resume link remains a placeholder.

## Explore the source

- [src/App.jsx](src/App.jsx) — Application structure and routing.
- [src/components/Portfolio/index.jsx](src/components/Portfolio/index.jsx) — Project gallery.
- [src/components/Contact/index.jsx](src/components/Contact/index.jsx) — Contact-form state and validation.

## Run locally

Requires Node.js/npm. From the repository root:

```bash
npm ci
npm run dev
```

Open the address printed by Vite.

## Checks

```bash
npm run build
npm run lint
```

## Current limits

The resume link is a placeholder. The contact form validates input and logs it locally; it does not deliver messages. This is a coursework prototype rather than the current professional portfolio.

Setup instructions were checked against source; builds and application behavior have not been rerun during this cleanup.

**License:** [MIT](LICENSE).
