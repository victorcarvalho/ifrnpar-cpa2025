# IFRN CPA Report (Static)

Static single-page report meant to be served via GitHub Pages or any static host.

To publish on GitHub Pages:

1. Create a repository on GitHub and push this folder as the repository root.
2. In the repository settings, enable **Pages** and set source to the `main` branch and root (`/`).
3. Add a `.nojekyll` file at the repo root to prevent Jekyll processing (optional but recommended).

Quick git commands:

```bash
git init
git add .
git commit -m "Initial commit: static report"
git branch -M main
git remote add origin git@github.com:USERNAME/REPO.git
git push -u origin main
```

Optional: use `gh` CLI to create and push in one step:

```bash
gh repo create USERNAME/REPO --public --source=. --remote=origin --push
```

Notes:
- The page uses CDN-hosted Tailwind, Chart.js and FontAwesome. For production pin versions or vend those assets.
- The HTML keeps pt-BR numeric formatting (comma decimals) for display; JS parsing is tolerant to that format.
