# Ruilong Ren Homepage

Personal academic homepage for [Ruilong Ren (???)](https://github.com/Xiaolong-RRL).

## Preview locally

```bash
cd homepage
python3 -m http.server 8765
# open http://127.0.0.1:8765
```

## Deploy to GitHub Pages

1. Create a repo named `Xiaolong-RRL.github.io` (or any repo with Pages enabled).
2. Push the contents of this folder to the `main` (or `gh-pages`) branch.
3. In repo Settings ? Pages, set source to that branch / `/ (root)`.

```bash
git init
git add .
git commit -m "Initial academic homepage"
git branch -M main
git remote add origin git@github.com:Xiaolong-RRL/Xiaolong-RRL.github.io.git
git push -u origin main
```

## Customize

- Avatar: `assets/avatar.jpg`
- Links / papers: edit `index.html`
- Styles: `css/style.css`
