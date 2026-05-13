# Humdrum Style Guide

Interactive style guide for [humdrum.one](https://humdrum.one) apps. Live themes (Humdrum, Flexoki, Uchu, e-ink), color levels (200–600), typography specimens, and reusable component patterns.

## Local

Open `index.html` in a browser, or serve with anything:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Deploy (GitHub Pages)

```bash
git init
git add .
git commit -m "init"
git branch -M main
git remote add origin git@github.com:<you>/<repo>.git
git push -u origin main
```

Then in the repo on GitHub:

1. **Settings → Pages**
2. **Source:** Deploy from a branch
3. **Branch:** `main`, folder `/ (root)`
4. Save → wait ~30s → page lives at `https://<you>.github.io/<repo>/`

`.nojekyll` is already present so GitHub serves files as-is (no Jekyll processing).

## Files

```
index.html        ← entry
tokens.css        ← all theme + type tokens
style-guide.css   ← page chrome (cards, swatches, layout)
fonts/            ← Awke, Untitled Sans, Name Mono (woff2)
```

## Sources

- **Flexoki** — [stephango.com/flexoki](https://stephango.com/flexoki) · [github.com/kepano/flexoki](https://github.com/kepano/flexoki)
- **Uchu** — [uchu.style](https://uchu.style) · [github.com/Passw/NeverCease-uchu](https://github.com/Passw/NeverCease-uchu)
- **Humdrum** — custom palette, OKLCH-stepped levels, blue base `#0F80EA`
