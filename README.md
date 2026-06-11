# Pawan Singh Ahirwar — Portfolio

Personal portfolio website for **Pawan Singh Ahirwar**, AI/ML Engineer (Computer Vision · NLP · Generative AI).

🔗 **Live site:** `https://pawanahirwar.github.io/portfolio/`

## What this is

A single-page, fully static portfolio built with plain **HTML, CSS, and a little JavaScript** — no build step, no dependencies, no backend. It loads fonts from Google Fonts and runs anywhere that can serve a static file.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The entire website (HTML + CSS + JS inline) |
| `README.md` | This file |
| `LICENSE` | Pawan Singh Ahirwar |
| `.gitignore` | Ignores OS / editor junk files |

## Run it locally

Just open `index.html` in any browser. Or, for a local server:

```bash
# Python 3
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Create a new **public** repository on GitHub named `portfolio` (don't add a README — this repo already has one).
2. From this folder, push the code:

   ```bash
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/pawanahirwar/portfolio.git
   git push -u origin main
   ```

3. On GitHub, go to **Settings → Pages**.
4. Under **Source**, choose **Deploy from a branch**, select branch **`main`** and folder **`/ (root)`**, then **Save**.
5. Wait ~1–2 minutes. Your site goes live at:

   `https://pawanahirwar.github.io/portfolio/`

### Want it at the root URL instead?

If you name the repository `pawanahirwar.github.io` (exactly your username), the site will be served from `https://pawanahirwar.github.io/` with no `/portfolio/` suffix.

## Updating content

All content lives in `index.html`. Edit the text directly, commit, and push — GitHub Pages redeploys automatically.

```bash
git add .
git commit -m "Update content"
git push
```

## License

Pawan — see [LICENSE](LICENSE).
