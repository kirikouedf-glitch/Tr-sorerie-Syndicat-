# Trésorerie Syndicat PWA V2 complète

Fonctions :
1. plusieurs comptes bancaires et caisse ;
2. import CSV / Excel ;
3. rapprochement bancaire ;
4. photo / classement de justificatifs ;
5. ventilation détaillée des recettes et dépenses ;
6. budget prévisionnel / réalisé ;
7. tableaux de bord mensuels et par rubrique ;
8. recherche et filtres ;
9. numérotation automatique des pièces ;
10. clôture d'exercice avec bilan, compte de résultat et annexes ;
11. dossier annuel imprimable en PDF ;
12. sauvegarde complète et restauration.

Mise à jour GitHub Pages :
remplacer `index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg` dans le dépôt, puis Commit changes.

Migration :
la V2 tente de reprendre automatiquement les écritures de la V1 stockées localement dans le navigateur.

Notes :
- les justificatifs sont stockés localement dans le navigateur ; limite de 4 Mo par fichier dans cette version ;
- l'import CSV fonctionne hors connexion ;
- l'import Excel nécessite une connexion au chargement de la bibliothèque Excel ;
- le PDF est obtenu via le bouton Imprimer / Enregistrer en PDF du dossier annuel.
