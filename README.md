# Amber Console

**This Omarchy theme is a tribute to [DutchDiederik](https://github.com/DutchDiederik)'s excellent [AmberConsole](https://github.com/DutchDiederik/AmberConsole) html/css framework.**

![Amber Console: application screenshots surrounding Cliamp and OpenCode](preview.jpg)

## Install

Tested on **Omarchy 4.0.2**.

```bash
omarchy theme install https://github.com/zigmoo/omarchy-amber-console-theme
```

Select it later through **Style → Theme**, or:

```bash
omarchy theme set amber-console
```

The theme appears as **Amber Console** in Omarchy's picker.

## One emitter, several intensities

AmberConsole takes its cues from hardware that could vary the brightness of a single emitter, rather than assign different hues to different meanings. This theme maps every named ANSI color to that same ramp. Errors, warnings and success states share it; text labels, symbols, intensity and inverse video carry the distinction.

| Role | Color |
| --- | --- |
| Panel | `#100600` |
| Highlight | `#ffa86d` |
| Primary text | `#ff6b08` |
| Secondary text | `#dd5800` |
| Dim border | `#ab4500` |
| Inverse text | `#1e0c00` |

The colors come from [AmberConsole's neon tokens](https://github.com/DutchDiederik/AmberConsole/blob/e616e1c04aaf65d67e485559745421c8226ec4b3/src/tokens/colors.css). This is the neon profile; AmberConsole's separate P3 amber CRT profile has a different ramp.

## What the theme changes

- `colors.toml` supplies the palette for Omarchy's generated application themes.
- `shell.toml` colors the bar, menus, launcher, notifications and related shell surfaces.
- `icons.theme` selects orange Yaru-dark folder icons.
- `backgrounds/` contains the IMAX photograph.

Fonts, layout, widgets and desktop behavior are inherited. The package contains no hooks, scripts, plugins or global configuration changes.

This is a small working palette and surface adaptation. Websites, images and independently styled truecolor output can still contain other colors; the theme does not simulate every hardware effect or typographic rule in the original design system.

## With thanks

- **[DutchDiederik / Diederik](https://diederik.blog)** — AmberConsole's original design, hardware research and palette. Please visit [AmberConsole](https://github.com/DutchDiederik/AmberConsole); it is the heart of this theme.
- **[Jesse Palmer](https://x.com/RealJessePalmer/status/2080690462269259848)** — the IMAX console photograph.
- **[Bjarne Øverli](https://github.com/bjarneo/omarchy-evergreen-theme)** and the Omarchy theme community — the straightforward repository and installation conventions.
- [@DHH](https://x.com/dhh) for the amazing [@OmarchyLinux](https://x.com/OmarchyLinux)!!

The upstream **BSD-3-Clause** notice is retained in [LICENSE](LICENSE) for the theme. The IMAX photograph retains its original rights and is not covered by that license. The current `preview.jpg` montage contains application screenshots. Preview source assets, recipes and photo-based examples are preserved on the `theme_comp_tooling_dil-2723` branch.
