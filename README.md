# VELA Landing Page

Page de landing responsive pour VELA Business Media - Plateforme d'accompagnement business.

## Structure du projet

```
.
├── index.html           # Page HTML principale
├── styles/
│   └── main.css        # Styles CSS (animations incluses)
├── js/
│   └── main.js         # JavaScript pour interactions et animations
├── assets/
│   └── images/         # Dossier pour les images
└── README.md           # Ce fichier
```

## Fonctionnalités

- ✨ Animations fluides et modernes
- 📱 Design responsive (desktop, tablet, mobile)
- 🎨 Palette de couleurs VELA (bleus professionnels)
- ♿ Navigation accessible
- ⚡ Performance optimisée
- 🎥 Section vidéo interactive
- 📊 Animations de compteurs
- 🎯 Appels à l'action clairs

## Sections de la page

1. **Header** - Navigation sticky avec logo et CTA
2. **Hero** - Section principale avec texte et vidéo
3. **Features** - 4 points clés de la plateforme
4. **Pillars** - Les 5 piliers (Admin, Finance, Commerce, RH, Production)
5. **Pricing** - Présentation de l'offre avec illustration
6. **Levels** - Les 5 niveaux de parcours
7. **Journey** - Processus en 4 étapes
8. **Dashboard** - Aperçu de l'interface utilisateur
9. **CTA** - Appel à l'action final
10. **Footer** - Pied de page

## Animations

- **Fade In** - Les éléments s'apparaissent graduellement
- **Slide In** - Apparition avec translation depuis la droite
- **Fade In Up** - Apparition avec translation depuis le bas
- **Float** - Animation flottante du deltaplane
- **Hover Effects** - Interactions au survol des boutons et cartes

## Utilisation

1. Ouvrir `index.html` dans un navigateur
2. Les animations se déclenchent au scroll
3. Cliquer sur les liens de navigation pour un scroll fluide
4. Cliquer sur la vidéo pour voir le comportement interactif

## Personnalisation

### Couleurs
Modifier les variables CSS dans `main.css` :
```css
:root {
    --primary-blue: #2B5AA7;
    --light-blue: #4A90E2;
    --dark-blue: #1E3D66;
    /* ... */
}
```

### Contenu
Modifier directement dans `index.html` les textes et contenu.

### Images
Ajouter les images dans le dossier `assets/images/` et les référencer dans le HTML.

## Compatibilité navigateurs

- Chrome/Edge (dernières versions)
- Firefox (dernières versions)
- Safari (dernières versions)
- Support mobile complet

## Notes techniques

- Pas de dépendances externes
- CSS Grid et Flexbox pour le layout
- Intersection Observer pour les animations au scroll
- Smooth scroll natif
- Media queries pour la responsivité
