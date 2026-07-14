# Minal Baig — Portfolio

Personal portfolio site. Each page lives in its own folder so it can be updated independently.

## Structure
```
index.html                  Homepage
about/index.html            About page
proconnect/index.html       Case study: Bayut ProConnect
haddad/index.html           Case study: Haddad
agent-performance/index.html  Case study: Agent Performance
hatla2ee/index.html         Case study: Hatla2ee
```

Every page is fully self-contained (all images, fonts and scripts inlined) — updating one folder never affects the others.

## Publish with GitHub Pages
1. Create a new repository on github.com (e.g. `minal-portfolio`).
2. Upload the contents of this folder to the repo root (drag & drop on github.com works, or `git add . && git commit && git push`).
3. In the repo: **Settings → Pages → Source: Deploy from a branch → main / (root)** → Save.
4. Your site goes live at `https://<username>.github.io/minal-portfolio/` within a minute or two.

## Updating a page
Replace only that folder's `index.html` (e.g. `haddad/index.html`) and push — nothing else changes.
