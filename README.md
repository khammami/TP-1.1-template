# Travail à faire (Compte Rendu)

> [!WARNING]  
> Veuillez suivre les instructions détaillées du codelab **[Comment soumettre votre compte rendu](https://codelabs-enetcom.khammami.tn/codelabs/soumettre-compte-rendu/)** pour soumettre votre compte rendu.

## Créer et exécuter une application

* Créer un nouveau projet Android à partir du modèle vide.

* Ajouter des instructions de journalisation pour différents niveaux dans `onCreate()` dans l'activité principale.

* Créer un émulateur pour un appareil, en ciblant la version d'Android de votre choix, puis exécuter l'application.

* Utiliser le filtrage dans Logcat pour rechercher vos instructions de journal et ajuster les niveaux pour afficher uniquement les instructions de débogage ou d'erreurs.

## Répondre à ces questions

### **Question 1**

**Q1.** Quel est le nom du fichier de mise en page de l'activité principale?

📋 **A1.** Choisissez-en un:

* [ ] **(a)** `MainActivity.java`
* [ ] **(b)** `AndroidManifest.xml`
* [ ] **(c)** `activity_main.xml`
* [ ] **(d)** `build.gradle`

### **Question 2**

**Q2.** Quel est le nom de la ressource chaîne qui spécifie le nom de l'application?

📋 **A2.** Choisissez-en un:

* [ ] **(a)** `app_name`
* [ ] **(b)** `xmlns:app`
* [ ] **(c)** `android:name`
* [ ] **(d)** `applicationId`

### **Question 3**

**Q3.** Quel outil utilisez-vous pour créer un nouvel émulateur?

📋 **A3.** Choisissez-en un:

* [ ] **(a)** Android Device Monitor
* [ ] **(b)** AVD Manager
* [ ] **(c)** SDK Manager
* [ ] **(d)** Theme Editor

### **Question 4**

**Q4.** Supposons que votre application inclut cette instruction de journalisation:

```java
Log.i("MainActivity", "MainActivity layout is complete");
```

Vous voyez la mention `"MainActivity layout is complete"` dans le volet **Logcat** si le menu de niveau `Log` est réglé sur lequel des éléments suivants?

📋 **A4.** Choisissez-en un:

* [ ] **(a)** Verbose
* [ ] **(b)** Debug
* [ ] **(c)** Info
* [ ] **(d)** Warn
* [ ] **(e)** Error
* [ ] **(f)** Assert

## Notes

> [!NOTE]  
>
> Vérifiez que l'application dispose des éléments suivants:
>
> * Une activité qui affiche `"Hello World"` à l'écran.
> * Des instructions de `Log` dans `onCreate()` dans l'activité principale.
> * Le niveau de `Log` dans le volet Logcat n'affiche que les instructions de débogage ou d'erreurs.
