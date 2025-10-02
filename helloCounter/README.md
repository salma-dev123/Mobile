Générer l’APK debug
📒 Glossaire minute
APK : fichier installable d’une app Android.
assembleDebug : action qui génère l’APK debug.
ADB : outil qui installe l’APK sur émulateur ou appareil.
✅ Objectif
Obtenir un APK debug et vérifier qu’il s’installe et s’ouvre sur un appareil ou émulateur.

1) Générer l’APK
   Dans Android Studio : Build → Build APK(s)
   L’APK se trouve dans : app/build/outputs/apk/debug/app-debug.apk
2) Installer l’APK
   Choisir un émulateur ou brancher un appareil.
   Lancer l’app avec Android Studio (Run ▶) ou avec ADB.
   📦 Livrables attendus
   Fichier app-debug.apk
   README avec les étapes pour le générer et l’installer