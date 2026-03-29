IMAGES FOLDER — MAANYA PATEL SITE
==================================

Drop your image files in this folder, then swap the CSS placeholder divs
in the HTML for <img> tags.

HOW TO ADD ARTWORK:
-------------------
Each painting placeholder in the HTML looks like this:

  <div class="canvas canvas-1" style="aspect-ratio:4/3;"></div>

Replace it with:

  <img src="images/your-file.jpg" alt="Painting title"
       style="width:100%;aspect-ratio:4/3;object-fit:cover">

SCULPTURE PHOTO:
----------------
Save the glass vessel photo as:  images/sculpture.jpg

The gallery.html page is already set up to display it — it references
"images/sculpture.jpg" with an automatic fallback to a colour placeholder
if the file isn't found.

RECOMMENDED IMAGE FILES:
-------------------------
sculpture.jpg         — the glass vessel / blood memory sculpture
synaptic-fire.jpg     — gallery item 1 (large red/black painting)
bone-map.jpg          — gallery item 2 (figure study)
cortical-storm.jpg    — gallery item 3 (warm explosion)
peeling-thought.jpg   — gallery item 4 (dark panel)
studio-process.jpg    — about page (close-up process shot)
exhibition-view.jpg   — exhibitions page hero

TIPS:
-----
- Save images as .jpg for photos, .png if you need transparency
- Compress images before uploading (aim for under 500KB per image)
  → Use squoosh.app for free browser-based compression
- GitHub Pages has a 1GB soft limit, so keep total site size reasonable
