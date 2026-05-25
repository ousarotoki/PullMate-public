# PullMate

> Chrome extension that supercharges GitHub pull request reviews with a persistent sidebar, progress tracking, file filtering, bot comment hiding, review checklists, time tracking, and private inline notes.

[**Visit the landing page &rarr;**](https://ousarotoki.github.io/PullMate-public/)

## Features

- **Persistent Review Sidebar** — progress tracker, time tracker, and quick actions on every PR
- **Review Progress Tracker** — syncs with GitHub's "Viewed" toggle; shows progress in sidebar
- **File Filter Panel** — reviewed / unreviewed / pending sections with click-to-navigate
- **Bot Comment Filter** — hide bot noise with one click or `Alt+B`
- **Pending Comment Badge** — never forget to submit your review
- **Review Checklist** — built-in templates (General, Security, Performance) with custom checklists
- **Private Inline Notes** *(Pro)* — add notes on diff lines; Markdown export
- **Review Time Tracker** *(Pro)* — auto-track time spent per PR with idle detection
- **Keyboard Shortcuts** — `Alt+N/P/M/B/T/C` — fully configurable
- **Dark Mode** — syncs with GitHub's theme automatically
- **Onboarding Tour** — 5-step walkthrough on first install

## Quick Start

1. Install from the [Chrome Web Store](#) (coming soon)
2. Open any GitHub pull request
3. The PullMate sidebar appears automatically on the right

## Development

```bash
npm install
cp .env.example .env   # configure SENTRY_DSN and store URLs
npm run build          # produces dist/
npm run dev            # watch mode
npm test               # Jest with coverage
npm run lint           # ESLint
npm run format         # Prettier
```

Load `dist/` as an unpacked extension in Chrome (`chrome://extensions` → Load unpacked).

## Tech Stack

Chrome Extension Manifest V3, React 18, Webpack 5, Babel, Sentry, Lemon Squeezy, Jest + Playwright.
