# A Little Universe for Jaya 🎂✨

A single-page birthday wishes site. It is a fully static site: one `index.html`
file that pulls fonts, Bootstrap, and Tailwind from CDNs, so there is **no build
step** and no server required.

## Local preview
Just open `index.html` in a browser, or serve the folder with any static server:

```bash
# Option A: Python
python -m http.server 8000

# Option B: Node (npx, no install)
npx serve .
```

Then visit http://localhost:8000

## Deploy (Netlify, Git-based)
1. Push this repo to GitHub/GitLab/Bitbucket.
2. In Netlify: **Add new site → Import an existing project** and pick the repo.
3. Netlify reads `netlify.toml` automatically (publish dir = `.`, no build command).
4. Click **Deploy**. Every future `git push` redeploys the site automatically.

## Files
- `index.html` — the entire site
- `netlify.toml` — Netlify config (publish dir + headers)
- `.gitignore` — keeps installer/log junk out of the repo
