# README.md Guide

An interactive single-page reference tool for learning Markdown syntax — built for developers who want to write clean, well-structured README files.

Each section pairs the raw Markdown syntax with a live rendered preview, so you see exactly what your code will look like on GitHub.

---

## Features

- Side-by-side **Markdown source** and **rendered preview** for every syntax element
- Sticky right-hand navigation with active section highlighting as you scroll
- Fully **responsive** — collapses to a mobile-friendly layout with a slide-out nav drawer
- Syntax token colouring in code panes for easier reading
- Tip boxes highlighting common gotchas

## Sections Covered

| Category | Topics |
| -------- | ------ |
| Basics | Headings, Paragraphs & Line Breaks, Emphasis |
| Structure | Lists, Blockquotes, Horizontal Rules |
| Rich Content | Links, Images, Code (inline & fenced), Tables |
| Extended | Task Lists, Badges |

## Getting Started

No build step or dependencies required. Open `index.html` directly in any modern browser.

```bash
# Clone or download the project, then open in your browser
open index.html
```

Or drop it on any static host (GitHub Pages, Netlify, Vercel) and share the URL.

## File Structure

```
.
├── index.html      # Everything — HTML, CSS, and JS in one file
└── README.md       # This file
```

## Usage

1. Pick a topic from the **"On this page"** navigation panel on the right.
2. Read the **Markdown** pane to see the raw syntax.
3. Check the **Preview** pane to see how it renders.
4. Copy the syntax pattern into your own README.

On mobile, tap **☰ Contents** in the header to open the navigation drawer. Tapping any link closes it automatically.

## Responsive Behaviour

| Viewport | Layout |
| -------- | ------ |
| Desktop (> 1024px) | Full two-column layout with sticky side nav |
| Tablet (768–1024px) | Narrower nav, slightly reduced padding |
| Mobile (< 768px) | Single column, stacked panes, slide-down nav drawer |
| Small mobile (< 420px) | Further reduced font sizes and padding |

## Tech Stack

- Plain **HTML, CSS, JavaScript** — no frameworks or build tools
- Fonts: [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (code) + [Syne](https://fonts.google.com/specimen/Syne) (body) via Google Fonts
- Layout: CSS Grid and Flexbox
- Scroll tracking: `IntersectionObserver` API

## Contributing

1. Fork the repo
2. Add or improve a section in `index.html` following the existing `.lesson` card pattern
3. Open a pull request with a short description of what you changed

## License

MIT — free to use, modify, and share.
