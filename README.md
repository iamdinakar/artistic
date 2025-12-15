# Procedural Hash Sketchpad (Gen Only) (Abstract Art With Shareable Links)

This is a tiny, single-page sketch generator for making abstract drawings that feel like “algorithmic ink.”  
Each image is created from a small set of choices (preset + sliders + seed), and those choices are stored in the URL so you can share the result as a link.

Think of it like a camera for generative art:
- the preset is the “lens”
- the sliders are your “exposure settings”
- the seed is the “moment you captured”

Open the same link later (or on a different device) and you’ll get the same drawing again.

---

## Live links

- Vercel: `https://artistic-nu.vercel.app/`

---

## What you can make

This app produces abstract, print-friendly sketches with a few different “styles”:

- **flow**  
  Smooth current-like lines, like wind maps, topographic currents, or liquid motion.

- **grid**  
  Clean geometric doodles with subtle irregularities—structured, but still human-feeling.

- **constellations**  
  Star-map networks: points, connections, and soft “space” atmosphere.

- **scribblefill**  
  Organic blobs filled with hand-drawn style hatching.

---

## How to use it

1. Open the site.
2. Choose a preset.
3. Adjust the sliders until you like the look.
4. Click **Generate** to lock it into a shareable link.
5. Click **Share** to copy the link.
6. Download:
   - **PNG** for quick sharing
   - **SVG** for scalable, crisp prints and editing in vector tools

---

## Sharing and reproducibility

Instead of saving a big image file inside the link, the URL stores a compact “recipe.”  
That recipe always regenerates the same result, so sharing the link is enough.

---

## Export

- **PNG** downloads what is visible on screen (scaled to fill your window).
- **SVG** downloads a true high-quality scalable vector graphics version in a `1000×1000` space (best for printing or editing).

---

## Run locally (Python)

If you just want to open the file, you can double-click `index.html`.  
If you prefer a local server (recommended for consistent behavior across browsers):

1. Put `index.html` in a folder.
2. In that folder, run:

   - Python 3:
     `python -m http.server 8000`

3. Open:
   `http://localhost:8000`

---

## Deployment notes

### Vercel
Deploy as a static site that serves `index.html` at the root.

### GitHub Pages
Enable GitHub Pages for the repo and point it at the branch/folder that contains `index.html`.

---

## License

Use it however you like. Attribution appreciated but not required.

MIT. Give credit where it is due.
