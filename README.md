# Moteur de ressources INRAE V0.7

Version adaptée à partir de `moteur_web_activites_v0_6`.

- Corpus intégré : **909 ressources** (le fichier disponible au moment de la génération contient 909 ressources, pas encore 1000).
- Interface et logique de recherche reprises du V0.6 : requête par concepts en ET, synonymes, mots génériques ignorés, score interne uniquement pour le classement.
- Champs adaptés au corpus INRAE : type, thématique, sous-thématique, porteur, unité, centre, partenaires, accessibilité, tags et lien.
- Les 19 lignes GAMAE conservées avec l'URL catalogue sont signalées dans l'interface par `lien catalogue à vérifier`.

## Utilisation
Ouvrir `index.html` dans un navigateur. Aucun serveur n'est nécessaire.

## Remplacement futur par le corpus 1000
Le corpus est embarqué dans `index.html` et copié séparément dans `data.json`. Quand le fichier 1000 sera finalisé, il suffira de régénérer ces deux fichiers en conservant la même structure.
