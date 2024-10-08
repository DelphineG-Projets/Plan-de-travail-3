# Mission ÉcoEcho : Nettoyage Intergalactique


> En tant que membres d'une compagnie intergalactique de nettoyage vous avez pour mission de voyager à travers diverses planètes pour restaurer des écosystèmes pollués en résolvant des énigmes et en interagissant avec la faune locale.

### Description 
Les joueurs incarnent des agents d’une compagnie intergalactique de nettoyage, envoyés sur des planètes dévastées par la pollution et la dégradation écologique. Chaque mission les plonge dans des environnements variés.

Les joueurs utiliseront des technologies avancées pour nettoyer les zones contaminées, résoudre des énigmes environnementales et interagir avec la faune locale. En collectant des ressources et en réparant des habitats, ils apprendront l'importance de la durabilité et de la protection des écosystèmes.

Avec une ambiance immersive, des graphismes colorés et des mécaniques de jeu engageantes, cette expérience éducative sensibilisent les joueurs aux enjeux environnementaux tout en les invitant à participer activement à la protection de la nature, même au-delà de leur propre planète. 

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
