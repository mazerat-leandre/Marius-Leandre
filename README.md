# GitHub Pages : /test et /prod

## Structure
- /index.html : sélecteur d'environnement (par défaut PROD)
- /prod/* : site production
- /test/* : site de test

## URLs
- PROD : https://<user>.github.io/<repo>/prod/
- TEST : https://<user>.github.io/<repo>/test/
- Sélecteur : https://<user>.github.io/<repo>/

## Workflow
1. Développer et valider dans /test
2. Quand c'est OK, copier le contenu de /test vers /prod (remplacer)
3. Commit + push -> GitHub Pages se met à jour

## Notes
- Les pages /prod et /test ont un badge "ENV" + un bouton "Changer" (retour au sélecteur).
