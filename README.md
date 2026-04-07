# styletmpdev

A minimal, eye-friendly CSS framework for development. Inspired by GitHub Dark Mode.

## Features

- Dark, readable color scheme (GitHub-inspired, not pure black)
- Monospace font for code-like interfaces
- Minimal CSS (< 500 chars) - low conflict risk
- Clean tables, forms, and typography
- Easy to inject and remove

## Usage

Copy the `<style>` block into your HTML or PHP `</body>` tag:

```html
<style>
body{background:#0d1117;color:#c9d1d9;font-family:monospace;margin:0;padding:20px;line-height:1.6}table{width:100%;border-collapse:collapse;margin:20px 0}th{background:#161b22;color:#c9d1d9;padding:12px;text-align:left;border-bottom:1px solid #30363d;font-weight:normal}td{padding:12px;border-bottom:1px solid #30363d}a{color:#58a6ff;text-decoration:none}h1,h2,h3{color:#c9d1d9;font-weight:normal;margin-top:24px}
</style>
```

Or include via file in your dev folder.

## Why?

Perfect for quick prototyping, admin panels, and learning projects. No setup overhead, no framework bloat, no CSS conflicts.

## Design Principles

- **Dark, not harsh**: GitHub-inspired grays, not pure black
- **Monospace by default**: Makes dev UIs feel intentional
- **Minimal selectors**: Fewer conflicts with production CSS
- **No framework dependencies**: Vanilla CSS only
- **Temporary-first**: Designed to be removed without traces

## Color Palette

- Background: `#0d1117` (near-black)
- Text: `#c9d1d9` (light gray)
- Links: `#58a6ff` (GitHub blue)
- Borders: `#30363d` (subtle dark gray)
- Table headers: `#161b22` (slightly lighter than background)

## License

MIT

