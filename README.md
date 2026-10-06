# UIX-templates

Live UI animation templates — the 13 real effects extracted from
`AETHERION/ASSETS` (the other ~488 `Template-*` files are empty stubs).

## View the animations

Open `gallery.html` in any browser — all 13 effects play live, no build step:

```bash
open gallery.html
```

| # | Template file | Effect | Interaction |
|---|---------------|--------|-------------|
| 4 | `templates/Template-[4].txt` | DodgeField — button dodges the cursor | try to catch it |
| 5 | `templates/Template-[5].txt` | FolderFloat — notes float out of a folder | hover the folder |
| 6 | `templates/Template-[6].txt` | BorderGlow — cursor-following glow | move mouse over card |
| 7 | `templates/Template-[7].txt` | PixelCard — shimmering pixel field | move mouse over canvas |
| 8 | `templates/Template-[8].txt` | Dock — macOS-style magnification | move across icons |
| 9 | `templates/Template-[9].txt` | MagicBento — spotlight + tilt + stars | hover cells |
| 10 | `templates/Template-[10].txt` | Liquid Metal — animated metallic sheen | auto-plays |
| 11 | `templates/Template-[11].txt` | ElectricBorder — rotating electric edge | auto-plays |
| 12 | `templates/Template-[12].txt` | GlitchText — RGB-split glitch | auto-plays |
| 13 | `templates/Template-[13].txt` | WaveShader — sine waves + RGB split | auto-plays |
| 14 | `templates/Template-[14].txt` | TrueFocus — focus box sweeps words | auto-plays |
| 15 | `templates/Template-[15].txt` | DecryptedText — scramble-to-decrypt | hover to replay |
| 16 | `templates/Template-[16].txt` | SplitFlap — departure-board flip | auto-cycles |

## Source

Each file under `templates/` is the original React/JSX snippet verbatim;
`gallery.html` is a dependency-free (vanilla CSS/JS/Canvas) live rendering
of every effect so they can be seen without a React/Three.js toolchain.
