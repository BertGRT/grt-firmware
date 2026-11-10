# GRT Dashboard V3 — firmwares

Logiciels compilés du tableau de bord moto GRT Dashboard V3 (Gourbi Racing Team), téléchargés par l'application
GRT Chrono pour mettre l'écran et la carte acquisition à jour par WiFi. Ce dépôt ne contient pas de code source.

- `manifest.json` : version, fichier, taille et empreinte SHA-256 de chaque logiciel ;
- `ecran/` : le logiciel de l'écran (Waveshare ESP32-S3-Touch-LCD-4.3B). Il ne s'installe que sur un écran qui porte
  déjà le logiciel GRT (à partir de la version 3.2.8), par l'application ou par la page `http://192.168.4.1/update` ;
- `acquisition/` : le logiciel de la carte acquisition (ESP32-C3), un fichier par variante de carte (`acq` : modules,
  `acq_pcb` : circuit imprimé, `acq_aio` : tout en un). L'application l'envoie à l'écran, qui le transmet à la carte.

Fichiers fabriqués par `tools/release/publier_firmware.py` du projet.
