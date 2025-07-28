# JStore - E-Commerce Template

Un template moderne et responsive pour site e-commerce développé avec HTML, CSS et JavaScript.

![JStore Logo](assets/images/favicon.png)

## 📋 Description

JStore est un template complet d'e-commerce conçu pour créer des boutiques en ligne modernes et attrayantes. Le template inclut toutes les pages essentielles d'un site e-commerce avec un design responsive et des fonctionnalités interactives.

## ✨ Fonctionnalités

### 🎨 Design & Interface
- **Design Responsive** : Compatible avec tous les appareils (desktop, tablette, mobile)
- **Interface Moderne** : Design contemporain avec animations et transitions fluides
- **Navigation Mobile** : Menu hamburger optimisé pour mobile
- **Slider Interactif** : Carrousel d'images avec navigation
- **Animations CSS** : Transitions et effets visuels

### 📄 Pages Incluses
- **Page d'Accueil** (`index.html`) : Vitrine principale avec produits et promotions
- **Connexion** (`signin.html`) : Formulaire de connexion utilisateur
- **Inscription** (`signup.html`) : Formulaire d'inscription utilisateur
- **Page 404** (`404.html`) : Page d'erreur personnalisée

### 🛍️ Fonctionnalités E-Commerce
- **Catalogue Produits** : Affichage des produits avec catégories
- **Panier d'Achat** : Interface panier avec navigation mobile
- **Système de Promotions** : Bannières et offres spéciales
- **Recherche Produits** : Barre de recherche intégrée
- **Wishlist** : Liste de souhaits
- **Méthodes de Paiement** : Support cartes bancaires (Visa, Mastercard, etc.)

### 🔧 Technique
- **HTML5 Sémantique** : Structure optimisée pour le SEO
- **CSS3 Moderne** : Flexbox, Grid, animations
- **JavaScript Vanilla** : Interactions sans framework
- **Font Awesome** : Icônes vectorielles
- **Compatible Navigateurs** : Support des navigateurs modernes
- **Assets Organisés** : Structure de fichiers claire

## 🏗️ Structure du Projet

```
JSTORE/
│
├── index.html              # Page d'accueil
├── signin.html             # Page de connexion
├── signup.html             # Page d'inscription
├── 404.html               # Page d'erreur
├── README.md              # Documentation
│
├── assets/
│   ├── css/
│   │   ├── main.css              # Styles principaux
│   │   ├── styles.css            # Styles additionnels
│   │   ├── color.css             # Palette de couleurs
│   │   ├── z-index.css           # Gestion des z-index
│   │   │
│   │   ├── components/           # Composants CSS
│   │   │   ├── header.css        # En-tête
│   │   │   ├── nav.css           # Navigation
│   │   │   ├── footer.css        # Pied de page
│   │   │   ├── cart.css          # Panier
│   │   │   ├── product.css       # Produits
│   │   │   ├── slider.css        # Carrousel
│   │   │   ├── mobile.css        # Version mobile
│   │   │   ├── media.css         # Media queries
│   │   │   └── ...
│   │   │
│   │   └── framework/
│   │       └── utiles.css        # Classes utilitaires
│   │
│   ├── js/
│   │   ├── main.js               # Script principal
│   │   └── main_v1.js            # Version alternative
│   │
│   └── images/
│       ├── favicon.png           # Icône du site
│       ├── banner/               # Images bannières
│       ├── brand/                # Logos marques
│       ├── card/                 # Icônes cartes bancaires
│       ├── flags/                # Drapeaux pays
│       ├── icons/                # Icônes diverses
│       ├── post/                 # Images articles
│       ├── product/              # Images produits
│       │   ├── best-seller/
│       │   ├── categories/
│       │   ├── featured/
│       │   ├── latest-new/
│       │   ├── latest-products/
│       │   ├── new-arrivals/
│       │   └── top-rated/
│       └── slider/               # Images carrousel
```

## 🚀 Installation et Utilisation

### Prérequis
- Navigateur web moderne
- Serveur web local (optionnel)

### Installation
1. **Cloner ou télécharger** le projet :
   ```bash
   git clone https://github.com/espero-soft/e-commerce_template.git
   cd JSTORE
   ```

