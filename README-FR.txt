SALIHA — PROJET ANDROID
=======================

Ce dossier contient le projet source Android de SALIHA : un jeu de blocs façon puzzle/Tetris, avec des cases illustrées de pastèques, un score et des niveaux.

IMPORTANT
---------
Ceci est le projet Android prêt à être ouvert dans Android Studio. Il ne s'agit pas encore d'un APK signé ni d'une publication Play Store.

COMMENT FABRIQUER L'APK
-----------------------
1. Sur un ordinateur, installe Android Studio depuis le site officiel : https://developer.android.com/studio
2. Décompresse SALIHA-Android.zip.
3. Dans Android Studio, choisis « Open » puis sélectionne le dossier SALIHA-Android.
4. Accepte la synchronisation Gradle et laisse Android Studio télécharger les composants Android nécessaires.
5. Pour tester : branche un téléphone Android avec le débogage USB activé, puis clique sur Run (triangle vert).
6. Pour créer un APK : menu Build > Build Bundle(s) / APK(s) > Build APK(s).
7. Pour Google Play, il faudra ensuite générer un Android App Bundle signé via Build > Generate Signed Bundle / APK > Android App Bundle.

IDENTIFIANT TECHNIQUE
--------------------
Nom affiché : SALIHA
Application ID : fr.saliha.jeu
Version : 1.0

Le projet utilise une WebView locale : le jeu fonctionne sans site web externe et ne demande aucune permission réseau.
