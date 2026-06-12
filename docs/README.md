# LIT project page (GitHub Pages)

This folder is the **static project website** for the CASE 2026 paper *Learning Robotic Policy with Imagined Transition*.

## Publish on GitHub

1. Push this repository to GitHub.
2. Repository **Settings → Pages**.
3. **Build and deployment → Source:** Deploy from a branch.
4. **Branch:** `main` (or your default branch), **Folder:** `/docs`.
5. After deployment, the site URL is:

   `https://<username>.github.io/<repository>/`

   Example: if the repo is `CASE2026_LIT`, the homepage is  
   `https://<username>.github.io/CASE2026_LIT/`

## Local preview

From the repository root:

```bash
cd docs && python3 -m http.server 8080
```

Then open `http://localhost:8080/`.

## Assets

- `assets/pdf/paper.pdf` — camera-ready PDF (copied from your local build; replace when updated).
- `assets/pdf/*.pdf` — optional vector exports for figures; the page shows **PNG** images in `assets/images/` (no inline PDF viewer).
- `assets/images/` — figures exported for the web (PNG).

## Video

The page embeds the Bilibili player for BV `BV1wbQDYmENv`. If the iframe is blocked, use the direct Bilibili link in the video section.

## Citation

The site’s BibTeX block cites the arXiv preprint [2503.10484](https://arxiv.org/abs/2503.10484); swap in the IEEE proceedings entry when you want the CASE citation instead.
