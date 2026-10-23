<p align="center">
  <img src="https://zupimages.net/up/26/43/ny8q.png" alt="Logo de MCS Studio" width="128">
</p>

<h1 align="center">MCS Studio</h1>

<p align="center">
  Convertissez les cartes <b>Battle</b> de Minecraft: PlayStation 3 Edition (<b>.mcs</b>)<br>
  en sauvegardes PS3 normales, modifiables en Créatif.
</p>

<p align="center">
  <a href="https://github.com/INF3CONxR7/MCS_Studio/releases/latest"><img src="https://img.shields.io/github/v/release/INF3CONxR7/MCS_Studio?label=t%C3%A9l%C3%A9charger&color=0070FA" alt="Télécharger"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?logo=windows&logoColor=white" alt="Windows 10 et 11">
  <a href="https://discord.gg/TbFYvqsh5z"><img src="https://img.shields.io/badge/Discord-rejoindre-5865F2?logo=discord&logoColor=white" alt="Serveur Discord"></a>
</p>

---

## Fonctionnalités

- **Carte Battle → monde normal** : le terrain, les constructions, les coffres, les entités et les coordonnées de la
  carte `.mcs` sont repris tels quels, dans un monde en mode Créatif où l’on construit et casse librement.
- **Sauvegarde PS3 complète** : `GAMEDATA`, `METADATA` et `PARAM.PFD` sont reconstruits et **re-signés**
  automatiquement à partir d’une sauvegarde créée sur votre console : aucun autre outil à lancer.
- **Apparition sûre** : le joueur apparaît dans l’arène, sur un sol solide, avec de la place autour.
- **Vérifiée avant d’être publiée** : la sauvegarde est relue entièrement (signature, CRC, chaque chunk comparé à la
  carte) ; en cas d’échec, rien n’est créé. Vos fichiers d’origine ne sont jamais modifiés.
- **Toutes les versions du jeu** : la sauvegarde peut aussi être produite pour les autres versions de Minecraft PS3
  (`BLES01976`, `NPEB01899`, `BLUS31426`, `NPUB31419`, `NPJB00539`), chacune re-signée. Sans carte `.MCS`, MCS Studio
  crée seulement ces versions à partir d’une sauvegarde existante (un monde déjà converti et modifié sur la console).
- **Mises à jour signées** et **activité Discord** facultative.

## Installation

1. Téléchargez `MCSStudio-win-x64.zip` depuis la [dernière version](https://github.com/INF3CONxR7/MCS_Studio/releases/latest).
2. Décompressez-le où vous voulez et lancez `MCS Studio.exe` (le runtime .NET est inclus).

## Utilisation

1. Sur la PS3, créez un monde en **Créatif**, taille **Classique**, et copiez-le sur une clé USB (utilitaire de données
   sauvegardées).
2. Dans MCS Studio, choisissez le fichier **.MCS** de la carte, puis le dossier de cette sauvegarde
   (`PS3\SAVEDATA\NPEB01899-…`) : « GAMEDATA détecté » s’affiche. Cochez au besoin les autres versions du jeu à
   produire.
3. **Convertir**, puis choisissez où créer le résultat.
4. Copiez le dossier `PS3` du résultat à la racine de la clé et importez la sauvegarde sur la PS3 : elle remplace le
   monde créé à l’étape 1.

## Crédits

Développé par **INF3C7ONxR7**. Formats PS3 établis avec l’aide des travaux publics d’[Apollo Save Tool](https://github.com/bucanero/apollo-ps3)
(bucanero) et de MCC Tool Chest ; implémentation propre à MCS Studio.

## Support

Une question, un bug : rejoignez le [serveur Discord](https://discord.gg/TbFYvqsh5z).
