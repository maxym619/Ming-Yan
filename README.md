# Personal Website

This is a minimal static personal website scaffold. Files:

- `index.html` — main page
- `styles.css` — simple styling

How to publish on GitHub Pages

1. Initialize local git and commit:

```bash
cd personal-website
git init
git add .
git commit -m "Initial site scaffold"
git branch -M main
```

2. Create a repository on GitHub (two options):

- Web: create a new repo at https://github.com/new, then follow the push instructions.
- CLI (if you have GitHub CLI `gh`):

```bash
gh repo create USERNAME/REPO --public --source=. --remote=origin --push
```

3. Push to GitHub (if created via web):

```bash
git remote add origin https://github.com/USERNAME/REPO.git
git push -u origin main
```

4. Enable GitHub Pages:

- Web: Repo → Settings → Pages → Choose branch `main` (root) → Save.
- CLI: you can use `gh` or the repo settings UI.

Optional: add a `CNAME` file with your custom domain and configure DNS.

Replace `USERNAME` and `REPO` with your GitHub username and repository name.
