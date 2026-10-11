# VTC Tracker — paquet d'installation

Ce dépôt public ne contient **que le paquet d'installation** du VTC Tracker.
Aucune source n'est publiée ici.

## Télécharger

La dernière version est dans l'onglet **Releases** :

https://github.com/DamienGamer601/vtc-tracker/releases/latest

## Ce que contient le paquet

- `VTC-Tracker.exe` — l'enregistreur (aucune installation de Node n'est nécessaire) ;
- `vtc_scs_telemetry.dll` — le plugin de télémétrie pour ETS2 et ATS ;
- `overlay/` — l'overlay de télémétrie (PowerShell 7) ;
- `installer.cmd` / `installer.ps1` — l'installation guidée ;
- `LISEZ-MOI.txt` — la notice complète, et `EMPREINTES-SHA256.txt` les empreintes.

## Installer

1. Téléchargez le ZIP de la dernière version et décompressez-le.
2. Double-cliquez sur `installer.cmd` (il demandera les droits administrateur).
3. Ouvrez https://hub.drivershub.fr pour obtenir votre code d'appairage à 6 chiffres.

Windows affichera un avertissement SmartScreen : l'exécutable n'est pas signé.
Cliquez sur « Informations complémentaires », puis « Exécuter quand même », et
comparez l'empreinte SHA-256 publiée avec chaque version.

VTC DriversHub — https://hub.drivershub.fr