# Feane - Site Web de Restaurant



## Description

**Feane** est un site web complet de restaurant développé exclusivement avec **HTML, CSS et Bootstrap**. Le projet reproduit un design moderne et élégant, comprenant plusieurs pages (Accueil, Menu, À propos, Réservation) avec un design responsive et une navigation fluide.

Le site met en avant une expérience utilisateur optimale avec des animations subtiles, une palette de couleurs chaleureuse (noir et orange/jaune) et une typographie soignée.

## Objectifs du Projet

-  **Structurer un site web complet** avec HTML et CSS
-  **Maîtriser Bootstrap** pour créer des layouts responsives
-  **Reproduire un design existant** en respectant l'apparence visuelle
- **Développer l'autonomie** dans le choix des polices et couleurs
- **Créer une expérience utilisateur fluide** sur tous les appareils

## Technologies Utilisées

- **HTML5** - Structure sémantique et accessible
- **CSS3** - Styles personnalisés, animations et transitions
- **Bootstrap 5.3** - Framework CSS pour le responsive design
- **Bootstrap Icons** - Bibliothèque d'icônes moderne
- **Google Fonts** - Polices personnalisées (Dancing Script + Poppins)

## 📋Spécifications Techniques

### Responsive Design
- **Mobile First** - Optimisé pour tous les écrans
- **Breakpoints Bootstrap** - Tablette (768px) et Desktop (992px)
- **Navigation adaptative** - Menu burger sur mobile

### Fonctionnalités
-  Menu de navigation fixe et responsive
- Sections d'offres promotionnelles
- Catalogue de plats avec filtres
- Formulaire de réservation complet
- Section témoignages clients
- Footer avec informations de contact

## 📄 Structure du Projet


feane/
├── index.html              # Page d'accueil
├── menu.html              # Page menu des plats
├── about.html             # Page à propos
├── book.html              # Page réservation
├── css/
│   └── style.css          # Styles personnalisés
├── images/                # Dossier des images
│   ├── hero-burger.jpg
│   ├── menu-items/
│   └── testimonials/
└── README.md              # Documentation
```

## Pages du Site

### 1. **Page d'Accueil (index.html)**
-  Hero section avec image de burger et CTA
- Cartes d'offres promotionnelles (20% et 15% de réduction)
- Aperçu du menu avec filtres
- Section "About Us" avec animation
- Formulaire de réservation
- Témoignages clients

### 2. **Page Menu (menu.html)**
- Filtres par catégories (All, Burger, Pizza, Pasta, Fries)
- Grille de plats responsive (3/2/1 colonnes)
- Boutons "Add to Cart" sur chaque plat
- Prix clairement affichés

### 3. **Page À Propos (about.html)**
- Histoire du restaurant
- Présentation de l'équipe
-  Valeurs et engagement qualité

### 4. **Page Réservation (book.html)**
-  Formulaire complet de réservation
  - Nom complet
  - Numéro de téléphone
  - Email
  - Nombre de personnes (dropdown)
  - Date de réservation (date picker)
- Carte Google Maps intégrée
- Informations de contact

## Design & Identité Visuelle

### Palette de Couleurs
```css
--primary-color: #ffbe33;    /* Jaune/Orange */
--dark-bg: #222831;          /* Noir/Gris foncé */
--text-light: #ffffff;        /* Blanc */
--light-bg: #f8f9fa;         /* Gris clair */
```

### Typographie
- **Titres** : Dancing Script (cursive, style élégant)
- **Corps de texte** : Poppins (moderne, lisible)

### Composants Clés
- Boutons arrondis avec effet hover
- Cartes avec shadow et transition au survol
- Images circulaires pour les témoignages
- Icônes Bootstrap pour les actions

##  Responsivité

| Breakpoint | Taille | Layout Menu | Navigation |
|------------|--------|-------------|------------|
| Mobile | < 768px | 1 colonne | Menu burger |
| Tablette | 768px - 991px | 2 colonnes | Menu burger |
| Desktop | ≥ 992px | 3 colonnes | Menu horizontal |

## Installation & Utilisation

### 1. Cloner le repository

git clone https://github.com/Mika-illou/-Feane.git


### 2. Ouvrir le projet

# Option 1 : Ouvrir directement dans le navigateur
open index.html

# Option 2 : Utiliser un serveur local (recommandé)
python -m http.server 8000
# Puis ouvrir http://localhost:8000


### 3. Navigation
- **Accueil** : `index.html`
- **Menu** : `menu.html`
- **À propos** : `about.html`
- **Réservation** : `book.html`

## Classes Bootstrap Utilisées

### Layout & Grid
- `container`, `container-fluid`
- `row`, `col-*`, `g-*` (gutters)
- `d-flex`, `justify-content-*`, `align-items-*`

### Composants
- `navbar`, `navbar-toggler`, `navbar-collapse`
- `card`, `card-body`, `card-img-top`
- `btn`, `btn-*` (variantes)
- `form-control`, `form-select`

### Utilitaires
- `m-*`, `p-*`, `mb-*`, `mt-*` (marges/paddings)
- `text-*` (alignement, couleurs)
- `d-none`, `d-md-block`, `d-lg-flex` (responsive display)
- `position-*`, `top-*`, `start-*`
- `rounded`, `shadow`, `border-*`

## Fonctionnalités Avancées

### Animations CSS
- **Float animation** pour les images de burger
- **Hover effects** sur les cartes de menu
- **Transitions** douces sur les boutons
- **Scale transform** au survol



##  Ressources Utilisées

### Documentation
- [Bootstrap 5.3 Documentation](https://getbootstrap.com/docs/5.3/)
- [MDN HTML](https://developer.mozilla.org/fr/docs/Web/HTML)
- [MDN CSS](https://developer.mozilla.org/fr/docs/Web/CSS)

## 🎓 Compétences Développées

### Techniques
-  Structuration HTML sémantique
-  Maîtrise de Bootstrap (grid, composants, utilitaires)
- CSS avancé (flexbox, animations, transitions)
- Responsive design mobile-first
-  Intégration de polices personnalisées

### Méthodologiques
-  Analyse et reproduction d'un design
-  Organisation de code propre et maintenable
- Gestion de projet avec Git/GitHub
- Recherche autonome de solutions
- Documentation technique


## Auteur

**Mika Illou**
- GitHub : [@Mika-illou](https://github.com/Mika-illou)
- Projet : Restaurant Feane
- Formation : Développement Web

## Licence

Ce projet est réalisé dans un cadre éducatif.

