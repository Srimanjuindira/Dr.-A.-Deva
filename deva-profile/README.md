# Dr. A. Deva | Academic Profile

Static website: `index.html` + `photo.jpg` + `Dr-A-Deva-CV.pdf`. No build step.

## Open locally
Double-click `index.html`.

## Put it online (GitHub Pages)
1. Create an empty repo named `deva-profile` on GitHub.
2. Run:
```bash
cd deva-profile
git init
git add .
git commit -m "Add academic profile site"
git branch -M main
git remote add origin https://github.com/<your-username>/deva-profile.git
git push -u origin main
```
3. On GitHub: Settings > Pages > Source: `main` branch, `/ (root)` > Save.
4. The site appears at `https://<your-username>.github.io/deva-profile/`.
