# UIX-templates

Live UI animation templates — the 18 real effects ([4]–[21]).
`gallery.html` renders every one live with dependency-free vanilla code.

## View the animations

Open `gallery.html` in any browser — all 14 effects play live, no build step:

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
| 17 | `templates/Template-[17].txt` | TechText — dashed area reveal + specks + sweep | move mouse · drag text · click letter |
| 18 | `templates/Template-[18].txt` | StrokeText — staggered stroke-draw + wipe fill (working vanilla impl, live in gallery) | hover to replay |
| 19 | `templates/Template-[19].txt` | FuzzyText — row-displacement fuzz canvas (full impl, live in gallery) | hover to intensify |
| 20 | `templates/Template-[20].txt` | GradientText — animated gradient sweep, seamless loop (working vanilla impl, live in gallery) | auto-plays |
| 21 | `templates/Template-[21].txt` | BranchedMenu — tree menu with animated branch lines (working vanilla impl, live in gallery) | click groups / items |

## Source

Each file under `templates/` is the original React/JSX snippet verbatim;
`gallery.html` is a dependency-free (vanilla CSS/JS/Canvas) live rendering
of every effect so they can be seen without a React/Three.js toolchain.
