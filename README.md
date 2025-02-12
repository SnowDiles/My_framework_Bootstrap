# Framework UI

Un framework CSS léger et flexible pour créer des interfaces utilisateur modernes et responsives.

## Table des matières

- [Installation](#installation)
- [Fonctionnalités](#fonctionnalités)
- [Composants](#composants)
- [Système de grille](#système-de-grille)
- [Utilitaires](#utilitaires)

## Installation

```html
<!-- Ajoutez le CSS dans votre <head> -->
<link rel="stylesheet" href="path/to/framework.css">
```

## Fonctionnalités

- Système de grille responsive basé sur CSS Grid
- Composants UI préconçus
- Classes utilitaires
- Design moderne et personnalisable
- Support mobile-first

## Composants

### Boutons

Plusieurs styles de boutons sont disponibles :

```html
<button class="btn btn-primary">Bouton Primary</button>
<button class="btn btn-secondary">Bouton Secondaire</button>
<button class="btn btn-success">Bouton Succès</button>
<button class="btn btn-danger">Bouton Danger</button>
<button class="btn btn-warning">Bouton Avertissement</button>
```

États des boutons :
- `.active` - Pour l'état actif
- `.disabled` - Pour désactiver un bouton

### Images

Classes disponibles pour les images :
- `.img-responsive` - Images responsives
- `.img-rounded` - Coins arrondis
- `.img-circle` - Image circulaire
- `.img-thumbnail` - Style vignette
- `.img-blur` - Effet de flou

### Alertes

```html
<div class="alert alert-primary" role="alert">Message d'alerte</div>
<div class="alert alert-success" role="alert">Message de succès</div>
```

## Système de grille

Le système de grille utilise un modèle à 12 colonnes avec différents breakpoints :

| Breakpoint    | Préfixe      | Dimension  |
|--------------|--------------|------------|
| Extra small  | `.col-`      | < 576px    |
| Small        | `.col-sm-`   | ≥ 576px    |
| Medium       | `.col-md-`   | ≥ 768px    |
| Large        | `.col-lg-`   | ≥ 992px    |
| Extra large  | `.col-xl-`   | ≥ 1200px   |

### Utilisation de base

```html
<div class="container">
  <div class="row">
    <div class="col-md-6">Colonne 6/12</div>
    <div class="col-md-6">Colonne 6/12</div>
  </div>
</div>
```

### Bonnes pratiques

1. Utilisez toujours la structure `.container > .row > .col-*`
2. Préférez les classes responsive pour une meilleure adaptation mobile
3. Limitez-vous à 12 colonnes par ligne

## Utilitaires

### Couleurs de texte

```html
<p class="text-primary">Texte primary</p>
<p class="text-secondary">Texte secondary</p>
<p class="text-success">Texte success</p>
<p class="text-info">Texte info</p>
<p class="text-warning">Texte warning</p>
<p class="text-danger">Texte danger</p>
```

### Couleurs de fond

```html
<div class="bg-primary">Fond primary</div>
<div class="bg-secondary">Fond secondary</div>
<div class="bg-success">Fond success</div>
<div class="bg-info">Fond info</div>
<div class="bg-warning">Fond warning</div>
<div class="bg-danger">Fond danger</div>
```

## Contribution

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou à soumettre une pull request.

## Licence

MIT
