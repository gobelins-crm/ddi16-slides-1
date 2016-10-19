class: center, middle, inverse
# Initiation Mobile Java/Android
## DDI16

---
class: center, middle, inverse
# Présentez-vous !

---
.left-column[
## Louis Beltramo
## louis@beltramo.me
### - SRC Montbéliard
### - Gobelins CRM Annecy
### - Freelance
### - Développeur mobile, web & interactif
]

.right-column[
.pull-left[

### Du mobile
- JS / Cordova
- Java / Android
- Haxe / OpenFL / Kha
- ~~AS3 / Air~~

### Du web
- JS / Backbone, Vue, Angular
- Node / Hapi
- Ruby / Rails
- PHP / Wordpress, Drupal
]

### De l'interactif
- Haxe / OpenFL / Kha
- Mapping
- Arduino
- Kinect

### Dev/Ops
- Admin Linux / Ansible
- Proxmox, LXC
- Docker, Dokku, Kubernetes
- ...

]

---
class: center, middle, inverse
# Modalités

---
.left-column[
## Modalités
### - Rendu
]

.right-column[
# .center[Vendredi 4 novembre 2016 à 23h59]
]
---

.left-column[
## Modalités
### - Rendu
### - Rendu intermédiaire
]

.right-column[
# .center[Vendredi 21 octobre 2016 à 16h30]
]
---

.left-column[
## Modalités
### - Rendu
### - Livrables
]

.right-column[
### Claroline
- Zip des sources
- Apk de l'appli
- Vidéos / captures d'écrans
- README.md / Document d'info sur votre projet
  - Lien vers le dépôt Git

### Dépôt Git
- Projet complet versionné
- Historique des commits reflétant tout votre travail
- README.md _le document d'info complet_
]
---

.left-column[
## Modalités
### - Rendu
### - Livrables
### - Barême
]

.right-column[
## Ce qui rentre dans les critères d’évaluation :
- Projet complet et fonctionnel : __5 points__
- Qualité du travail :            __5 points__
- Maîtrise des concepts Java :    __3 points__
- Maîtrise des concepts Android : __3 points__
- Ergonomie :                     __2 points__
- Qualité du code source :        __1 point__
- Gestion du projet :             __1 point__

## Ce qui ne rentre pas dans les critères d’évaluation :
- le graphisme
- les bugs mineurs
]
---

.left-column[
## Modalités
### - Rendu
### - Planning
]

.right-column[
# mercredi 19 octobre
## après-midi
- Un peu de théorie
- Prise en main d'Android Studio
- Devices et émulateurs
- Hello World
]
---

.left-column[
## Modalités
### - Rendu
### - Planning
]

.right-column[
# jeudi 20 octobre

## matin
- Architecture et composants Android
  - Manifest
  - Activity et explicit Intents
  - Layouts
  - Fragments
  - Ressources
  - Adapter et RecyclerView

## après-midi
- Google Play Services
- Géolocation
]

---
.left-column[
## Modalités
### - Rendu
### - Planning
]

.right-column[
# vendredi 21 octobre
## matin
- Mapbox

## après-midi
- Projet
]

---
.left-column[
## Modalités
### - Rendu
### - Planning
]

.right-column[
# ~~lundi 31 octobre~~
]

---
class: center, middle, inverse
# Android

---
.left-column[
## Android
### - Android, Inc
]

.right-column[
## Fondé en Octobre 2003
- concurrencer Symbian (!) et Windows Mobile (!)
- le but : "smarter mobile devices that are more aware of its owner's location and preferences"
<br />
<br />
.pull-left[![img](./images/juggle.gif)]
]

.footnote[Pour info en 2002 on vendait encore des Nokia 3310]

---
.left-column[
## Android
### - Android, Inc
### - Google
]

.right-column[
## Racheté par Google en Août 2005
- Travail sur une platforme mobile basée sur le noyau Linux
- Protoype proche d'un blackberry
<br/>
<br/>
.pull-left[![tiny_img](./images/sooner.jpg)]
]

---
.left-column[
## Android
### - Android, Inc
### - Google
### - Touchscreen
]

