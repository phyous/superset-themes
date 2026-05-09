# Superset Themes

A curated collection of 30 themes for [superset.sh](https://superset.sh), ported from popular coding color schemes.

## Installation

1. Open Superset → Settings → Appearance → Theme
2. Import any `.json` file from the `themes/` folder
3. Select the imported theme to apply it

You can also import multiple themes at once by wrapping them in an array or `{ "themes": [...] }`.

---

## Dark Themes

Classic dark backgrounds with carefully balanced contrast and syntax colors.

| Theme | Accent | File |
|-------|--------|------|
| **Catppuccin Mocha** | Pastel blue | [`catppuccin-mocha.json`](themes/catppuccin-mocha.json) |
| **Dracula** | Vibrant purple | [`dracula.json`](themes/dracula.json) |
| **Tokyo Night Storm** | Cool blue | [`tokyo-night-storm.json`](themes/tokyo-night-storm.json) |
| **Nord** | Frost cyan | [`nord.json`](themes/nord.json) |
| **Gruvbox Dark** | Warm yellow | [`gruvbox-dark.json`](themes/gruvbox-dark.json) |
| **One Dark** | Soft blue | [`one-dark.json`](themes/one-dark.json) |
| **Solarized Dark** | Precise blue | [`solarized-dark.json`](themes/solarized-dark.json) |
| **Kanagawa** | Ink blue | [`kanagawa.json`](themes/kanagawa.json) |
| **Everforest Dark** | Forest green | [`everforest-dark.json`](themes/everforest-dark.json) |
| **Ayu Dark** | Warm amber | [`ayu-dark.json`](themes/ayu-dark.json) |

## Light Themes

Bright backgrounds for daytime use, with readable contrast and vibrant accents.

| Theme | Accent | File |
|-------|--------|------|
| **Catppuccin Latte** | Vivid blue | [`catppuccin-latte.json`](themes/catppuccin-latte.json) |
| **Solarized Light** | Precise blue | [`solarized-light.json`](themes/solarized-light.json) |
| **Gruvbox Light** | Earthy orange | [`gruvbox-light.json`](themes/gruvbox-light.json) |
| **Tokyo Night Day** | Bright blue | [`tokyo-night-day.json`](themes/tokyo-night-day.json) |
| **One Light** | Clean blue | [`one-light.json`](themes/one-light.json) |
| **Everforest Light** | Natural green | [`everforest-light.json`](themes/everforest-light.json) |
| **Rose Pine Dawn** | Iris purple | [`rose-pine-dawn.json`](themes/rose-pine-dawn.json) |
| **GitHub Light** | GitHub blue | [`github-light.json`](themes/github-light.json) |
| **Nord Light** | Arctic blue | [`nord-light.json`](themes/nord-light.json) |
| **Ayu Light** | Warm orange | [`ayu-light.json`](themes/ayu-light.json) |

## Alt Themes

Distinctive color palettes with unique character — from neon synthwave to muted ink washes.

| Theme | Accent | File |
|-------|--------|------|
| **Rose Pine** | Iris purple | [`rose-pine.json`](themes/rose-pine.json) |
| **Rose Pine Moon** | Iris purple | [`rose-pine-moon.json`](themes/rose-pine-moon.json) |
| **Monokai Pro** | Bright yellow | [`monokai-pro.json`](themes/monokai-pro.json) |
| **Catppuccin Macchiato** | Pastel blue | [`catppuccin-macchiato.json`](themes/catppuccin-macchiato.json) |
| **Catppuccin Frappe** | Soft blue | [`catppuccin-frappe.json`](themes/catppuccin-frappe.json) |
| **Synthwave '84** | Neon pink | [`synthwave-84.json`](themes/synthwave-84.json) |
| **Kanagawa Dragon** | Muted coral | [`kanagawa-dragon.json`](themes/kanagawa-dragon.json) |
| **Material Palenight** | Twilight blue | [`material-palenight.json`](themes/material-palenight.json) |
| **Night Owl** | Accessible blue | [`night-owl.json`](themes/night-owl.json) |
| **Horizon** | Sunset pink | [`horizon.json`](themes/horizon.json) |

---

## Customizing

Each theme file is standalone JSON. Fork any theme as a starting point for your own:

```bash
cp themes/dracula.json themes/my-theme.json
```

Edit the `id`, `name`, and colors to taste, then import into Superset.

## Theme Structure

```
├── ui        — App chrome: backgrounds, borders, sidebar, charts, highlights
└── terminal  — Integrated terminal: 16 ANSI colors, cursor, selection
```

See the [Superset docs](https://docs.superset.sh/custom-themes) for the full color key reference.
