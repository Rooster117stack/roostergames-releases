# Rooster Games — BarnVale

Windows launcher and update feeds for our experimental shared 120-acre Animal Crossing town.

[Download Rooster Games 0.2.0 for Windows](https://github.com/Rooster117stack/roostergames-releases/releases/download/launcher/RoosterGames-0.2.0-x64-setup.exe)

1. Install Rooster Games 0.2.0. If you already have 0.1.0, install this update once.
2. Open Settings, select your own compatible Animal Crossing USA Rev 0 ISO, and choose your own player profile name.
3. Click **Download**, then **Play**. The signed catalog supplies the BarnVale server address.

The host must be running the BarnVale server and relay. Friends do not need a VPN or router configuration. If the game opens its introduction, **Space** advances dialogue and **W/S** selects answers.

The launcher verifies and downloads the official upstream multiplayer release directly, then applies our mod patch locally. This repository does not distribute a game ISO, the complete game executable, extracted disc assets, town saves, player profiles, or server credentials. Each player supplies their own USA Rev 0 (GAFE01_00) disc image. The launcher includes dependency notices and source packages where required.

This is an experimental fan modification. Installation, file verification, update rollback and local multiplayer were tested. Successful play from another home still needs a real friend connection test; an available download does not establish that test has passed.

The underlying project is [ACGC-PC-Multiplayer](https://github.com/vsimochi/ACGC-PC-Multiplayer), using its official v0.4.1 Windows release as the pinned patch base. Retain the supplied licenses and third-party notices. This project is unofficial and is not affiliated with or endorsed by Nintendo. Development used AI assistance (Codex).

The `catalog` and `launcher` releases hold the signed update feeds. Use the installer above; the patch ZIP is installed and verified by the launcher.
