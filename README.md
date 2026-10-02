# Glass Scope

A magnifying glass distortion tool for images and SVGs. Single self-contained file (`index.html`), WebGL shader, shadcn/ui-style interface.

## Run it
- Open `index.html` in any modern browser, or
- In Claude: upload `index.html` and ask Claude to publish it as an artifact (declare the `downloads` capability so Export works in the published page).

## Features
- Sources: PNG, JPG, WebP, GIF, SVG files (drop, browse, paste) or pasted SVG code
- Distortion styles: Convex, Glass ball, Concave, Ripple, Swirl, Liquid, Faceted
- Glass edge: Clean, Soft, or Spill outside (with transition width)
- Glass shapes, frame (glass rim / metal ring), handle, highlight, shading, drop shadow
- Presets, compare (hold C), export PNG / JPG / WebP at full resolution

## Notes
- Needs an internet connection only for the Geist font (falls back to system fonts).
- SVGs that reference external images or fonts render without them; inline those first.
