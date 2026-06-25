# Pourtek Design System v2

## Core Colors

| Token | Hex |
|---|---|
| Primary Blue | `#278bcb` |
| Dark | `#262626` |
| Mid Gray | `#676767` |
| Background | `#f1f0f0` |
| White | `#ffffff` |

---

## Blue Scale

| Token | Hex | Swatch |
|---|---|---|
| `--blue-50` | `#eef6fc` | |
| `--blue-100` | `#d8edf8` | |
| `--blue-200` | `#a8d5ef` | |
| `--blue-300` | `#6db8e0` | |
| `--blue-400` | `#3f9ed4` | |
| `--blue-500` | `#278bcb` | ★ Primary |
| `--blue-600` | `#1f76b3` | |
| `--blue-700` | `#1a6499` | |

`#eef6fc` → `#d8edf8` → `#a8d5ef` → `#6db8e0` → `#3f9ed4` → `#278bcb` → `#1f76b3` → `#1a6499`

---

## Dark Scale

| Token | Hex |
|---|---|
| `--dark-600` | `#404040` |
| `--dark-700` | `#333333` |
| `--dark-800` | `#262626` | ★ Primary Dark |
| `--dark-900` | `#1a1a1a` |

`#404040` → `#333333` → `#262626` → `#1a1a1a`

---

## Gray Scale

| Token | Hex |
|---|---|
| `--gray-50` | `#f4f4f4` |
| `--gray-100` | `#e8e8e8` |
| `--gray-200` | `#d4d4d4` |
| `--gray-300` | `#b8b8b8` |
| `--gray-400` | `#9e9e9e` |
| `--gray-500` | `#808080` |
| `--gray-600` | `#676767` | ★ Mid Gray |

`#f4f4f4` → `#e8e8e8` → `#d4d4d4` → `#b8b8b8` → `#9e9e9e` → `#808080` → `#676767`

---

## Semantic Roles

| Role | Token | Hex |
|---|---|---|
| Background base | `--offwhite` | `#f1f0f0` |
| Brand primary | `--dark-800` | `#262626` |
| Brand accent | `--blue-500` | `#278bcb` |
| Foreground primary | `--dark-800` | `#262626` |
| Foreground secondary | `--gray-600` | `#676767` |
| Interactive primary | `--blue-500` | `#278bcb` |
| Interactive hover | `--blue-400` | `#3f9ed4` |
| Interactive press | `--blue-700` | `#1a6499` |
| Border default | `--gray-200` | `#d4d4d4` |
| Border accent | `--blue-500` | `#278bcb` |

---

## Typography

| Role | Font | Fallback |
|---|---|---|
| Display / Headers | Barlow Condensed | Arial Narrow, sans-serif |
| Body | Plus Jakarta Sans | Helvetica Neue, sans-serif |
| Mono / Data | JetBrains Mono | Courier New, monospace |

### Font Weights
- Regular: `400`
- Medium: `500`
- Semibold: `600`
- Bold: `700`
- Extrabold: `800`

---

## Shadows

```css
--shadow-1: 0 1px 3px rgba(0,0,0,0.08), 0 1px 2px rgba(0,0,0,0.04);
--shadow-2: 0 4px 12px rgba(0,0,0,0.08), 0 2px 4px rgba(0,0,0,0.04);
--shadow-3: 0 12px 32px rgba(0,0,0,0.10), 0 4px 8px rgba(0,0,0,0.06);
--shadow-4: 0 24px 64px rgba(0,0,0,0.14), 0 8px 16px rgba(0,0,0,0.08);
--shadow-blue: 0 8px 24px rgba(39,139,203,0.25);
```

---

## Border Radius

| Token | Value |
|---|---|
| `--radius-sm` | `4px` |
| `--radius-md` | `6px` |
| `--radius-lg` | `10px` |
| `--radius-xl` | `14px` |
| `--radius-2xl` | `20px` |
| `--radius-pill` | `999px` |

---

## Utility Colors

| Name | Hex |
|---|---|
| Success | `#22c55e` |
| Error | `#ef4444` |
| Info | `#278bcb` |

---

## Brand Rules

- No em dashes in any copy
- No emojis in marketing materials
- No unverifiable stats
- No client name-drops in rep-agnostic footers
- Voicemail scripts: never open with name — lead with problem or hook
- Primary one-pager file: `pourtek-interactive-one-pager.html`
