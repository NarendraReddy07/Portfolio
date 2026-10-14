# Narendra Reddy Vennapusa: Portfolio

Static site (HTML, CSS, JS). No build step. three.js loads from a CDN, so you need internet to view it.

## Run locally
```
python -m http.server 8000
```
Open http://localhost:8000

## Publish on GitHub Pages
1. Create a public repo named `NarendraReddy07.github.io`.
2. In this folder:
   ```
   git init
   git add .
   git commit -m "Add portfolio"
   git branch -M main
   git remote add origin https://github.com/NarendraReddy07/NarendraReddy07.github.io.git
   git push -u origin main
   ```
3. Settings > Pages > Deploy from a branch > `main` / `(root)` > Save.
