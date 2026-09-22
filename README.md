# Blobbington

A pen for the RoboFont glyph editor. Drag to draw with an oval nib: the mark is exactly where the nib travelled, like ink on paper, and the outline is fitted with clean, editable curves. Click once to stamp a single dab.

## Install

1. Download `Blobbington.roboFontExt.zip` from this repo
2. Unzip it
3. Double-click `Blobbington.roboFontExt`
4. Quit RoboFont completely and reopen it

Blobbington appears in the glyph editor toolbar.

## Controls

The panel opens when you select the tool and closes when you switch away. Settings are remembered between sessions.

- **Fidelity**: how many points the finished outline uses. Accurate keeps more detail, Smooth uses fewer points. Neither moves your line.
- **Size**: length of the nib in font units.
- **Angle**: rotation of the nib.
- **Roundness**: 100 is a round marker, 1 is a flat broad nib.
- **Stabilizer**: the nib trails the cursor on a string, smoothing out wobble. 0 is off.

Type a value into any field or drag its slider. Hold Shift to lock a stroke to 45 and 90 degrees. Strokes stay separate; use Remove Overlap to merge them.

## Beta notes

Feedback welcome. Worth trying:

- straight strokes and curves with a flat nib (roundness 1)
- tight hairpins and figure-eights
- the stabilizer at a few settings
- very large and very small sizes
- long strokes, to check speed

Please include your RoboFont and macOS versions with any bug report. If a stroke fails, the Output Window prints an error message; copying that into your report helps a lot.

## License

MIT

Built by Ry Sunday Faraola, [Commodity Foundry](https://commodityfoundry.com)
