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
- Your hero portrait is now **self-hosted** in `assets/portrait.jpg` (cropped from your CV headshot, shown in a circular frame) so it no longer depends on the disabled Cloudinary account. **Make sure to upload the `assets` folder along with `index.html`** when you push to GitHub — both are required.
- Most instrument photos (confocal, LC-MS, RT-PCR, FTIR) still link to your other Cloudinary account (`dmuecdqxy`) — those were working as of this build. The HPLC photo and the three testimonial photos previously pointed at the now-disabled `dbyioi2qq` account; the HPLC image has been swapped for a free-license Unsplash photo, and the testimonial photos have been replaced with simple initials avatars (I didn't want to substitute a stock photo and pass it off as an actual picture of your named colleagues).
- If you'd like real photos for the testimonials, or want everything fully self-hosted (immune to any Cloudinary account issues going forward), just send me the image files and I'll drop them into `assets/` and wire them in.
- Phone number used: `+91 7904484318` (from your CV) — your old site listed a different number (`+91 9488058967`); update in the Contact section if the CV one isn't current.
- Resume/Publications/Achievements/GenBank links point to your existing Google Drive files — make sure sharing is set to "Anyone with the link."
