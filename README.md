# Japan Night — Kyoto Andon

Lantern amber and plum shadows on a rain-polished Kyoto lane. A dark companion theme for [Omarchy](https://omarchy.org/), part of the [Japan Night](https://github.com/devgtv/omarchy-japan-night-theme) collection.

[![A quiet sky above a traditional Kyoto street, with warm lanterns, wooden facades and reflections on wet stone.](backgrounds/kyoto-andon.jpg)](backgrounds/kyoto-andon.jpg)

## Install

```bash
omarchy theme install https://github.com/devgtv/omarchy-japan-night-kyoto-andon-theme.git
```

Omarchy installs and applies the theme. To switch back to it later:

```bash
omarchy theme set japan-night-kyoto-andon
```

## Wallpaper and bar

A quiet sky above a traditional Kyoto street, with warm lanterns, wooden facades and reflections on wet stone. The original illustration is 3840 × 2160; its upper eighth is quiet, dark sky so a top bar does not obscure the main scene. `colors.toml` supplies the Omarchy palette and `waybar.css` defines matching foreground and background colours for Waybar setups.

The [editable SVG master](artwork/kyoto-andon.svgz) can be rendered at other resolutions. For example, with librsvg:

```bash
gzip -dc artwork/kyoto-andon.svgz | rsvg-convert -w 5120 -h 2880 > kyoto-andon.png
```

## More themes

See the [Japan Night collection](https://github.com/devgtv/omarchy-japan-night-theme#night-journeys) for the other Night Journeys variants.
