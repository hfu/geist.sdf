# geist.sdf
Geist Sans and Geist Mono fontstack for MapLibre GL JS

# Available fonts
- Geist Black
- Geist Bold
- Geist ExtraBold
- Geist ExtraLight
- Geist Light
- Geist Medium
- Geist Regular
- Geist SemiBold
- Geist Thin
- Geist Mono Black
- Geist Mono Bold
- Geist Mono Light
- Geist Mono Medium
- Geist Mono Regular
- Geist Mono SemiBold
- Geist Mono Thin
- Geist Mono UltraBlack
- Geist Mono UltraLight

# Usage instructions

To use Geist fonts with MapLibre GL JS, set the `glyphs` property in your `style.json` to the published SDF font URL, for example:

```json
"glyphs": "https://hfu.github.io/geist.sdf/{fontstack}/{range}.pbf"
```

Set the `text-font` property in your style layers to the desired font name, for example:

```json
"layout": {
  "text-font": ["Geist Mono Regular"]
}
```

# Copilot instructions
1. The pilot will be converting Geist Sand and Geist Mono using Font Maker and copy the output to the `docs` folder so that it can be used in MapLibre GL JS through GitHub Pages.
2. The copilot need to document the process of converting the fonts and using them in MapLibre GL JS.

# License
- The fonts are licensed under the SIL Open Font License, Version 1.1.
- See the LICENSE file for details.

# See also
- https://vercel.com/font
- https://github.com/vercel/geist-font/releases/tag/1.4.2
- https://maplibre.org/font-maker/
- https://github.com/maplibre/font-maker