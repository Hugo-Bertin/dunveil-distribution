# Dunveil Launcher

Dunveil is an original Minecraft Java Edition magic academy server project, built around six elements: Nature, Fire, Ice, Air, Earth and Lightning.

This repository is the public distribution and information page for **Dunveil Launcher**, our desktop launcher. The initial version targets the Windows development and building team; macOS and Linux are planned for later.

## What the launcher does

- Installs and verifies Minecraft Java Edition, Java 21, Fabric and the Dunveil client modpack.
- Connects players through Microsoft OAuth with PKCE, Xbox Live and Minecraft Services.
- Checks Minecraft Java ownership and retrieves the player's Minecraft profile.
- Launches the game for `build.dunveil.fr`.
- Provides application updates, pack verification and repair, memory settings and support logs.

The launcher requires a legitimate Minecraft Java Edition account. It does not provide cracked/offline authentication or bypass ownership checks. Account session tokens are encrypted locally using the operating system's secure storage. It does not ask for Microsoft passwords itself or send session tokens to a Dunveil authentication server.

## Project status

Initial internal development. The dedicated Microsoft application **Dunveil Launcher** has been registered, and its Minecraft API access review is being prepared. There is no public player release yet. The source repository is private.

Application / client ID: `56e3ba67-daeb-404c-901e-441df3f29eec` (a public identifier, not a secret).

## Downloads and updates

Approved releases will be published in this repository's Releases section. Public release files will not include worlds, account sessions or private server configuration. Third-party mod and resource-pack redistribution permissions must be checked before public distribution.

An independent community project; not an official Minecraft product and not approved by or associated with Mojang or Microsoft.
