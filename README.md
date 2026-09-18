# Blobbington

A blob brush for the RoboFont glyph editor. Drag to paint with an oval brush. Strokes commit as clean, overlap-free outlines with smooth points. Click once to stamp a single dab.

## Install

1. Download `Blobbington.roboFontExt.zip` from this repo
2. Unzip it
3. Double-click `Blobbington.roboFontExt`
4. Quit RoboFont completely and reopen it

Blobbington appears in the glyph editor toolbar.

## Controls

The panel appears when you select the tool and closes when you switch away. Settings persist between sessions.

- **Fidelity** — Accurate keeps more of your hand movement, Smooth fits fewer points. Sharp corners are preserved at any setting.
- **Size** — brush diameter in font units
- **Angle** — rotation of the brush oval
- **Roundness** — 100% is a circle, lower values flatten the oval

Type a value into any field or drag the slider.

## Beta notes

Testing feedback welcome. Worth trying:

- tight hairpin turns and figure-eights
- an angled flat brush (low roundness, angle around 40) drawn in every direction
- very large and very small brush sizes
- typing values into the fields
- switching tools back and forth

Please report your RoboFont version and macOS version with any bug.

## License

MIT

Built by Ry Sunday Faraola, [Commodity Foundry](https://commodityfoundry.com)
