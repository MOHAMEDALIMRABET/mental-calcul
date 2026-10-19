# Ardoise de calcul mental

Jeu de calcul mental pour les élèves, jouable dans le navigateur sur ordinateur, tablette et téléphone.

## Le jeu

- **Opérations** : addition, soustraction, multiplication, ou un peu de tout.
- **Types de calcul** : simple (`4 + 3 = ?`), à trous (`4 + ? = 7`), ou les deux mélangés.
- **Niveaux** :
  - Facile : jusqu'à 10 (tables 1 à 5), 2 minutes
  - Moyen : jusqu'à 20, parfois 100 (tables 2 à 10), 3 minutes
  - Difficile : jusqu'à 100 (tables 2 à 12), 3 minutes
- Séries de 10 calculs, 4 réponses au choix à toucher.
- Sons pour les bonnes et mauvaises réponses (bouton pour couper le son).
- Sans faute : coupe, feu d'artifice, confettis et « Génial ! » à voix haute.

## Explications des erreurs

Pour les additions et soustractions à trous ratées, l'écran de fin montre une bande numérique avec les bonds :

- si les unités le permettent, on complète d'abord les unités puis les dizaines (`4 + ? = 55` : +1 puis +50) ;
- sinon on passe par la dizaine la plus proche (`4 + ? = 51` : +6, +40, +1 = 47).

## Utilisation

Ouvrir `index.html` dans un navigateur. Aucun serveur ni installation nécessaire.
Pour le mettre en ligne : Settings → Pages → Deploy from branch → `main` / root.
