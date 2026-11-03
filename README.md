# ibidem-art.fr — copie statique

Ce dépôt contient une **copie statique** du site <https://ibidem-art.fr>, générée
depuis le WordPress hébergé chez Ionos le 3 novembre 2026.

Le site fonctionne sans PHP ni base de données : seuls des fichiers HTML, CSS, JS
et des images sont présents. Il est publié par GitHub Pages.

## Ce qui a été figé

- Les articles, pages, catégories, étiquettes et la pagination sont conservés
  avec les mêmes adresses qu'auparavant.
- Le champ de recherche renvoie vers une recherche Google restreinte au domaine
  (GitHub Pages ne peut pas exécuter de recherche interne).
- Le formulaire de commentaire a été retiré ; les adresses de contact
  (contact@ibidem-art.fr, olivier.morice@ibidem-art.fr) restent sur la page Contact.
- `feed.xml` est un flux RSS figé au moment de la capture.

## Mettre à jour

Le site ne se modifie plus depuis l'administration WordPress : toute modification
demande de régénérer cette copie puis de valider et de pousser sur GitHub.