2. **Ouvrir le projet** :
   - Ouvrir `index.html` directement dans un navigateur
   - Ou utiliser un serveur local :
     ```bash
     # Avec Python
     python -m http.server 8000
     
     # Avec Node.js (live-server)
     npx live-server
     
     # Avec VS Code Live Server extension
     ```

3. **Accéder au site** :
   - Navigateur direct : `file:///chemin/vers/index.html`
   - Serveur local : `http://localhost:8000`

### Pages Disponibles
- **Accueil** : `index.html`
- **Connexion** : `signin.html`
- **Inscription** : `signup.html`
- **Erreur 404** : `404.html`

## 🎨 Personnalisation

### Couleurs
Modifier les couleurs dans `assets/css/color.css` :
```css
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
    --accent-color: #your-color;
}
```

### Images
- Remplacer les images dans `assets/images/`
- Respecter les dimensions existantes
- Formats supportés : JPG, PNG, SVG, WebP

### Contenu
- Modifier les textes directement dans les fichiers HTML
- Adapter les liens et URLs
- Personnaliser les formulaires

### Styles
- Styles principaux : `assets/css/main.css`
- Composants : `assets/css/components/`
- Responsive : `assets/css/components/media.css`

## 📱 Responsive Design

Le template est optimisé pour :
- **Desktop** : > 1024px
- **Tablette** : 768px - 1024px
- **Mobile** : < 768px

Breakpoints principaux :
```css
/* Mobile First */
@media (min-width: 768px) { /* Tablette */ }
@media (min-width: 1024px) { /* Desktop */ }
@media (min-width: 1200px) { /* Large Desktop */ }
```

## 🔧 Fonctionnalités JavaScript

### Navigation Mobile
```javascript
// Toggle menu mobile
const toggleNav = (event) => {
    // Gestion ouverture/fermeture menu
}
```

### Fonctionnalités Incluses
- Menu hamburger
- Panier coulissant
- Animations smooth
- Navigation tactile

## 🎯 SEO et Performance

### Optimisations SEO
- Structure HTML5 sémantique
- Meta tags optimisés
- Attributs alt sur les images
- URLs descriptives

### Performance
- Images optimisées (WebP quand possible)
- CSS minifié en production
- Chargement asynchrone des ressources
- Structure CSS modulaire

## 🌐 Compatibilité Navigateurs

| Navigateur | Version Minimum |
|------------|----------------|
| Chrome     | 60+            |
| Firefox    | 55+            |
| Safari     | 12+            |
| Edge       | 79+            |

## 📦 Dépendances

### CDN Utilisés
- **Font Awesome 6.1.1** : Icônes vectorielles
  ```html
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css">
  ```

### Polices
- System fonts par défaut
- Fallbacks inclus

## 🤝 Contribution

1. Fork le projet
2. Créer une branche (`git checkout -b feature/amelioration`)
3. Commit les changements (`git commit -am 'Ajout nouvelle fonctionnalité'`)
4. Push vers la branche (`git push origin feature/amelioration`)
5. Créer une Pull Request

## 📋 Roadmap

### Version Future
- [ ] Intégration API e-commerce
- [ ] Système de paiement
- [ ] Dashboard admin
- [ ] Multi-langues
- [ ] Mode sombre
- [ ] PWA support

## 🐛 Problèmes Connus

- Navigation mobile peut nécessiter un double-tap sur certains appareils
- Images lourdes peuvent impacter le temps de chargement initial

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 👥 Auteurs

- **Espero Soft** - Développement initial
- GitHub : [@espero-soft](https://github.com/espero-soft)

## 📞 Support

- **Issues** : [GitHub Issues](https://github.com/espero-soft/e-commerce_template/issues)
- **Email** : support@espero-soft.com
- **Documentation** : Ce README

## 🔗 Liens Utiles

- [Démo Live](https://espero-soft.github.io/e-commerce_template)
- [Documentation CSS](assets/css/README.md)
- [Guide de Contribution](CONTRIBUTING.md)

---

⭐ **N'oubliez pas de mettre une étoile si ce projet vous a aidé !**
