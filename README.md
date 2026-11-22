# CODAGE — Apprendre à programmer

CODAGE est une application Flutter Android pour apprendre la programmation en français, à travers des cours courts, des exemples de code, des quiz et un suivi de progression.

## Parcours inclus
- HTML : balises, structure, liens et images
- CSS : styles, classes, Flexbox
- JavaScript : variables, conditions, fonctions
- Python : affichage, types et boucles
- Dart & Flutter : bases du langage, fonctions, widgets

## Fonctionnalités
- Leçons avec explications et exemples de code
- Quiz à choix multiple
- Leçons marquées comme terminées
- XP (25 points par leçon) et niveaux
- Progression enregistrée localement sur l'appareil
- Interface sombre avec navigation Accueil / Cours / Progrès

## Compiler l'APK
GitHub Actions compile automatiquement l'APK sur chaque push à `main` et peut être lancé manuellement depuis l'onglet Actions.

1. Ouvrir le workflow **Flutter Android APK**
2. Cliquer **Run workflow**
3. Une fois terminé, récupérer l'artefact `CODAGE-APK`

Le fichier APK est publié comme artifact et conservé 14 jours.

## Lancer en local
Installer Flutter, puis exécuter :

```bash
flutter pub get
flutter run
```

## À venir
Davantage de leçons, d'autres langages, projets guidés, exercices de pratique et un vrai éditeur de code intégré.