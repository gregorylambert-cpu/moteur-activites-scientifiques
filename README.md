# Moteur de ressources INRAE V0.9 — corpus de 636 ressources

Version actualisée à partir du corpus INRAE dédoublonné et des tags harmonisés.

## Fonctionnement
- Corpus de 636 ressources dans `data.json`.
- Copie embarquée du même corpus dans `index.html` pour conserver le fonctionnement autonome sans serveur.
- Recherche par concepts, avec synonymes et classement interne.
- Filtres : type harmonisé, domaine scientifique, sujet, approche, contexte, thématique historique, centre, accessibilité et porteur.
- Les tags harmonisés sont la base des mots-clés de chaque fiche.

## Lancement
Ouvrir `index.html` dans un navigateur. `data.json` est fourni séparément pour consultation et réutilisation, mais la page autonome utilise la copie embarquée.

## À garder en tête
Les classifications type/domaine/sujet/approche/contexte sont une première structuration automatique à valider par des tests de recherche. Les fiches dont les tags étaient « à qualifier » conservent leurs champs descriptifs, mais n'ont pas de tags harmonisés ajoutés artificiellement.
