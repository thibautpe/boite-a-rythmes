# Utilisation

## Vue d’ensemble

K.O. II est une boîte à rythmes visuelle orientée séquenceur. L’écran est découpé en plusieurs zones fonctionnelles :

- écran de contrôle central
- grille de pattern
- groupes A à D
- pads sonores
- modes de réglage
- commandes playback et enregistrement

## Les groupes

Le projet contient quatre groupes : A, B, C et D.

Chacun de ces groupes dispose de :

- un pattern indépendant
- 12 sons
- un niveau sonore propre
- un comportement de synchronisation cohérent avec le tempo global

## Les pads

Il y a 12 pads. Ils servent à :

- jouer les sons
- sélectionner un son ou une piste éditable
- entrer des valeurs numériques pour le mode `ptn`
- déclencher des actions rapides selon le mode actif

Les sons sont répartis par logique d’instrumentation :

- Groupe A : percussions
- Groupe B : basse
- Groupe C : pluck / synthèse aiguë
- Groupe D : cloches / résonance

## Contrôle du séquenceur

### Play / Stop

Le bouton `play` active ou coupe le cycle.

### Pause / tempo

Le mode `tempo` permet d’ajuster le BPM. Le projet couvre une plage pratique et stable pour le groove.

### Longueur du pattern

Le mode `length` permet de modifier la longueur du pattern, de 1 à 64 steps selon la logique interne du séquenceur.

### Timing

Le mode `timing` permet de choisir la valeur de subdivision de la grille, par exemple :

- `1/1`
- `1/2`
- `1/4`
- `1/8`
- `1/8T`
- `1/16`
- `1/16T`
- `1/32`

Le suffixe `T` indique un triolet.

## Enregistrement direct

Le bouton `rec` active l’enregistrement en direct. Pendant l’enregistrement, les notes jouées peuvent être mémorisées dans le pattern courant.

## Fader

Le fader permet de régler rapidement des paramètres globaux ou de groupe, notamment :

- level
- pitch
- decay
- swing

## Édition de son

Le mode `sound` / `edit` permet de modifier la hauteur et la durée du son sélectionné, via les knobs ou les réglages associés.

## Échantillonnage

Le mode `sample` permet d’enregistrer un échantillon depuis le microphone, puis de l’associer à un pad.

### Limites pratiques

- durée limitée pour éviter la surcharge mémoire
- la qualité dépend de la source audio et du navigateur

## Conseils

- Commence par le mode `ptn` pour créer un groove simple
- Utilise les groupes pour séparer percussion, basse et harmonies
- Réduis la durée pour tester rapidement des idées
- Garde le `tempo` stable pendant les réglages d’édition

---

Retour à la [page d’accueil](Home.md)
