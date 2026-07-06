# Praneeth Varma Danthuluri — Portfolio

Static portfolio site for **praneethvarmadanthuluri.com**. Single-file build (no framework, no build step) — deployable to GitHub Pages as-is.

## Contents

- `index.html` — the complete site (HTML + CSS + JS in one file)
- `CNAME` — custom domain for GitHub Pages
- `resume.pdf` — **add your resume here** (the "Download Resume" button links to `resume.pdf` in the repo root)

## Deploy to GitHub Pages (new repo)

1. Create a **new** repository on GitHub (e.g. `portfolio`) — do NOT reuse `pranuvar.github.io`.
2. Push these files to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Portfolio site"
   git branch -M main
   git remote add origin https://github.com/Pranuvar/portfolio.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**.
4. Preview URL will be `https://pranuvar.github.io/portfolio/` within a minute or two.

## DNS records for praneethvarmadanthuluri.com

At your domain registrar, add:

| Type  | Host | Value               |
|-------|------|---------------------|
| A     | @    | 185.199.108.153     |
| A     | @    | 185.199.109.153     |
| A     | @    | 185.199.110.153     |
| A     | @    | 185.199.111.153     |
| CNAME | www  | pranuvar.github.io  |

Then on GitHub: **Settings → Pages → Custom domain** → enter `praneethvarmadanthuluri.com` → Save → tick **Enforce HTTPS** once the certificate is issued (can take up to an hour after DNS propagates).

## Customising project links

Each project card currently links to `https://github.com/Pranuvar`. To point a card at its specific repo, edit the `href` on the three `<a class="glass-card proj-card">` elements in `index.html` (marked with a comment).
