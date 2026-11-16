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

## v2.5
- Suppression du champ de désignation personnalisée : le type d’essai est choisi dans la liste prédéfinie.
- Conservation du commentaire facultatif ; s’il est renseigné, il est normalisé et ajouté à la fin du nom de chaque photo capturée.
- Le champ commentaire est vidé après la capture pour éviter de le réutiliser involontairement.
- Suppression de l’affichage temporaire du commentaire dans la galerie : le commentaire figure désormais directement dans le nom du fichier photo.
- Conservation du résultat facultatif (OK/KO/vide), du numéro de pièce et des fonctions vidéo, import, galerie, partage et accès SharePoint.

**Date :** 16 novembre 2026  
**Déploiement :** version intégrée à la branche `main` pour GitHub Pages.

## v2.6
- Optimisation de l'interface caméra pour iPhone : ajout d'un statut toujours lisible (« PRÊT À FILMER » / « ENREGISTREMENT EN COURS ») avec annonce accessible.
- Agrandissement et mise en évidence du compteur de durée, avec chiffres à largeur fixe pour faciliter la lecture pendant la capture.
- Synchronisation de l'indicateur visuel et du compteur au démarrage, à l'arrêt et en cas d'erreur d'enregistrement.
- Conservation des fonctions et réglages de la v2.5, notamment les choix de type d'essai, résultat, pièce, commentaire dans le nom photo, import, galerie, partage et accès SharePoint.

**Date :** 16 novembre 2026  
**Déploiement :** branche `main`, publication GitHub Pages.  
**Vérifications :** syntaxe JavaScript contrôlée ; test réel de la caméra et de l'enregistrement à effectuer sur iPhone.
