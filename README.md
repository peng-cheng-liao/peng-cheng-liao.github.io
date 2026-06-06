# Pengcheng Liao Personal Website

This is a static personal website inspired by Daniel Liang's academic homepage, built with plain HTML and CSS so it can run directly on GitHub Pages.

## Files

- `index.html`: page content
- `styles.css`: page styling
- `assets/Pengcheng_Liao_CV.pdf`: downloadable CV
- `assets/quantum-network.png`: homepage visual
- `.nojekyll`: tells GitHub Pages to serve the files exactly as written

## Preview Locally

Open `index.html` in a browser, or run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

The live site is published at `https://peng-cheng-liao.github.io`.

## Publish On GitHub Pages

1. Create a new GitHub repository named `<your-github-username>.github.io`.
2. Upload all files from this `personal-website` folder to that repository.
3. Open `https://<your-github-username>.github.io` after GitHub finishes publishing.

For this account, the repository name is `peng-cheng-liao.github.io`.

## Edit Content

Update text, links, publication entries, and conference entries in `index.html`. To replace the CV, overwrite `assets/Pengcheng_Liao_CV.pdf` with a new PDF using the same filename.
