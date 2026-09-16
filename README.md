# Portfolio — Sahade Zongo

Portfolio personnel + CV de **Sahade Zongo** — Chef de Projet ERP & Développeur Full-Stack (PHP · Flutter · BI · IA appliquée).

Site statique, sans dépendance de build : HTML/CSS/JS natif, polices Google Fonts, visualisations faites main (canvas + SVG).

## Contenu
- `index.html` — le portfolio (hero animé, radar de compétences, timeline, projets)
- `cv.html` — le CV imprimable (bouton « Imprimer / PDF »)
- `assets/` — images (déposez ici `photo.jpg` pour la photo de profil)

## Ajouter la photo
1. Déposez votre photo dans `assets/photo.jpg` (format carré recommandé).
2. Dans `index.html` et `cv.html`, remplacez le monogramme `SZ` par une balise `<img src="assets/photo.jpg" alt="Sahade Zongo">` (un commentaire indique l'emplacement dans `cv.html`).

## Aperçu local
Ouvrez simplement `index.html` dans un navigateur, ou servez le dossier :
```bash
python -m http.server 8000
```

## Déploiement — GitHub Pages
```bash
git remote add origin https://github.com/<votre-compte>/portfolio.git
git push -u origin main
```
Puis sur GitHub : **Settings → Pages → Source : branche `main` / dossier `/root`**.
Le site sera publié sur `https://<votre-compte>.github.io/portfolio/`.

---
© Sahade Zongo
