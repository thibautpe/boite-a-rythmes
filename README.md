# K.O. II — boîte à rythmes web

Application PWA statique de boîte à rythmes visuelle. L’interface est conçue pour être simple, portable et compatible avec un hébergement statique comme GitHub Pages.

Fichiers principaux :
- `index.html` : interface principale et logique de séquenceur
- `sw.js` : cache PWA et mise à jour de version
- `manifest.webmanifest` : configuration d’installation de l’application
- `icons/` : icônes de l’application

## Publier sur GitHub Pages
1. Crée un dépôt (ex. `metronome`) et envoie-y le contenu de ce dossier à la racine.
2. Ouvre le dépôt > Settings > Pages > Source : *Deploy from a branch*, branche `main`, dossier `/ (root)`.
3. Après une minute : `https://<ton-pseudo>.github.io/metronome/`.

## Installer
- PC (Chrome / Edge) : icône « Installer » dans la barre d’adresse.
- Android (Chrome) : menu ⋮ > « Installer l’application ».
- iPhone / iPad (Safari) : Partager > « Sur l’écran d’accueil ».

## Utiliser
- Les 12 pads déclenchent les sons et servent aussi de clavier numérique.
- Les groupes A à D jouent chacun un pattern indépendant.
- Le bouton `play` lance le séquenceur, `rec` active l’enregistrement en direct et `shift` active les actions secondaires.
- Les boutons `−` et `+` ajustent le mode courant (tempo, longueur, timing, etc.).

- Dernière mise à jour : 2026-10-15
- Modifications : ajout d’un mode d’entraînement, d’un tap tempo, de presets locaux, du mode performance live, du phraseur de patterns, du mode paint, de nouveaux effets audio avancés ainsi que de kits supplémentaires et de réglages de niveau par groupe ; mise à jour du cache PWA et de la version de publication.
- À venir : validation mobile finale, polish UX et enrichissement des sons disponibles.

### Feature active : performance live + effets
- Le bouton `live` active un mode de scène plus rapide pour jouer et ajuster un groove en direct.
- Le bouton `fill` injecte un accent rapide sur le pattern courant.
- Le bouton `mute all` coupe ou remet tout le son d’un coup pour préparer un break ou une transition.
- Le bouton `phrase` active un cycle de quatre motifs pour créer une section en boucle.
- Le bouton `paint` active l’édition rapide des steps par glisser-déposer.
- Les effets `reverb` et `saturation` sont désormais pilotés via les effets du séquenceur.

## Notes
- Tous les chemins sont relatifs : le projet fonctionne dans un sous-dossier GitHub Pages.
- Le PWA fonctionne hors ligne après une première visite en ligne.
- Le service worker met en cache les ressources installées et invalide les anciennes versions lors du déploiement.
