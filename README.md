# Brian Pham – Portfolio (Single Folder, No CDNs)

Publish‑ready for GitHub Pages. No external CSS/JS; everything is local.

## Files
- `index.html` – one‑page site
- `tailwind-local.css` – compact utility CSS (Tailwind‑like subset used by this page)
- `styles.css` – small custom tweaks
- `script.js` – mobile menu + footer year
- `profile.svg` – placeholder avatar
- `BrianPham-InternResume.pdf` – **placeholder** CV (replace with your real PDF)
- `.nojekyll` – ensures Pages serves files as‑is
- `LICENSE` – MIT

## Publish on GitHub Pages
1. Create a repository and add all files from this folder to the repo **root**.
2. In **Settings → Pages**: Source = *Deploy from a branch*; Branch = `main`; Folder = `/ (root)`.
3. Wait for the green banner “Your site is published.”
4. Replace `BrianPham-InternResume.pdf` with your real CV (keep the same filename for the links to work).

## Local preview
Open `index.html` directly or run:
```bash
python3 -m http.server 5050
# visit http://localhost:5050/index.html
```
