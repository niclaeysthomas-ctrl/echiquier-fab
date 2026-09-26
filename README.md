# L'Échiquier de Fab

Entraîneur d'échecs personnalisé — puzzles tactiques et répertoire d'ouvertures calés sur les vraies statistiques chess.com de SalutFabbb.

- **Diagnostic** : analyse des dernières parties (via l'API publique chess.com) pour repérer les ouvertures qui sous-performent.
- **Puzzles** : positions tactiques vérifiées coup par coup avec Stockfish.
- **Ouvertures** : modules jouables (Française, Sicilienne, Scandinave, Gambit Dame, Italienne, Caro-Kann) avec plans expliqués, certains ciblant explicitement les points faibles identifiés.

Application autonome en un seul fichier HTML (aucune dépendance serveur), utilisant [chess.js](https://github.com/jhlywa/chess.js) pour la validation des coups.

## Utilisation

Ouvrir `index.html` dans un navigateur, ou servir le dossier statiquement (GitHub Pages, etc.).
