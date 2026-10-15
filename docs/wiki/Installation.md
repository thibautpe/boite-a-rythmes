# Installation

## Déploiement GitHub Pages

Le projet est conçu pour être publié sur GitHub Pages sans étape de build.

### Étapes

1. Envoie le contenu du dépôt à la racine du repository
2. Ouvre `Settings` → `Pages`
3. Sélectionne `Deploy from a branch`
4. Choisis la branche `main`
5. Choisis le dossier `/ (root)`
6. Sauvegarde et attends quelques minutes

L’URL de la page sera du type :

```text
https://<ton-pseudo>.github.io/<nom-du-depot>/
```

## Installer l’application

### Sur ordinateur

- Chrome / Edge : cliquer sur l’icône d’installation dans la barre d’adresse

### Sur Android

- Ouvrir le site dans Chrome
- Menu `⋮` → `Installer l’application`

### Sur iPhone / iPad

- Ouvrir le site dans Safari
- `Partager` → `Sur l’écran d’accueil`

## Prérequis

Aucun prérequis technique particulier n’est nécessaire, si ce n’est un navigateur moderne supportant l’API Audio du navigateur.

## Bonnes pratiques

- Les chemins sont relatifs, ce qui évite les problèmes sur GitHub Pages
- Le projet a été pensé pour fonctionner dans un sous-dossier et dans le dépôt racine
- L’application fonctionne hors ligne après une première visite en ligne

## Vérification rapide

Après publication, vérifie que :

- la page se charge sans erreur JavaScript
- le bouton `play` active le séquenceur
- le son est audible dans le navigateur
- l’icône d’installation apparaît si le navigateur le permet

---

Retour à la [page d’accueil](Home.md)
