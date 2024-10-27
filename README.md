# Astronea

> En tant qu'astronaute, vous devez réparer la tour de communication de votre vaisseau pour demander de l'aide après que celui-ci aie mystérieusement cesser de fonctionner.

### Description

Plongez dans l'univers captivant Astronea, un jeu VR où vous incarnez un astronaute de la compagnie intergalactique StellarCorp. Envoyé sur une base spatiale pour étudier des astres mystérieux, votre mission prend une tournure inattendue lorsque votre vaisseau cesse mystérieusement de fonctionner.

Face à l'urgence, vous devez réparer la tour de communication afin de demander de l'aide. Explorez un environnement fascinant, rempli de technologies avancées et de paysages spatiaux éblouissants. Résolvez des énigmes complexes et interagissez avec des éléments de votre environnement pour restaurer le fonctionnement de votre vaisseau.

### Moodboard

#### Visuel

![Moodboard Visuel]()

#### Sonore

Ambiances composées d'une basse synthétisée, de nappes de synthé et de leads de synthé. <br>
[lonnex - losing (slowed and reverb)](https://youtu.be/KZrvnPOu5oU?si=-EyvkCBBUJ0rWzIe) <br>
[lonnex - losing](https://youtu.be/BgBNLX_3afs?si=vbkmEJgLcy-1HkoC) <br>
[liminalyx - cold loneliness](https://youtu.be/xqp4gNT410s?si=xMWUA3M1ONo_CCdn) <br>
[cholosus - Dream](https://youtu.be/se5uNCrig18?si=1A6mLVT9Ko01AWEO) <br>
[SymphoCat - Long Whale Song](https://youtu.be/Glrwf8rKBXw?si=dz6L2nXC5B8sKCXO) <br>
[.diedlonely - avenoir](https://youtu.be/xF6Z8PdFbZQ?si=Gps7YuQKD7YOBPhE) <br>
[SymphoCat - Blue Whale](https://youtu.be/krSuui3nwqQ?si=G1x6yA_Nd2OJu_S9) <br>

### effet sonore
[prendre bouteille](https://pixabay.com/fr/sound-effects/bottle-clink-101000/) <br>

### Schéma d'interactivité

```mermaid
flowchart TD
    A[Personne met le casque VR] --> B[Personne joue au jeu]
    B --> C[Personne lit le journal de bord et les tâches à réaliser]
    C --> D[Personne va dans la première pièce débarrée]
    D --> E[Personne résout le puzzle]
    E --> F[Personne sort de la pièce pour aller dans la prochaine pièce débarrée]
    F --> G[Personne résout le puzzle]
    G --> H[Personne sort de la pièce pour aller dans la prochaine pièce débarrée]
    H --> I[Personne résout le puzzle]
    I --> J[Personne sort de la pièce pour aller dans la prochaine pièce débarrée]
    J --> K[Personne résout le puzzle]
    K --> L[Personne va valider qu'il a fait toutes les tâches]
    L --> M{Jeu termine ?}
    M -->|Oui| N[Jeu terminé]
    M -->|Non| B
    A --> O[Personne interagit avec l'environnement]
    B --> O
    C --> O
    D --> O
    E --> O
    F --> O
    G --> O
    H --> O
    I --> O
    J --> O
    K --> O
    L --> O

```
