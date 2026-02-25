# Portfolio Professionnel - Thibaut Lhernout

Ce projet est un portfolio moderne et responsive réalisé dans le cadre du **BUT Réseaux et Télécommunications (R&T)** à l'IUT de Béthune.

## 🚀 Caractéristiques

- **Design Moderne & Cyber** : Thème sombre avec des accents cyan/bleu, animations fluides et esthétique soignée.
- **Entièrement Responsive** : Adapté aux smartphones, tablettes et ordinateurs de bureau.
- **Filtrage Dynamique** : Système de filtrage par compétences (PN BUT R&T) pour organiser les projets SAE.
- **Certification W3C** : Code HTML et CSS propre suivant les standards du web.
- **CV Intégré** : Version web complète du CV professionnel.

## 📁 Structure du Projet

- `index.html` : Page d'accueil avec présentation personnelle.
- `cv.html` : Curriculum Vitae complet.
- `portfolio.html` : Galerie de projets avec système de filtrage.
- `legal.html` : Mentions légales et crédits.
- `style.css` : Styles globaux, variables CSS et media queries.
- `assets/` : Dossier contenant les images et ressources (dont `me.jpg`).

## 🛠️ Technologies Utilisées

- **HTML5** : Structure sémantique.
- **CSS3** : CSS Grid, Flexbox, Variables (Custom Properties), Animations.
- **JavaScript** : Menu mobile et logique de filtrage des projets (Vanilla JS).

## 📝 Comment ajouter un projet ?

Pour ajouter une nouvelle SAE ou un projet personnel dans `portfolio.html` :

1. Repérez la section `<div class="grid" style="gap: var(--space-lg);">`.
2. Ajoutez un élément `<article>` avec la structure suivante :

```html
<article class="cv-container project-item" data-category="NOM_CATEGORIE">
    <h3 style="color: var(--primary); margin-bottom: 0.5rem;">Nom du Projet</h3>
    <p>Description courte...</p>
    <ul>
        <li>Détail 1</li>
        <li>Détail 2</li>
    </ul>
</article>
```

*Catégories disponibles pour `data-category` : `admin`, `connect`, `prog`, `secu`, `surv`.*

---
*Réalisé par Thibaut Lhernout - Hébergé sur GitHub Pages.*
# Thibaut-Lhernout.github.io