.right-column[
## iPhone sort en 2007
- Pas de clavier physique !
- Google se dépêche d'ajouter un touchscreen mais garde le clavier physique.

## HTC Dream (G1) sort en 2008
<br/>
<br/>
.pull-left[![tiny_img](https://upload.wikimedia.org/wikipedia/commons/b/be/HTC_Dream_Orange_FR.jpeg)]
]

---
.left-column[
## Android
### - Android, Inc
### - Google
### - Touchscreen
### - Nexus
]

.right-column[
## Nexus One en 2010 / Android Eclair 2.1
.pull-left[![tiny_img](https://upload.wikimedia.org/wikipedia/commons/thumb/2/22/Nexus_One.png/300px-Nexus_One.png)]
]

---
.left-column[
## Android
### - Android, Inc
### - Google
### - Touchscreen
### - Nexus
### - Versions
]

.right-column[
## D'android Alpha à Android Marshmallow
.center[![tiny_img](https://upload.wikimedia.org/wikipedia/commons/e/ee/Android_historical_version_distribution_-_vector.svg)]
https://en.wikipedia.org/wiki/Android_version_history
]

---
.left-column[
## Android
### - Android, Inc
### - Google
### - Touchscreen
### - Nexus
### - Versions
### - AOSP
]

.right-column[
# Android Open Source Project
- Couche propriétaire Google
- De nombreuses applis AOSP sont abandonnées

## Plusieurs Android
- Cyanogen
- Replicant

## Des morceaux d'Android ailleurs
- Firefox OS
- Jolla Sailfish OS
]

---
class: center, middle, inverse
# Android 5


---
.left-column[
## Android 5
]
<br/>
<br/>
<br/>
.center[
![img](./images/juggle_lollipop.gif)
]

---
.left-column[
## Android 5
### - Material Design
]

.center[
<video autoplay="true" loop="true">
    <source src="https://developer.android.com/design/material/videos/ContactsAnim.mp4" />
</video>
]

.footnote[[->Intro material design](http://www.google.com/design/spec/material-design/introduction.html)]

---
.left-column[
## Android 5
### - Material Design
### - Nouveautés
]
.right-column[
.pull-right[![tiny_img](https://developer.android.com/images/android-5.0/notifications/hun-example.png)]
## Notifications
## Project Volta
## ART
- Remplace Dalvik
- AOT au lieu de JIT

]

???
__ART__ Ahead-of-time (AOT) compilation

---
.left-column[
## Android 5
### - Material Design
### - Nouveautés
### - Android Wear
]

.right-column[
.pull-right[![Right-aligned image](https://developer.android.com/wear/images/notifications.png)]
## Mobile & Wear
- Applis "déportés"
]

---
.left-column[
## Android 5
### - Material Design
### - Nouveautés
### - Android Wear
### - Android TV
]

.pull-left[![full_img](https://developer.android.com/tv/images/atv-framed.png)]

---
.left-column[
## Android 5
### - Material Design
### - Nouveautés
### - Android Wear
### - Android TV
### - Android Auto
]

.pull-left[![full_img](http://www.android.com/new/images/auto/slide-1.jpg)]

---
.left-column[
## Android 5
### - Material Design
### - Nouveautés
### - Android Wear
### - Android TV
### - Android Auto
### - OK Google
]

.pull-left[![full_img](http://www.android.com/new/images/auto/slide-4.jpg)]

---
class: center, middle, inverse
# Android 6

---
.left-column[
## Android M
### - Permissions
]
## Runtime Permissions
![img](images/request_permission_dialog.png)
---

## Runtime Permissions
```java
if (ContextCompat.checkSelfPermission(this, Manifest.permission.READ_CONTACTS)
        != PackageManager.PERMISSION_GRANTED) {
    if (ActivityCompat.shouldShowRequestPermissionRationale(thisActivity,
            Manifest.permission.READ_CONTACTS)) {
        // L'utilisateur a déjà refusé la permission
        // Essayer d'être convaincant
    } else {
        ActivityCompat.requestPermissions(this,
                new String[]{Manifest.permission.READ_CONTACTS},
                MY_PERMISSIONS_REQUEST_READ_CONTACTS);

    }
}
```
---

## Runtime Permissions
```java
@Override
public void onRequestPermissionsResult(int requestCode,
        String permissions[], int[] grantResults) {
    switch (requestCode) {
        case MY_PERMISSIONS_REQUEST_READ_CONTACTS: {
            if (grantResults.length > 0
                && grantResults[0] == PackageManager.PERMISSION_GRANTED) {
                // Permission accordée
            } else {
                // Permission refusée
            }
            return;
        }
    }
}
```
---

.left-column[
## Android M
### - Permissions
### - Power saving
]
.right-column[
## Doze mode
![tiny_img](images/doze.png)
## App Standby
- Réseau une fois par jour
- Utilisation de GCM (connexion partagée)
]
---

.left-column[
## Android M
### - Permissions
### - Power saving
### - Text selection
]
.right-column[
![img](images/text-selection.gif)
]
---

.left-column[
## Android M
### - Permissions
### - Power Saving
### - Text Selection
### - Fingerprint
]
.right-column[
![img](images/fingerprint-screen.png)
]
---

.left-column[
## Android M
### - Permissions
### - Power Saving
### - Text Selection
### - Fingerprint
### - Voice Actions
]
.right-column[
![tiny_img](images/tunein-interaction.gif)
]
---

.left-column[
## Android M
### - Permissions
### - Power Saving
### - Text Selection
### - Fingerprint
### - Voice Actions
### - Divers
]
.right-column[
## Auto Backup
## App links
## Toujours plus de Play Services
]
---

class: center, middle, inverse
# Android Nougat

[Android 7.0 for Developers](https://developer.android.com/about/versions/nougat/android-7.0.html)
---

.left-column[
## Android N
### - Multi-Window
]

.right-column[
## Multi-Window support
![img](https://developer.android.com/images/android-7.0/mw-splitscreen.png)

```
android:resizeableActivity=["true" | "false"]
```
```java
startDragAndDrop(ClipData, DragShadowBuilder,
    Object, DRAG_FLAG_GLOBAL)
```
]
---

.left-column[
## Android N
### - Multi-Window
### - Notifications
]
.right-column[
## Inline reply, grouping,
![img](https://developer.android.com/images/android-7.0/inline-type-reply.png)
## Grouping
![img](https://developer.android.com/images/android-7.0/inline-type-reply.png)

]
---

.left-column[
## Android N
### - Multi-Window
### - Notifications
### - Power saving
]
.right-column[
## Doze mode updated
![tiny_img](https://developer.android.com/images/android-7.0/doze-diagram-1.png)
![tiny_img](https://developer.android.com/images/android-7.0/doze-diagram-2.png)
]
---

.left-column[
## Android M
### - Multi-Window
### - Notifications
### - Power saving
### - Data saving
]
.right-column[
```java
ConnectivityManager connMgr = (ConnectivityManager)
        getSystemService(Context.CONNECTIVITY_SERVICE);
if (connMgr.isActiveNetworkMetered()) {
  // Checks user’s Data Saver settings.
  switch (connMgr.getRestrictBackgroundStatus()) {
    case RESTRICT_BACKGROUND_STATUS_ENABLED:
    // Background data usage is blocked for this app.

    case RESTRICT_BACKGROUND_STATUS_WHITELISTED:
    // The app is whitelisted.

    case RESTRICT_BACKGROUND_STATUS_DISABLED:
    // Data Saver is disabled.
  }
} else {
  // The device is not on a metered network.
}
```
]
---

.left-column[
## Android M
### - Multi-Window
### - Notifications
### - Power saving
### - Data saving
### - Direct Boot
]
.right-column[
```java
<receiver
  android:directBootAware="true" >
  ...
  <intent-filter>
    <action android:name="android.intent.action.ACTION_LOCKED_BOOT_COMPLETED" />
  </intent-filter>
</receiver>
```
]
---

.left-column[
## Android Studio 2.2
### - OpenJDK 8
### - Layout Editor
### - Improved emulator
### - Instant run that works
]
.right-column[
![img](https://developer.android.com/studio/images/hero_image_studio_2-2.png)
]

---

class: center, middle, inverse
# Android Studio

---
.left-column[
## Android Studio
### - ADT ?
]

.right-column[
## ADT
- Eclipse
- Ant
- Abandonné par Google

## Android Studio
- IntelliJ Idea
- Gradle
- IDE officiel pour Android
]
.right[![Right-aligned image](https://1.bp.blogspot.com/-u5dfSsMOMC0/UZO_5DC_W9I/AAAAAAAACM8/YCMn15HPzpE/s1600/Studio_table.png)]

---
.left-column[
## Android Studio
### - ADT ?
### - Gradle
]

.right-column[
.pull-right[![Right-aligned image](images/android_build_process.png)]
## Automate everything
- Gestion des assets
- Gestion des librairies
- Compilation
- Build de l'APK
- Signature
- ...

## Groovy
- Langage dynamique pour la JVM

```groovy
def commitHg(message) {
    def stdout = new ByteArrayOutputStream()
    exec {
        commandLine "hg", "commit", "-A", "-m", message
        standardOutput = stdout
    }
    println stdout.toString()
}

```

.footnote[Ex: Grunt, Gulp, Robo, Rake, Leinigen...]
]

???


---
.left-column[
## Android Studio
### - ADT ?
### - Gradle
### - Maven
]

.right-column[
## Dépôt centralisé

```groovy
import java.util.regex.Pattern

apply plugin: 'com.android.application'

repositories {
    mavenCentral()
}
```

## Gestionnaire de dépendances
```groovy
    compile 'com.doomonafireball.betterpickers:library:1.5.+'
    compile 'com.android.support:support-v4:20.0.+'
    compile 'com.google.android.gms:play-services:4.4.+'
```
]

???

- Gestionnaire de dépendance (entre autres)
- PHP : Composer
- JS : NPM / bower
- Ruby : Gem / bundler

---
class: center, middle, inverse
# Git

---
.left-column[
## Git
### - Github.com
### - Bitbucket.org
### - Gitlab.com
]

.right-column[
## Pour visualiser tout ça
- https://windows.github.com/
- https://mac.github.com/
- http://www.sourcetreeapp.com/
- https://github.com/FredrikNoren/ungit
- Gitg sous Linux
]
---

class: center, middle, inverse
# http://guides.codepath.com/android
---

class: center, middle, inverse
# Direction Android Studio !
