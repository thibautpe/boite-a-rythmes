# K.O. II — boîte à rythmes web

K.O. II est une application PWA statique de boîte à rythmes visuelle, conçue pour être simple, portable et compatible avec un hébergement statique comme GitHub Pages.

L’interface est pensée pour être facile à prendre en main, avec des commandes rapides et une logique de séquenceur qui reste lisible même sur écran petit.

## Fichiers principaux

- `index.html` : interface principale et logique du séquenceur
- `sw.js` : service worker pour le cache PWA et la gestion des mises à jour
- `manifest.webmanifest` : configuration d’installation de l’application
- `icons/` : icônes de l’application

## Installation rapide

1. Place le contenu du dépôt à la racine d’un dépôt GitHub
2. Ouvre `Settings` → `Pages` → `Source` → `Deploy from a branch`
3. Sélectionne la branche `main` et le dossier `/ (root)`
4. L’application est ensuite accessible à l’URL : `https://<ton-pseudo>.github.io/<nom-du-depot>/`

## Installer comme application

- PC (Chrome / Edge) : icône d’installation dans la barre d’adresse
- Android (Chrome) : menu `⋮` → `Installer l’application`
- iPhone / iPad (Safari) : `Partager` → `Sur l’écran d’accueil`

## Utilisation rapide

- Les 12 pads déclenchent les sons et servent aussi de clavier numérique
- Les groupes A à D jouent chacun un pattern indépendant
- `play` lance ou arrête le séquenceur
- `rec` active l’enregistrement en direct
- `shift` active des fonctions secondaires
- Les boutons `−` et `+` ajustent le mode courant (tempo, longueur, timing, etc.)

## PWA et mode hors ligne

- Après une première visite en ligne, l’application peut fonctionner hors ligne
- Le service worker met en cache les ressources de l’application
- Les anciennes versions sont invalidées lors du déploiement

## Changelog

- Dernière mise à jour : 2026-10-15
- Modifications : alignement du dépôt sur la version actuelle de K.O. II ; mise à jour des fichiers PWA ; documentation rassemblée pour refléter l’interface livrée
- À venir : validation du comportement clavier sur navigations anciennes, nettoyage des presets et documentation avancée

## Liens utiles

- [README principal](../README.md)
- [Installation](Installation.md)
- [Utilisation](Utilisation.md)
- [Raccourcis clavier](Raccourcis-clavier.md)
- [Journal des changements](Changelog.md)

---

Cette documentation est aussi disponible dans le dépôt sous `docs/wiki/` pour une consultation simple et une maintenance facile.
