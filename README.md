# trail Design System

Pages: https://mkmlman.github.io/trail/

## Contents

| File | Purpose |
|------|---------|
| `tokens.css` | Design tokens as CSS custom properties (colors, typography, spacing, radii, shadows) |
| `components.css` | Reusable component classes (cards, lists, stats, buttons, tabs, pills) |
| `index.html` | Interactive documentation page (open in browser) |

## Quick start

```html
<link rel="stylesheet" href="tokens.css">
<link rel="stylesheet" href="components.css">
```

```css
@import url("tokens.css");
@import url("components.css");
```

All tokens are on `:root` — override any value to customize:

```css
:root {
  --sr-accent: #0891b2;
  --sr-radius-lg: 12px;
}
```

MIT — see [LICENSE](LICENSE).

## Design principles

- **Dark first**: zinc-900 background, light text, no light mode
- **Data dense**: tight spacing, monospace for values, serif for hierarchy
- **Minimal decoration**: no shadows, thin borders, translucent surfaces
- **One accent**: single violet accent for interactive elements
