Here’s a clean **README.md** you can use for your assignment:

```markdown
# Génération et Installation d’un APK Debug

## ✅ Objectif
Obtenir un fichier **app-debug.apk**, l’installer sur un appareil (ou émulateur) et vérifier que l’application fonctionne correctement.  

---

## 1) Générer l’APK
1. Ouvrir le projet dans **Android Studio**.  
2. Dans la barre de menu :  
```

Build → Build APK(s)

````
3. Une fois la génération terminée, Android Studio affiche un message indiquant l’emplacement de l’APK.  
- Le fichier se trouve dans :  
  ```
  app/build/outputs/apk/debug/app-debug.apk
  ```

---

## 2) Installer l’APK

### Option A : Via Android Studio
1. Brancher un appareil Android (mode développeur + débogage USB activé) ou lancer un **émulateur**.  
2. Cliquer sur **Run ▶** dans Android Studio.  
3. L’application est automatiquement installée et lancée.  

### Option B : Via ADB (ligne de commande)
1. Vérifier que l’appareil est détecté :  
```bash
adb devices
````

2. Installer l’APK généré :

   ```bash
   adb install app/build/outputs/apk/debug/app-debug.apk
   ```
3. Lancer l’application depuis le téléphone/émulateur.

---
