# Site GDEM – Groupement des Entrepreneurs Malgaches

Site statique en 3 pages (aucune dépendance, aucun build) :

- `index.html` : présentation
- `adhesion.html` : adhésion et gouvernance
- `contact.html` : appel aux investisseurs, e-mails / appels / WhatsApp cliquables

## Déploiement

### 1. GitHub
    git remote add origin https://github.com/<compte>/gdem-site.git
    git branch -M main
    git push -u origin main

### 2. Netlify
Netlify > Add new site > Import an existing project > GitHub > choisir `gdem-site`.
Build command : (vide) · Publish directory : `.` (déjà défini dans `netlify.toml`).
Chaque `git push` redéploie automatiquement le site.
