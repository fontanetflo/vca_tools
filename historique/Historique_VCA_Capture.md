# Historique VCA Capture

## v2.2
- Version de référence récupérée depuis `main/index.html`.
- Fonctions existantes : capture photo, capture vidéo via MediaRecorder, import, galerie, partage iOS et lien SharePoint.

## v2.3 (préparation)
- Ajout d'une désignation photo prédéfinie, avec **EI** sélectionné par défaut.
- Ajout d'un champ de désignation personnalisée qui remplace le choix prédéfini pour les captures suivantes.
- Nommage des photos : `NOM_ESSAI_DESIGNATION_01.ext`.
- Extension du fichier photo adaptée au type MIME courant (JPG, PNG, WebP, HEIC/HEIF).
- Enregistrement vidéo avec `MediaRecorder.start(1000)` pour recevoir les segments toutes les secondes, plus gestion explicite de l'événement d'erreur.
- Aucun changement volontaire aux fonctions d'import, de galerie, de partage et d'accès SharePoint.

**Date de préparation :** 16 novembre 2026  
**Statut :** branche de prévisualisation, non publiée sur `main`. Tests réels iPhone à effectuer avant fusion.
