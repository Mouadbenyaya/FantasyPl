# Fantasy Premier League Showcase Website https://mouadbenyaya.github.io/FantasyPl/

Ce projet est un site vitrine statique dédié à la Fantasy Premier League, conçu pour présenter des stratégies, des analyses de joueurs et fournir des conseils aux utilisateurs. Le site est construit en utilisant uniquement HTML5 et CSS3, sans aucune dépendance JavaScript pour l'interactivité, garantissant ainsi performance et légèreté.

## Technologies Utilisées

- **HTML5** : Structure sémantique du contenu (header, main, section, article, footer).
- **CSS3** : Mise en forme et interactivité.
  - **Flexbox & Grid** : Pour la mise en page responsive.
  - **CSS Variables (:root)** : Pour la gestion centralisée des couleurs, des espacements et des effets.
  - **Media Queries** : Pour assurer la compatibilité sur mobile (<768px), tablette (<992px) et desktop (>1140px).
  - **CSS-Only Interactivity** : Le menu hamburger sur mobile et les effets de survol sont gérés entièrement en CSS (utilisation de l'input hack `checkbox` pour le menu).

## Structure du Projet

Le projet est structuré comme suit :

- **`index.html`** : Page d'accueil présentant le concept et les points clés.
- **`page1.html`** (Stratégies) : Détail des stratégies pour réussir en FPL.
- **`page2.html`** (Joueurs) : Focus sur les meilleurs joueurs et l'analyse.
- **`contact.html`** : Page de contact avec formulaire (visuel) et informations.
- **`mentions-legales.html`** : Page pour les mentions légales du site.
- **`style.css`** : Fichier de style unique contenant l'ensemble des règles CSS du site.

## Fonctionnalités Techniques

1.  **Architecture & Structure** :
    *   **Site Statique** : Architecture multi-pages simple et robuste, idéale pour un site vitrine performant.
    *   **Organisation des Fichiers** : Séparation claire entre contenu (`.html`), styles (`.css`), et médias (`/images`).
    *   **Propreté du Code** : CSS épuré, suppression des styles inutilisés pour maintenir la légèreté.

2.  **Design Responsive & Mobile-First** :
    *   **Fluidité** : Le site s'adapte à toutes les tailles d'écran (Mobile, Tablette, Desktop) grâce à des media queries précis (`768px`, `992px`, `1140px`).
    *   **Grilles et Flexbox** : Utilisation intensive de CSS Grid et Flexbox pour des mises en page réactives complexes sans frameworks lourds.

3.  **Interface Utilisateur (UI) Modernisée** :
    *   **En-tête (Header) Avancé** : Design révisé avec "Top Bar", navigation sur fond blanc pour la clarté, et logo image redimensionné pour l'impact visuel.
    *   **Pied de page (Footer) Cohérent** : Harmonisation du footer avec le thème clair du site.
    *   **Navigation "No-JS"** : Menu mobile innovant utilisant le "Checkbox Hack" CSS, garantissant une navigation fonctionnelle même sans JavaScript.

4.  **Performance & Optimisation** :
    *   **Zéro JS de Dépendance** : Pas de jQuery, pas de frameworks JS lourds. Le chargement est instantané.
    *   **CSS Optimisé** : Utilisation de variables CSS (`:root`) pour une maintenance aisée des couleurs et espacements.

5.  **Accessibilité & Standards** :
    *   **HTML Sémantique** : Balisage structuré (`header`, `nav`, `main`, `section`, `footer`) pour les lecteurs d'écran et le SEO.
    *   **Focus Visuel** : Styles dédiés pour la navigation au clavier (`:focus`).

##  Installation et Utilisation

Puisque le site est purement statique :

1.  Clonez ou téléchargez le projet.
2.  Assurez-vous que le dossier `images` contient bien le logo (`Logo.png`).
3.  Ouvrez `index.html` dans votre navigateur. C'est tout !
