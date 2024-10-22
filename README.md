# TransMission


> En tant qu'astronaute, vous devez réparer la tour de communication de votre vaisseau pour demander de l'aide après que celui-ci aie mystérieusement cesser de fonctionner. 

### Description 
Plongez dans l'univers captivant NOM DU JEU, un jeu VR où vous incarnez un astronaute de la compagnie intergalactique StellarCorp. Envoyé sur une base spatiale pour étudier des astres mystérieux, votre mission prend une tournure inattendue lorsque votre vaisseau cesse mystérieusement de fonctionner.

Face à l'urgence, vous devez réparer la tour de communication afin de demander de l'aide. Explorez un environnement fascinant, rempli de technologies avancées et de paysages spatiaux éblouissants. Résolvez des énigmes complexes et interagissez avec des éléments de votre environnement pour restaurer le fonctionnement de votre vaisseau.


### Moodboard
#### Visuel
![Moodboard Visuel](https://i.ibb.co/MGjzmK5/ambiances.png)
#### Sonore

### Schéma d'interactivité
```mermaid
graph TD
    A[Écran d'Accueil] --> B[Sélection de Mission]
    B --> C[Exploration de la Zone]
    C --> D[Résolution d'Énigmes]
    D --> E[Récupération des Éléments]
    E --> F[Interaction avec la Faune]

    D --> D1[Triage de Déchets]
    D --> D2[Purification de l'Eau]
    D --> D3[Puzzle de l'Équilibre Écologique]

    E --> E1[Nettoyage de la Zone]
    E --> E2[Planter des Arbres]

    %% Logique de progression
    D1 --> E1[Nettoyage de la Zone]
    D2 --> E1
    D3 --> E1

    %% Fin du jeu
    E1 --> |"Tous les puzzles résolus et environnement nettoyé"| H[Monde Propre et Beauté Restaurée]
    H --> I[Choisir de Rester ou Quitter]
```
