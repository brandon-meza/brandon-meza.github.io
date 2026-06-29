# Brandon Meza-González — academic website

A single self-contained page (`index.html`) plus an `assets/` image folder. No build step, no dependencies.

## Files
```
index.html        ← the whole site
assets/
  profile.jpg     ← your photo (cropped + enhanced)
  pore.png        ← MspA nanopore / ssDNA  (PCCP 2026, CC BY-NC)
  fes.png         ← hydrolysis free-energy maps (PCCP 2023)
```
All figures are your own published work and are captioned with their citation on the page.

## Publish on GitHub Pages (free) — 5 minutes
1. Create a free account at **github.com** (if you don't have one).
2. Create a **new repository** named exactly **`<your-username>.github.io`**
   (e.g. `brandonmeza.github.io`). Make it **Public**.
3. On the repo page click **“Add file ▸ Upload files”**, then drag in
   **`index.html`** and the **`assets`** folder. Commit.
4. Go to **Settings ▸ Pages**. Under *Build and deployment* set
   **Source = Deploy from a branch**, **Branch = `main`**, **folder = `/ (root)`**. Save.
5. Wait ~1 minute, then open **`https://<your-username>.github.io`**. Done.

### Updating later
Edit `index.html` (or replace an image in `assets/`) → upload again → it redeploys automatically.

## Change the photo (optional)
Replace `assets/profile.jpg` with any square image of the same name — no HTML edit needed.

## Add a paper figure later
You authored your papers, so you may reuse your own figures on a personal site
(add a citation). Put the image in `assets/` and use the commented `<figure>`
template inside the Research section of `index.html`. The *Scientific Data* 2024
paper is open-access (CC-BY) and freely reusable with attribution.

## Custom domain (optional)
In **Settings ▸ Pages ▸ Custom domain** enter a domain you own (e.g. from
Cloudflare/Porkbun) and add the DNS records GitHub shows.

## Alternative host (no GitHub)
Drag this whole folder onto **app.netlify.com/drop** or **Cloudflare Pages** for
an instant free URL — same files, no git required.
