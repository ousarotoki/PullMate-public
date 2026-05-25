# PullMate

> Chrome extension that supercharges GitHub pull request reviews with a persistent sidebar, progress tracking, file filtering, bot comment hiding, and private inline notes.

[**Visit the landing page &rarr;**](./landing/index.html)

## Features

- **Review Progress Tracker** — Syncs with GitHub's "Viewed" toggle; shows progress in sidebar
- **File Filter Panel** — Reviewed / Unreviewed / Pending sections with click-to-navigate
- **Bot Comment Filter** — Hide bot noise with one click or `Alt+B`
- **Pending Comment Badge** — Never forget to submit your review
- **Keyboard Shortcuts** — `Alt+N/P/M/B/T` — fully configurable
- **Private Inline Notes** *(Pro)* — Add notes on diff lines; Markdown export

## Quick Start

1. Install from the [Chrome Web Store](#) (coming soon)
2. Open any GitHub pull request
3. The PullMate sidebar appears automatically on the right

## Development

```bash
npm install
npm run build   # builds dist/
npm run dev     # watch mode
npm test        # Jest with coverage
```

Built with: React 18, Chrome Manifest V3, Webpack 5, Jest + Playwright.
