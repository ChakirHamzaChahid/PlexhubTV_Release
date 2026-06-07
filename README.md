# PlexHubTV

Client **Android TV** qui unifie tes bibliothèques **Plex, Jellyfin et IPTV/Xtream** en une seule bibliothèque (sans doublons quand le même film/série existe sur plusieurs serveurs), avec un lecteur performant **ExoPlayer** + repli **MPV** pour le Dolby Vision / HDR.

> ⚠️ Ce dépôt sert **uniquement à distribuer l'APK**.).

## 📥 Installation

1. Ouvre l'onglet **[Releases](../../releases)** et télécharge l'APK adapté à ton appareil :

   | Appareil | APK à télécharger |
   |---|---|
   | **Mi Box S** et boîtiers/TV **ARM 32 bits** | `app-armeabi-v7a-release.apk` |
   | TV/boîtiers **ARM 64 bits** récents | `app-arm64-v8a-release.apk` |

   En cas de doute, `armeabi-v7a` fonctionne sur les deux (un peu moins optimisé sur 64 bits).

2. Sur la TV : **Paramètres → Sécurité et restrictions → Sources inconnues**, et autorise l'app qui va installer (Downloader, explorateur de fichiers…).

3. Installe l'APK :
   - **Via un explorateur TV** (Downloader, *Send Files to TV*, X-plore…) : ouvre le fichier téléchargé.
   - **Via ADB** (depuis un PC) :
     ```bash
     adb install -r app-armeabi-v7a-release.apk
     ```

## 🔄 Mises à jour

L'application intègre les **mises à jour OTA**. Sinon, réinstalle le dernier APK par‑dessus l'actuel : même signature → installation sans perte de données.

## 🆕 Version actuelle

**1.0.17** — voir les notes détaillées dans la dernière [Release](../../releases/latest).

## 📄 Licence

© 2026 ChakirHamzaChahid — **Tous droits réservés. Propriétaire et confidentiel.**

Distribution **binaire uniquement**. Toute copie, redistribution, décompilation ou réutilisation du code (même partielle) est interdite sans autorisation écrite préalable.
