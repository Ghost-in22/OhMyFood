# **OhMyFood**

## **Description**

Ce projet, **OhMyFood**, est un site web responsive développé dans le cadre d'une formation. Il permet aux utilisateurs de découvrir les menus de restaurants gastronomiques et de précommander leurs repas avant leur arrivée, afin de réduire le temps d'attente. Le site a été conçu en suivant une approche **mobile-first**, avec un design simple et une expérience utilisateur fluide.

## **Fonctionnalités**

- Page d’accueil avec une **section de localisation des restaurants**.
- Présentation de 4 restaurants avec leurs **menus interactifs**.
- Possibilité pour les utilisateurs de composer leur menu à l’avance.
- **Animations CSS** pour un effet de transition agréable lors du survol des éléments.
- **Responsive** et optimisé pour les appareils mobiles, tablettes et desktop.

## **Technologies utilisées**

### **Frontend :**

- **HTML5** : Structure des pages web.
- **CSS3 (SCSS)** : Gestion avancée des styles avec SCSS, incluant des **variables**, **mixins**, et une **architecture modulaire**.
- **Font Awesome** : Bibliothèque d'icônes pour enrichir l’interface.
- **Google Fonts** : Polices personnalisées pour une typographie cohérente.
- **Flexbox & CSS Grid** : Pour une disposition flexible et responsive des éléments du site.

### **Outils de développement :**

- **VS Code** : Éditeur de code avec des extensions telles que **Prettier** pour garantir la qualité du code.
- **Git & GitHub** : Utilisés pour le contrôle de version et la gestion du projet.
- **Figma** : Outil de design pour la création des maquettes et prototypes du site.
- **GitHub Pages** : Hébergement du projet pour une visualisation en ligne.

## **Installation**

### **Prérequis :**

- **Node.js** et **npm** (pour gérer les dépendances si nécessaire).
- Un éditeur de texte comme **VS Code**.

### **Cloner le projet :**

````bash
git clone https://github.com/Ghost-in22/OhMyFood.git

## **Structure du projet**

OhMyFood/
├── index.html             // Page d'accueil du site
├── restaurant/            // Dossier contenant les pages des restaurants
│   ├── a_la_francaise.html   // Menu du restaurant "À la Française"
│   ├── la_note_enchantee.html // Menu du restaurant "La Note Enchantée"
│   ├── la_palette_du_gout.html // Menu du restaurant "La Palette du Goût"
│   ├── le_delice_des_sens.html // Menu du restaurant "Le Délice des Sens"
├── sass/                  // Dossier contenant les fichiers SASS
│   ├── _base/             // Contient reset, variables, mixins
│   │   ├── _base.scss     // Réinitialisation des styles
│   │   ├── _mixins.scss   // Mixins réutilisables
│   │   └── _variables.scss // Variables globales (couleurs, polices, etc.)
│   ├── _layout/           // Contient header, footer
│   │   ├── _header.scss   // Styles du header global
│   │   └── _footer.scss   // Styles du footer global
│   ├── _modules/          // Contient sections, animations, fonctionnalités
│   │   ├── _animation-check.scss // Animation pour le check (sélecteur de plat)
│   │   ├── _animation-menu-item.scss // Animation pour les items du menu
│   │   ├── _announcement-bar.scss // Style pour la barre d'annonce
│   │   ├── _reservation-section.scss // Section réservation
│   │   ├── _restaurant-page.scss // Page des restaurants
│   │   ├── _restaurant-section.scss // Sections spécifiques du restaurant
│   │   ├── _steps-section.scss // Sections étapes (progression)
│   │   └── loader.scss // Style pour le loader
│   └── main.scss          // Fichier principal qui importe tous les autres fichiers SASS
├── assets/                // Dossier contenant les ressources du projet
│   ├── css/               // Contient des fichiers CSS spécifiques si nécessaires
│   ├── images/            // Contient les images du site
│   ├── icons/             // Contient les icônes utilisées dans le projet
│   └── texts/             // Contient les textes statiques utilisés dans le site
└── README.md              // Documentation du projet



# **OhMyFood**

## **Description**

This project, **OhMyFood**, is a responsive website developed as part of a training program. It allows users to discover the menus of gourmet restaurants and pre-order their meals before arriving, reducing wait times. The website was designed using a **mobile-first** approach, with a simple design and a smooth user experience.

## **Features**

- Homepage with a **restaurant location section**.
- Presentation of 4 restaurants with their **interactive menus**.
- Users can pre-select their meals in advance.
- **CSS Animations** for a pleasant transition effect when hovering over elements.
- **Responsive** and optimized for mobile devices, tablets, and desktops.

## **Technologies Used**

### **Frontend:**
- **HTML5**: Structure of the web pages.
- **CSS3 (SCSS)**: Advanced style management with SCSS, including **variables**, **mixins**, and a **modular architecture**.
- **Font Awesome**: Icon library to enrich the interface.
- **Google Fonts**: Custom fonts for consistent typography.
- **Flexbox & CSS Grid**: For flexible and responsive layout of site elements.

### **Development Tools:**
- **VS Code**: Code editor with extensions like **Prettier** to ensure code quality.
- **Git & GitHub**: Used for version control and project management.
- **Figma**: Design tool for creating mockups and prototypes of the site.
- **GitHub Pages**: Hosting the project for online visualization.

## **Installation**

### **Prerequisites:**
- **Node.js** and **npm** (to manage dependencies if necessary).
- A text editor like **VS Code**.

### **Clone the project:**
```bash
git clone https://github.com/Ghost-in22/OhMyFood.git

## **Project structure**

OhMyFood/
├── index.html             // Homepage of the site
├── restaurant/            // Folder containing restaurant pages
│   ├── a_la_francaise.html   // Menu of the "À la Française" restaurant
│   ├── la_note_enchantee.html // Menu of the "La Note Enchantée" restaurant
│   ├── la_palette_du_gout.html // Menu of the "La Palette du Goût" restaurant
│   ├── le_delice_des_sens.html // Menu of the "Le Délice des Sens" restaurant
├── sass/                  // Folder containing SASS files
│   ├── _base/             // Contains reset, variables, mixins
│   │   ├── _base.scss     // Reset styles
│   │   ├── _mixins.scss   // Reusable mixins
│   │   └── _variables.scss // Global variables (colors, fonts, etc.)
│   ├── _layout/           // Contains header, footer
│   │   ├── _header.scss   // Global header styles
│   │   └── _footer.scss   // Global footer styles
│   ├── _modules/          // Contains sections, animations, features
│   │   ├── _animation-check.scss // Animation for the check (plate selector)
│   │   ├── _animation-menu-item.scss // Animation for menu items
│   │   ├── _announcement-bar.scss // Style for the announcement bar
│   │   ├── _reservation-section.scss // Reservation section
│   │   ├── _restaurant-page.scss // Restaurant page styles
│   │   ├── _restaurant-section.scss // Restaurant-specific sections
│   │   ├── _steps-section.scss // Step progression sections
│   │   └── loader.scss // Loader style
│   └── main.scss          // Main file that imports all other SASS files
├── assets/                // Folder containing project resources
│   ├── css/               // Contains specific CSS files if necessary
│   ├── images/            // Contains images for the site
│   ├── icons/             // Contains icons used in the project
│   └── texts/             // Contains static texts used in the site
└── README.md              // Project documentation

````
