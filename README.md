# Slice of Life

Modpack Minecraft **1.21.1** (NeoForge) au thème futuriste : Mekanism, Create, Applied Energistics 2 et bien d'autres.

## Installer

1. Télécharge **Slice.of.Life.exe** dans la [dernière version](https://github.com/amista-dev/Slice-of-Life/releases/latest) (rubrique *Assets*).
2. Lance-le. Si Windows affiche « Windows a protégé votre ordinateur », clique sur **Informations complémentaires** puis **Exécuter quand même** (le lanceur n'est pas signé, c'est normal).
3. La première fois, choisis le dossier d'installation et la mémoire à donner au jeu, puis connecte-toi avec ton compte Microsoft dans la fenêtre de Prism Launcher.

Ensuite, lance simplement l'exe à chaque fois que tu veux jouer : il met le pack à jour tout seul.
Pour changer la mémoire ou le dossier plus tard : **R + Entrée** au démarrage du lanceur.

## Ce que fait le lanceur

- installe [Prism Launcher](https://prismlauncher.org) (version portable, téléchargée depuis son GitHub officiel) ;
- télécharge les mods depuis [Modrinth](https://modrinth.com) et vérifie chaque fichier ;
- active les packs de ressources du modpack (tu peux les retirer dans le jeu) et présélectionne le shader Bliss, désactivé par défaut ;
- démarre Minecraft : tu joues en solo ou tu rejoins le serveur de ton choix.

## Désinstaller

Supprime le dossier `%APPDATA%\.server-sliceoflife`, et le dossier `.server-sliceoflife` que tu as choisi à l'installation s'il est ailleurs.

## Fichiers de ce dépôt

`lanceur.json`, `modpack.lock.csv` et `modpack-config.zip` sont lus automatiquement par le lanceur : la liste exacte des mods (avec leur empreinte SHA-512) et les réglages du pack.
