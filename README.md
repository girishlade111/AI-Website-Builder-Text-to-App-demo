# AI Website Builder — Text-to-App Demo

A single-page, client-side demo of an AI-powered "text-to-app" website builder, in the spirit of Lovable or Bolt. Describe the site you want in plain text, provide your own LLM API key, and the app generates a working website — with a live preview tab, generated-code view, terminal/console panel, and ZIP export. Everything runs in the browser; no build step, no backend.

## Features

- **Prompt-to-site UI** — type a request like "Portfolio with dark mode" or "Landing page for SaaS" and hit Generate; includes quick prompt chips
- **Prompt enhancer** — one-click prompt refinement before generation
- **Preview / Code tabs** — toggle between the live generated site and its generated code
- **Code panel** — read-only code editor view with copy-to-clipboard
- **Terminal & console panels** — built-in terminal toggle, console log view, clear/close controls
- **Export ZIP** — download the generated site as a ZIP archive
- **BYO API key** — the API key field accepts your own key at runtime; no keys are stored or committed
- Dark, minimal UI (Tailwind-style zinc palette)

## Tech Stack

- HTML5
- CSS3 (utility classes, dark theme)
- Vanilla JavaScript — all logic inline in `index.html`

## Quick Start

No installation required:

1. Clone this repository:
   ```bash
   git clone https://github.com/girishlade111/AI-Website-Builder-Text-to-App-demo.git
   ```
2. Open `index.html` in a browser (or serve it statically):
   ```bash
   npx serve .
   ```
3. Enter your own LLM API key in the API KEY field, describe the site you want, and press Generate.

> Note: this is a UI/demo front end — generation calls are made from the browser using the key you supply. Never commit your API key to the repo.

## Project Structure

```
AI-Website-Builder-Text-to-App-demo/
├── index.html   # Complete app — markup, styles, and builder logic all inline
└── README.md    # This file
```

## Deployment

Deployed via GitHub Pages from the `main` branch (root path), so every push to `main` updates the live demo.

## Author

Built by Girish Lade — https://ladestack.in
