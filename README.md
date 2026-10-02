# Refractium

Glass distortion for images and SVGs. Simulates how different kinds of glass bend what is behind them. Single self-contained file (`index.html`), WebGL shader, shadcn/ui-style interface.

## Run it
- Open `index.html` in any modern browser, or serve the folder with any static server.

## Features
- Sources: PNG, JPG, WebP, GIF, SVG files (drop, browse, paste) or pasted SVG code
- Presets: Lens, Marble, Water drop, Concave, Vortex, Crystal
- Distortion styles: Convex, Glass ball, Concave, Ripple, Swirl, Liquid, Faceted
- Glass edge: Clean, Soft, or Spill outside (with transition width)
- Glass shape (round, squircle, wide), highlight, edge shading, drop shadow
- 4× supersampled rendering for a smooth, clean rim
- Compare (hold C), export PNG / JPG / WebP at full resolution

## Notes
- Needs an internet connection only for the Geist font (falls back to system fonts).
- SVGs that reference external images or fonts render without them; inline those first.
