# Documentation du tuo GitHub avec Git

## Initialiser un depot

```bash
git init
git remote add origin SSH_REPO
```

## Rédiger un commit

```
Titre du commit

Description, de notre commit avec des informations l'évolution du projet
```

```bash
git add .
git commit -m "Un commentaire"
git push origin main
```

## Création d'une branche

```bash
git checkout -b NOM_BRANCHE
```

Pour les bonnes prarique, on va intégrer la notion de revue de code. Pour cela,on va créer une branche, fiare des modifications, les envoyer sur le dépôt distant, puis créer un pull request pour demander une revue de code.
