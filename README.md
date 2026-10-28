# Portfolio de Claude Vidot

Site portfolio personnel réalisé uniquement en **HTML et CSS** (sans JavaScript ni framework), avec un style sombre et moderne.

**Site en ligne :** <https://kurodo97420.github.io/my-portfolio/>

## Pages du site

| Page | Fichier | Contenu |
|---|---|---|
| Accueil | `index.html` | Nom, menu vers les autres pages, liens LinkedIn et GitHub |
| À propos | `about.html` | Présentation du parcours et des objectifs |
| Compétences et Expérience | `competences.html` | Domaines de compétences et expériences professionnelles |
| Mon CV | `cv.html` | Téléchargement du CV au format PDF |
| Contact | `contact.html` | Liens LinkedIn et GitHub, et formulaire de contact (en cours de développement) |

La navigation entre les pages se fait depuis le haut de chaque page, avec un bouton « Retour à l'accueil ».

## Structure du dépôt

```
my-portfolio/
├── index.html          page d'accueil
├── about.html
├── competences.html
├── cv.html
├── contact.html
├── css/
│   └── style.css       feuille de style commune à toutes les pages
├── images/             photos du site (portrait, ordinateur démonté, escalade)
├── documents/
│   └── CV_VIDOT_CLAUDE_V11.pdf
└── README.md
```

## Choix techniques

- **HTML5 sémantique** : `header`, `nav`, `main`, `section`, titres hiérarchisés (`h1`, `h2`, `h3`).
- **CSS avec Flexbox** : une seule feuille de style, classes nommées de façon explicite et commentées.
- **Responsive** : le site s'adapte aux écrans de PC, de tablette et de smartphone grâce aux media queries.
- **Accessibilité** : contrastes de couleurs vérifiés, contour visible lors de la navigation au clavier, `aria-label` et `aria-current` sur la navigation.
- **Référencement (SEO)** : un titre et une description uniques par page.

## Ressources et crédits

- **Photos** (portrait, ordinateur démonté, escalade) : prises par l'auteur, sans droits de tiers. Les métadonnées (position GPS, etc.) ont été retirées avant publication.
- **Police** : polices système du visiteur (`system-ui`), aucun fichier de police externe.
- **Icônes, thèmes, framework, bibliothèques** : aucun. Tout le code (HTML et CSS) a été écrit pour ce projet.
- **Textes** : rédigés par l'auteur.
- **CV** : `documents/CV_VIDOT_CLAUDE_V11.pdf`, document personnel de l'auteur.

## Publication

Le site est hébergé gratuitement avec **GitHub Pages** (branche `main`, dossier racine). Chaque modification envoyée sur `main` met automatiquement le site en ligne, sans action manuelle.

## Contact

- LinkedIn : <https://www.linkedin.com/in/claude-v-684a30134/>
- GitHub : <https://github.com/Kurodo97420>
