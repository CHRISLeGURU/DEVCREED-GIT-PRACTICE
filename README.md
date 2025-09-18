# Documentation - Profil Étudiant DEVCREED Academy

## Vue d'ensemble
Ce projet présente des profils d'étudiants de DEVCREED Academy avec un design moderne et responsive utilisant HTML5 et CSS3.

## Structure des fichiers

### index.html
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
1. modifiez toute la section entre `<!-- PROFIL ÉTUDIANT -->` et `<!-- FIN PROFIL ÉTUDIANT -->`
2. Changer l'ID (ex: `id="marie-martin-profile"`)
3. Personnaliser :
   - Nom de l'étudiant
   - URL de la photo ou image tiré du dossier public
   - Texte de présentation
   - Liste des compétences
