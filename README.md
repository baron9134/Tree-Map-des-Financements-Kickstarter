# Tree-Map-des-Financements-Kickstarter
# Tree Map des Financements Kickstarter

## Description

Ce projet consiste à créer un **Tree Map** interactif pour visualiser les financements sur Kickstarter. Chaque case du Tree Map représente un projet financé, et sa taille est proportionnelle au montant de l'argent levé. En survolant une case, un **tooltip** apparaît, affichant des informations supplémentaires sur le projet.

## Technologies utilisées

- **HTML** pour la structure du site.
- **CSS** pour la mise en forme et le style.
- **JavaScript** avec **D3.js** pour générer le Tree Map et gérer les interactions.
- **D3.js** est utilisé pour la création de la visualisation basée sur les données JSON de Kickstarter.

## Fonctionnalités

- **Titre et Description** : Le Tree Map dispose d'un titre (`#title`) et d'une description (`#description`) pour fournir des informations contextuelles.
- **Tree Map interactif** : Chaque case du Tree Map représente un projet Kickstarter et est dimensionnée en fonction du montant de financement.
- **Légende** : La légende affiche des couleurs représentant les catégories de projets.
- **Tooltip** : Lorsque l'utilisateur survole une case, un tooltip affiche des informations supplémentaires sur le projet financé.
- **Réactivité** : Le projet est adapté pour être vu sur la plupart des tailles d'écran.

## User Stories

- **User Story #1** : Le Tree Map doit avoir un titre avec un id `#title`.
- **User Story #2** : Le Tree Map doit avoir une description avec un id `#description`.
- **User Story #3** : Le Tree Map doit avoir des rectangles avec la classe `tile` représentant les données.
- **User Story #4** : Il doit y avoir au moins deux couleurs différentes utilisées pour les cases.
- **User Story #5** : Chaque case doit avoir les propriétés `data-name`, `data-category` et `data-value` correspondant à son nom, catégorie et valeur.
- **User Story #6** : La surface de chaque case doit être proportionnelle à la valeur de `data-value`.
- **User Story #7** : Le Tree Map doit avoir une légende avec un id `#legend`.
- **User Story #8** : La légende doit avoir des rectangles avec la classe `legend-item`.
- **User Story #9** : Les rectangles dans la légende doivent utiliser au moins deux couleurs différentes.
- **User Story #10** : Lors du survol d'une case, un tooltip doit apparaître avec un id `#tooltip`.
- **User Story #11** : Le tooltip doit afficher une propriété `data-value` correspondant à la valeur de la case active.

## Dataset

Le projet utilise le dataset **Kickstarter Funding Data** fourni par FreeCodeCamp à l'adresse suivante :  
[Kickstarter Funding Data](https://cdn.freecodecamp.org/testable-projects-fcc/data/tree_map/kickstarter-funding-data.json)

## Installation et Exécution

1. Clonez le dépôt ou téléchargez les fichiers du projet.
2. Ouvrez le fichier `index.html` dans un navigateur pour visualiser le Tree Map.
3. Vous pouvez également déployer ce projet sur des plateformes comme GitHub Pages ou CodePen.

## Contributions

Les contributions sont les bienvenues ! Si vous avez des suggestions d'amélioration ou des corrections, n'hésitez pas à créer une **Pull Request**.

## Auteurs

- **[Ton Nom]** - *Développeur principal*
- **[Collaborateurs]** - *Contributions mineures ou fixes*

## License

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.
