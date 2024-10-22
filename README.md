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
flowchart TD
    A[Personne met le casque VR] --> B[Personne joue au jeu]
    B --> C[Personne lit le journal de bord et les tâches à réaliser]
    C -->|Interagir avec l'environnement| C
    C --> D[Personne va dans la première pièce débarrée]
    D -->|Interagir avec l'environnement| D
    D --> E[Personne résout le puzzle]
    E -->|Interagir avec l'environnement| E
    E --> F[Personne sort de la pièce pour aller dans la prochaine pièce débarrée]
    F -->|Interagir avec l'environnement| F
    F --> G[Personne résout le puzzle]
    G -->|Interagir avec l'environnement| G
    G --> H[Personne sort de la pièce pour aller dans la prochaine pièce débarrée]
    H -->|Interagir avec l'environnement| H
    H --> I[Personne résout le puzzle]
    I -->|Interagir avec l'environnement| I
    I --> J[Personne sort de la pièce pour aller dans la prochaine pièce débarrée]
    J -->|Interagir avec l'environnement| J
    J --> K[Personne résout le puzzle]
    K -->|Interagir avec l'environnement| K
    K --> L[Personne va valider qu'il a fait toutes les tâches]
    L -->|Interagir avec l'environnement| L
    L --> M{Jeu termine ?}
    M -->|Oui| N[Jeu terminé]
    M -->|Non| B

```
