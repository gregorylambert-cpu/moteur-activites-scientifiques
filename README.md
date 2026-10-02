# Moteur de ressources INRAE V0.8 — corpus 380

Base du moteur V0.7, avec son architecture et sa logique de recherche conservées, alimentée par le corpus consolidé de 380 ressources.

## Recherche
- concepts en ET ;
- synonymes historiques du V0.7 ;
- exclusion des mots génériques ;
- score interne pour le classement ;
- recherche dans les métadonnées historiques + taxonomie V1.

## Filtres V1
Type, domaine scientifique, sujet, approche, contexte, puis filtres historiques (thématique, centre, accessibilité, porteur).

Le corpus est séparé dans `data.json`. `index.html` contient également une copie embarquée pour conserver le fonctionnement sans serveur du V0.7.
