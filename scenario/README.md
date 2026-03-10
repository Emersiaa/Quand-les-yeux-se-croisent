# Scénario

Cette section présente le scénario de l'interactivité du projet.

## Scénarisation de l'interactivité

### Scène 1

| Verbe action | Condition de déclenchement | Effet visuel | Effet sonore | Effet interactif |
|--------------|-----------------------------|--------------|--------------|------------------|
| Entrer | Le visiteur suit le tapis vers l'exposition | Des empreintes d'animaux sur le tapis indiquent la direction | Une musique de fond organique légère boucle | NA |
| Se déplacer | Le visiteur circule autour des télévisions sans entrer dans la zone de détection | Les télévisions rétro diffusent en boucle des regards d’animaux animés par un effet de morphing de particules | La musique de fond organique se poursuit | L’installation demeure en mode contemplatif |
| S'approcher | S’approche du faisceau lumineux qui invite le visiteur à se positionner devant les télévisions | Les regards d’animaux continuent de défiler tandis que les lumières LED deviennent plus intenses pour signaler la zone d’interaction | La même musique de fond joue après un son de carillon une fois la présence captée | L'installation reconnait la présence du visiteur et passe à la scène 2 |

### Scène 2

| Verbe action | Condition de déclenchement | Effet visuel | Effet sonore | Effet interactif |
|--------------|-----------------------------|--------------|--------------|------------------|
| Rester en place | Détection captée par le capteur (caméra) | Les yeux d'animaux de deux télévisions se transforment en l’œil de l’interacteur en temps réel et les lumières LED changent de couleur | La même musique de fond joue avec des textures sonores inspirées d’animaux | L'installation traduit les gestes en visuels et lumières |
| Se déplace de gauche à droite | Mouvements captés par le capteur (caméra) | Les yeux de deux télévisions, maintenant ceux de l’interacteur, suivent le mouvement de la personne | La même musique de fond joue avec les textures sonores d'animaux | L'installation traduit les gestes en visuels et lumières |
| Se déplace de l'arrière à l'avant | Mouvements captés par le capteur (caméra) | Les yeux de deux télévisions, maintenant ceux de l’interacteur, se rapprochent ou s’éloignent visuellement selon la position de la personne | La même musique de fond joue avec les textures sonores d'animaux | L'installation traduit les gestes en visuels et lumières |
| Plusieurs personnes présentes | Mouvements captés de plusieurs personnes | Les yeux d'animaux de deux télévisions se transforment en l’œil de la première personne captée et les lumières LED changent de couleur | La même musique de fond joue avec les textures sonores d'animaux | L'installation priorise un seul interacteur |
| Caméra obstruée | Capteur perd la présence de l'interacteur | Les regards humains disparaissent progressivement et les yeux d’animaux réapparaissent. Les lumières redeviennent à leur état initial avec une animation respiratoire | La même musique de fond joue avec les textures sonores d'animaux et un son de carillon inversé | Fin du cycle - passe à la scène 3 |
| Reste trop longtemps | L'interacteur reste plus de 2 minutes | Les regards humains se transforment en animaux et les lumières redeviennent à leur état initial avec une animation respiratoire | La même musique de fond joue avec les textures sonores d'animaux et un son de carillon inversé | Fin du cycle - passe à la scène 3 |

### Scène 3

| Verbe action | Condition de déclenchement | Effet visuel | Effet sonore | Effet interactif |
|--------------|----------------------------|--------------|--------------|------------------|
| Quitter | Inactivité totale | Les télévisions alternent entre les regards d’animaux et les yeux humains déjà captés. Les petits écrans présentent en boucle la collection de regards enregistrés et les lumières reprennent leur animation respiratoire | La même musique de fond joue avec une texture sonore évoquant une respiration | Passe à la scène 1 |