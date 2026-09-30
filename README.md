# Antipodes

A custom dark Omarchy theme, built around three personal
photographs:

- **Boat** — a dark hull under dusk water, slate and ice-blue
- **Mist** — olive meadow under a pale, hazy sky
- **Coast** — a rocky shoreline meeting a calm sea under a clear blue sky

The palette takes its deep slate surfaces, glacier-blue accent, and sage/sand
neutrals from those images. Active window borders, tooltips, and menus use a
bright pale ice (`#F2F8FC`) for maximum contrast against both the dark window
surface and the misty wallpapers; inactive window borders sit at a mid-steel
blue (`#64809A`) so focus state is always unambiguous.

Icon theme: Yaru-blue-dark

## Files

| File | Purpose |
|------|---------|
| `colors.toml` | Palette; drives Hyprland, shell, terminals, and every themed app |
| `backgrounds/` | The three source photographs (`01-boat.jpg`, `02-mist.jpg`, `03-coast.jpg`) |
| `icons.theme` | Yaru-blue-dark icon set |
| `preview.png` | Theme-picker image: a real screenshot of a themed desktop |
| `preview-unlock.png` / `unlock.png` | Lock-screen images derived from the photos |

## Install

Via Omarchy:

```bash
omarchy theme install git@github.com:kabucey/omarchy-antipodes-theme.git
omarchy theme set Antipodes
```

…or clone into `~/.config/omarchy/themes/antipodes` and run
`omarchy theme set Antipodes`.
