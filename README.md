# Periasamy Sakthidhasan — Personal Academic Website

A single self-contained `index.html` (fonts + styles + script inline, images linked from your existing Cloudinary-hosted assets) combining your two previous CodeDesign pages plus details from your CV.

## Deploy to GitHub Pages (free) — two options

### Option A: New repo named `your-username.github.io` (site lives at the root URL)
1. Create a new **public** GitHub repo named exactly `your-username.github.io`.
2. Upload `index.html` **and the `assets` folder** to the repo root (Add file → Upload files — you can drag both in together).
3. Commit. Your site goes live at `https://your-username.github.io/` within a minute or two.

### Option B: Any repo name (site lives at a sub-path)
1. Create a public repo, e.g. `sakthidhasan-portfolio`.
2. Upload `index.html` **and the `assets` folder** to the repo root.
3. Go to **Settings → Pages**, under "Build and deployment" set **Source: Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
4. Your site goes live at `https://your-username.github.io/sakthidhasan-portfolio/`.

## Custom domain (optional)
In **Settings → Pages → Custom domain**, add your domain and follow GitHub's DNS instructions (a `CNAME` file is created automatically).

## Editing later
Everything — text, colors, fonts — lives in the one `index.html` file:
- Colors: `:root { --accent: ... }` near the top of the `<style>` block.
- Section content: search for the section's `id` (e.g. `id="publications"`) to jump straight to it.
- New publication: copy a `.pub-item` block and edit the year/title/authors/DOI.

## Notes
- Your **real photos are now in place**: hero portrait, HPLC, confocal, and FTIR are all self-hosted in `assets/` — no more dependency on any Cloudinary account. **Upload the `assets` folder along with `index.html`** when you push to GitHub — both are required.
- LC-MS, RT-PCR, and one fluorescence sample image still link to your other Cloudinary account (`dmuecdqxy`), which hasn't shown any issues. If you find/recover those originals too, send them over and I'll move them local the same way.
- Phone number used: `+91 7904484318` (from your CV) — your old site listed a different number (`+91 9488058967`); update in the Contact section if the CV one isn't current.
- Resume/Publications/Achievements/GenBank links point to your existing Google Drive files — make sure sharing is set to "Anyone with the link."
