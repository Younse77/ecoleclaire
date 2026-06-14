# ÉcoleClaire

Site de comparaison des écoles, collèges et lycées de France à partir des données officielles de l'Éducation nationale.

## Structure
- `index.html` — application principale
- `ecoles-france.json` — base de données (compressée)
- `robots.txt`, `sitemap.xml`, `llms.txt` — référencement (Google + IA)
- `og-image.png` — image de partage
- `ecole/` — pages individuelles par établissement (collèges et lycées)

## Déploiement
Site statique. Se déploie sur Cloudflare Pages (connexion Git, aucun build).

## À faire avant mise en production
Remplacer `REMPLACER-PAR-VOTRE-DOMAINE` par le vrai domaine dans `robots.txt`, `sitemap.xml` et les pages de `ecole/`.
