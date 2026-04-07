# styletmpdev

A minimal, eye-friendly CSS framework for development. Inspired by Commonplace.

## Features

- Light, readable color scheme (not pure white/black)
- Monospace font for code-like interfaces
- Minimal CSS (< 400 chars) - low conflict risk
- Clean tables, forms, and typography
- Easy to inject and remove

## Usage

Copy the `<style>` block into your HTML or PHP `</body>` tag:

```html
<style>
body{background:#f6f8fa;color:#24292e;font-family:monospace;margin:0;padding:20px;line-height:1.6}table{width:100%;border-collapse:collapse;margin:20px 0}th{background:#f3f3f3;color:#24292e;padding:12px;text-align:left;border-bottom:2px solid #e1e4e8;font-weight:normal}td{padding:12px;border-bottom:1px solid #e1e4e8}a{color:#0366d6;text-decoration:none}h1,h2,h3{color:#24292e;font-weight:normal;margin-top:24px}
</style>
```

Or include via file in your dev folder.

## Why?

Perfect for quick prototyping, admin panels, and learning projects. No setup overhead, no framework bloat, no CSS conflicts.

## Design Principles

- **Light on eyes**: Soft grays, not pure black
- **Monospace by default**: Makes dev UIs feel intentional
- **Minimal selectors**: Fewer conflicts with production CSS
- **No framework dependencies**: Vanilla CSS only
- **Temporary-first**: Designed to be removed without traces

## License

MIT
