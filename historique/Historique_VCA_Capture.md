# Historique VCA Capture

## v2.2
- Version originale conservée intégralement dans `historique/index_v2.2.html`.
- Fonctions présentes : capture photo, capture vidéo via MediaRecorder, import, galerie, partage iOS et lien SharePoint.

## v2.3
- Ajout des désignations photo prédéfinies : EI (par défaut), EF, KO, Test Rupture, Arrachement, Contrôle intermédiaire, Contrôle, Commentaire, Chocs 450g, Chocs 550g, Chute accidentelle, Reese et Vieillissement.
- Ajout d'un champ de désignation personnalisée.
- Nommage des photos : `NOM_ESSAI_DESIGNATION_01.ext`, avec normalisation des caractères et extension adaptée au type MIME détecté.
- Enregistrement vidéo avec `MediaRecorder.start(1000)` pour recevoir les segments toutes les secondes.
- Ajout d'une gestion explicite de l'événement d'erreur MediaRecorder.
- Les fonctions d'import, de galerie, de partage et d'accès SharePoint sont conservées.

**Date :** 16 novembre 2026  
**Déploiement :** version intégrée à la branche `main` pour GitHub Pages.  
**Vérification :** présence des modifications confirmée sur GitHub. Les essais fonctionnels sur iPhone et les enregistrements vidéo longs restent à effectuer.
