# styletmpdev

A minimal, eye-friendly CSS framework for development. GitHub-flavored dark theme.

## Features

- Dark, readable color scheme (GitHub-flavored)
- Monospace font for code-like interfaces
- Minimal CSS (302 chars) - low conflict risk
- Clean tables, forms, and typography
- Easy to inject and remove

## Usage

Copy the `<style>` block into your HTML or PHP `</body>` tag:

```html
<style>
body{background:#222830;color:#d2d7df;font-family:monospace;padding:20px}table{width:100%;border-collapse:collapse;margin:20px 0}th,h4{color:#d2d7df}th{background:#222830;padding:12px}td,th{border-bottom:1px solid #3e444d}td{padding:12px}a{color:#9fc0fc}input,textarea,select,button{background:#2a3139;color:#d2d7df;border:1px solid #3e444d;padding:8px;font-family:monospace}button:hover{background:#3e444d}
</style>
```

Or include via file in your dev folder.

## Why?

Perfect for quick prototyping, admin panels, and learning projects. No setup overhead, no framework bloat, no CSS conflicts.

## Design Principles

- **Dark, not harsh**: GitHub-flavored grays, optimized for readability
- **Monospace by default**: Makes dev UIs feel intentional
- **Minimal selectors**: Fewer conflicts with production CSS
- **No framework dependencies**: Vanilla CSS only
- **Temporary-first**: Designed to be removed without traces

## Color Palette

- Background: `#222830` (dark gray)
- Text: `#d2d7df` (light gray)
- Links: `#9fc0fc` (GitHub-flavored blue)
- Borders: `#3e444d` (subtle dark gray)
- Inputs: `#2a3139` (form background)

## License

MIT
