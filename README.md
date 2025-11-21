# Portfolio

Ce dépôt contient mon portfolio personnel (page statique HTML/CSS).

Structure:
- `index.html` — page principale
- `styles.css` — styles
- `assets/` — images et autres ressources (à ajouter)

Personnalisation rapide:
- Modifiez `index.html` pour mettre vos informations et projets
- Modifiez `styles.css` pour ajuster les couleurs, tailles et responsive

Comment publier sur GitHub (résumé):
1. Créez un repository sur GitHub (ex: `mon-portfolio`).
2. Dans ce dossier local, exécutez:

```powershell
git remote add origin https://github.com/<votre-username>/<votre-repo>.git
git branch -M main
git push -u origin main
```

Ou utilisez `gh` si installé:

```powershell
gh repo create <votre-username>/<votre-repo> --public --source=. --remote=origin --push
```

Besoin d'aide pour pousser ou créer le repo automatiquement ? Dites-moi votre nom d'utilisateur GitHub et si vous voulez que je tente `gh repo create` (cela peut ouvrir une invite pour se connecter).