# Documentation du tuto GitHub avec Git

## Initialisation du dépôt

```bash
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin SSH_REPO
git push -u origin main
```
## Rédiger un commit 

```
Titre du commit

Description de notre commit des informations sur l'évaluation du projet

```
## Envoyer un commit sur le dépot distant

```
git add .
git commit -m "Titre du commit"
git push origin main

```

## Creation de branche

```bash
git checkout -b NOM_BRANCHE
```

Pour les bonnes pratique, on va intégré la notion de revue de code. pour cela , on va créer une branche ,faire des modifications, les envoyer sur le depot distant, puis créer une pull request pour demnder une revue de code 