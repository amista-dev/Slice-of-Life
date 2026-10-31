# Slice of Life : modpack

Fichiers lus par le lanceur **Slice of Life.exe** à chaque démarrage :

| Fichier | Rôle |
|---|---|
| `lanceur.json` | nom du pack, versions de Minecraft et NeoForge, version de Prism, mods réservés au serveur |
| `modpack.lock.csv` | liste figée des mods : version exacte, adresse Modrinth et empreinte SHA-512 de chaque fichier |
| `modpack-config.zip` | réglages du pack (`impose/` = toujours appliqués, `defaut/` = seulement à la 1re installation) |

## Mettre le pack à jour

1. Modifier la liste des mods, puis relancer `Get-Modpack.ps1 -Figer` sur le PC d'administration.
2. Remplacer ici `modpack.lock.csv` (et `modpack-config.zip` si les réglages ont changé).
3. Au prochain lancement, chaque joueur reçoit la nouvelle version tout seul.

Le lanceur ne télécharge les mods que depuis `cdn.modrinth.com`, et Prism que depuis le GitHub officiel de Prism Launcher.
