# Dunveil Launcher

Le launcher Windows de l’académie de magie Dunveil, pour l’équipe de construction et de développement.

## Installation

[Télécharger la dernière version](https://github.com/Hugo-Bertin/dunveil-distribution/releases/latest), puis ouvrir le fichier **Dunveil-Launcher-Setup**. Le launcher installe Java 21, Minecraft 1.21.1, Fabric, les mods et le resource pack nécessaires. Les mises à jour suivantes sont proposées automatiquement.

Un compte possédant **Minecraft Java Edition** est nécessaire. La connexion passe par la page officielle Microsoft. L’application Microsoft dédiée à Dunveil a reçu son autorisation d’accès aux API Minecraft le 30 septembre 2026.

## Profils

- **BUILD** : `build.dunveil.fr`, avec les outils de construction de l’équipe.
- **DEV** : `dev.dunveil.fr:25566`, avec les mods Dunveil, leurs dépendances et le resource pack. L’accès est actuellement réservé au propriétaire ; le serveur applique aussi sa whitelist.

Les instances et les mises à jour des deux profils sont séparées. Les mods tiers sont téléchargés depuis leurs sources officielles Modrinth lorsque disponibles, puis vérifiés par empreinte SHA-256.

## Skins Dunveil

Le launcher permet d’appliquer un skin PNG 64×64 ou 128×128, avec le modèle Steve ou Alex. Ces skins sont propres à Dunveil : ils ne remplacent pas le skin officiel du compte sur les autres serveurs.

Les sessions du launcher sont chiffrées localement avec le stockage sécurisé du système. Le service HTTPS de skins Dunveil reçoit temporairement le jeton Minecraft pour vérifier l’identité du joueur auprès de Mojang ; il ne conserve pas ce jeton. Il ne reçoit ni mot de passe Microsoft ni jeton de renouvellement Microsoft. Les textures de skins appliquées sont publiques pour permettre leur affichage aux autres joueurs.

Les sources sont conservées dans un dépôt privé. Ce dépôt public contient uniquement les fichiers distribuables et les informations de téléchargement. Les versions macOS et Linux sont prévues ultérieurement.

Projet communautaire indépendant, non officiel et non affilié à Mojang ou Microsoft. L’autorisation d’accès aux API ne constitue pas une approbation du projet.
