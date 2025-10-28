# Debarghya's Quarto Website (GitHub Pages, same URL)

This starter is set up so you **do NOT need to install anything** locally. 
GitHub Actions will render the site for you, and GitHub Pages will serve it from the **same URL**: `https://debarghya-mukherjee.github.io`.

## 1) Upload these files to your repo
1. Go to https://github.com/debarghya-mukherjee/debarghya-mukherjee.github.io
2. Click **Add file → Upload files**.
3. Upload *all* files from this folder (keep the same structure).
4. Commit the changes to the **main** branch.

## 2) Turn on GitHub Pages (one-time)
- Repo **Settings → Pages**.
- **Build and deployment** → *Source*: **Deploy from a branch**.
- *Branch*: `main` and `/docs`.
- Save.

## 3) Wait for the automation
- A tab **Actions** will show a workflow named **Quarto Render** running.
- When it finishes, it will create a `docs/` folder and push the rendered site.
- Your site will be live at the same URL.

## 4) Edit content using GitHub’s web editor
- Click any `.qmd` file (e.g., `index.qmd`) → **✏️** edit → make changes → **Commit**.
- The **Quarto Render** action runs again and updates `/docs` automatically.

## 5) Add your publications
- Open `publications.qmd` (already wired to `refs.bib`). 
- Paste your BibTeX entries into `refs.bib`. 
- Commit. The page will list all entries automatically.
- `aliases: [research.html]` keeps old links working.

## 6) Optional branding
- Replace `assets/logo.svg` with your own logo (same filename).
- Tweak colors in `styles.scss`.

That’s it. You can ask ChatGPT to fill in your real publications and courses by providing your BibTeX file and course details.
