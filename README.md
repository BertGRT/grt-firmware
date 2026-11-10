# GRT Dashboard V3 — firmwares

Logiciels compilés du tableau de bord moto GRT Dashboard V3 (Gourbi Racing Team), téléchargés par l'application
GRT Chrono pour mettre l'écran à jour par WiFi. Ce dépôt ne contient pas de code source.

- `manifest.json` : version, fichier, taille et empreinte SHA-256 du dernier logiciel de l'écran ;
- `ecran/` : le logiciel de l'écran (Waveshare ESP32-S3-Touch-LCD-4.3B). Il ne s'installe que sur un écran qui porte
  déjà le logiciel GRT (à partir de la version 3.2.8), par l'application ou par la page `http://192.168.4.1/update`.

Fichiers fabriqués par `tools/release/publier_firmware.py` du projet.
