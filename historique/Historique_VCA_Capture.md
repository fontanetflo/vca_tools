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

## v2.4
- Renommage de la zone en « Type d’essai », avec conservation des 13 choix et du champ personnalisé.
- Ajout du résultat photo facultatif : OK, KO ou non renseigné.
- Ajout du numéro de pièce de 1 à 10 (pièce 1 par défaut).
- Ajout d'un commentaire facultatif associé à chaque photo pendant la session ; il est visible dans la galerie mais n'est pas exporté.
- Nommage des photos : `NOM_ESSAI_TYPE_[RESULTAT_]PXX_XX.ext`. Le résultat est omis s'il n'est pas renseigné.
- Les fonctions de capture vidéo, import, galerie, partage et accès SharePoint sont conservées.

**Date :** 16 novembre 2026  
**Déploiement :** version intégrée à la branche `main` pour GitHub Pages.
