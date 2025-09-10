# Documentation - Profil Étudiant DEVCREED Academy

## Vue d'ensemble
Ce projet présente des profils d'étudiants de DEVCREED Academy avec un design moderne et responsive utilisant HTML5 et CSS3.

## Structure des fichiers

### 📄 index.html
Fichier HTML principal contenant la structure de la page.

#### Structure générale
```
<!DOCTYPE html>
<html lang="fr">
├── <head> - Métadonnées et liens vers les ressources
├── <body>
    └── <div class="container">
        ├── <header class="header"> - Titre et sous-titre
        ├── <main class="main-content"> - Contenu principal
        │   └── <section class="student-profile"> - Profil étudiant réutilisable
        └── <footer class="footer"> - Pied de page
```

#### Section profil étudiant (réutilisable)
La section `student-profile` contient :
- **Section profil** : Photo et informations de base
- **Section présentation** : Description personnelle
- **Container compétences** : Compétences actuelles et futures

#### Comment ajouter un nouvel étudiant
1. Copier toute la section entre `<!-- PROFIL ÉTUDIANT -->` et `<!-- FIN PROFIL ÉTUDIANT -->`
2. Changer l'ID (ex: `id="marie-martin-profile"`)
3. Personnaliser :
   - Nom de l'étudiant
   - URL de la photo
   - Texte de présentation
   - Liste des compétences

### 🎨 styles.css
Fichier CSS principal avec un design moderne et sombre.

#### Variables CSS (`:root`)
```css
--primary-dark: #1a1d29     /* Couleur de fond principale */
--secondary-dark: #2a2d3a   /* Couleur de fond secondaire */
--accent-pink: #ff3b8a      /* Accent rose */
--accent-purple: #9d4edd    /* Accent violet */
--accent-blue: #3b82f6      /* Accent bleu */
--text-white: #ffffff       /* Texte principal */
--text-gray: #b8bcc8        /* Texte secondaire */
```

#### Sections principales

**Header**
- Titre avec dégradé coloré
- Ligne décorative avec effet de lueur
- Sous-titre stylisé

**Profil étudiant**
- Carte avec bordure dégradée
- Photo circulaire avec effet de bordure
- Nom avec effet de texte dégradé
- Sections avec barres colorées en haut

**Compétences**
- Deux colonnes : actuelles et futures
- Listes numérotées/à puces stylisées
- Effets de survol avec translation
- Compteurs CSS pour la numérotation

#### Classes importantes
- `.container` : Conteneur principal centré
- `.student-profile` : Section complète d'un étudiant
- `.profile-section` : Informations de base + photo
- `.skills-container` : Grille des compétences
- `.current-skills` / `.future-skills` : Sections de compétences


### 🚀 Déploiement
Le projet est prêt à être déployé sur n'importe quel service, nous utiliserons netlify ou vercel.