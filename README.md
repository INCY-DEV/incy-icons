<div align="center">

# INCY Icons

**The official icon set used in INCY apps — free for everyone.**

A clean, hand-crafted SVG icon library shipped with the INCY clients (iOS, Android, Desktop, Web Panel) and now released for the community.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Format](https://img.shields.io/badge/format-SVG-orange.svg)](#)
[![Icons](https://img.shields.io/badge/icons-58-success.svg)](#)

</div>

---

## About

This repository contains the icons used across the INCY ecosystem — the same icons you see in the iOS, Android, and Desktop apps and on [incy.cc](https://incy.cc). They are released as plain SVGs so anyone can drop them into their own project: VPN clients, dashboards, control panels, websites, presentations.

**No attribution required. No tracking. No fonts to embed. No build step.**

## Highlights

- **58 SVG icons** — pure vector, infinitely scalable, no rasterization
- **Single style** — consistent stroke weight, corner radius, and visual rhythm
- **Drop-in ready** — open, copy, paste; no icon font, no JS, no React component
- **Theme-friendly** — most icons inherit `currentColor`, so they recolor with CSS
- **Cross-platform tested** — already shipping on iOS / Android / macOS / Linux / Windows / Web

## Quick start

### HTML

```html
<img src="path/to/INCY-00002.svg" width="24" height="24" alt="" />
```

### Inline (recolorable with CSS)

```html
<svg width="24" height="24" fill="currentColor">
  <use href="path/to/INCY-00002.svg#icon" />
</svg>
```

```css
.icon { color: #B8D94A; }      /* INCY accent green */
.icon:hover { color: #2ECC71; }
```

### React / Svelte / Vue

Most modern bundlers can import SVGs directly:

```tsx
import IconShield from './incy-icons/INCY-00002.svg?react';

<IconShield className="w-6 h-6 text-emerald-500" />
```

## Catalog

All icons live in the repository root, named `INCY-00001.svg` … `INCY-00058.svg`.
A visual gallery is coming soon — for now, GitHub renders SVGs directly: just open any file to preview it.

## Used by

If you build something with these icons, open a PR and add it here.

## License

MIT — do whatever you want, including in commercial products.
Attribution is appreciated but never required.

See [LICENSE](LICENSE) for the full text.

## Contributing

Spotted a missing icon, an inconsistency, or an off-by-one stroke? Open an issue or a PR. Please:

- Keep the visual style consistent with existing icons (stroke weight, corner radius, padding)
- Use a 24×24 viewBox unless there's a reason not to
- Avoid embedded raster images — SVG path data only
- Run the file through [SVGO](https://github.com/svg/svgo) before submitting

## Links

- Website — [incy.cc](https://incy.cc)
- Telegram — [@incydvp](https://t.me/incy_public)
- Issues — [GitHub Issues](../../issues)

---

<div align="center">
Made with care by the INCY team.
</div>
