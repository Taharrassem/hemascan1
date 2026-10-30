HEMASCAN AI - v0.1 (non compilée, non testée)

COMPILER L'APK (sans Android Studio)
1. Créez un dépôt GitHub (gratuit).
2. Envoyez-y tout le contenu du dossier HemaScan (y compris .github/workflows/build.yml).
   Sur téléphone : github.com > Add file > Create new file, tapez le chemin
   ".github/workflows/build.yml" et collez le contenu. Un ordinateur est plus simple pour le reste.
3. Onglet Actions > "Build APK" > attendre la fin (5-10 min).
4. Ouvrez l'exécution terminée > Artifacts > HemaScan_AI > téléchargez, dézippez, installez l'APK
   (autoriser les sources inconnues).
En cas d'erreur de build : copiez le message ici pour correction.

CE QUE FAIT LA V0.1
- Photo (appareil photo), import multiple, amélioration contraste/netteté (OpenCV)
- Détection et comptage géométriques (OpenCV), cellules suspectes marquées "Incertaine"
- Zoom/déplacement, annotations, filtre, classification MANUELLE par toucher
- Résultats en tableau (%), comparaison de photos, export CSV

PAS ENCORE FAIT
- Classification automatique (aucun modèle entraîné), Room, export PDF/image annotée,
  déduplication des champs qui se chevauchent, recadrage.
NON VALIDÉ : ne pas utiliser pour un diagnostic.
