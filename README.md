# Clean Ops T7

A Patch for Call of Duty: Black Ops 3 - Multiplayer (Steam)

This patch ensures that any previously identified cheaters are automatically removed from multiplayer matches whenever a player with the patch installed joins or plays a game, maintaining a cheat-free environment.

This Patch also fixes most known Exploits and also includes a few bugfixes.

Please be aware that Clean Ops T7 is not an open source tool.

Join our [Discord](https://discord.gg/3hR2ffzhfV) for support and more information!

## Features

- [IP-Spoofing](https://github.com/notnightwolf/cleanopsT7/wiki/General-and-Technical-Information#ip-spoofing)
- [Patches most known exploits](https://github.com/notnightwolf/cleanopsT7/wiki/General-and-Technical-Information#exploit-patching)
- [Disconnects previously identified cheaters](https://github.com/notnightwolf/cleanopsT7/wiki/General-and-Technical-Information#automatic-cheater-removal)
- [Fixes FPS-Issues](https://github.com/notnightwolf/cleanopsT7/wiki/General-and-Technical-Information#performance-fixes)
- [Server-Browser](https://github.com/notnightwolf/cleanopsT7/wiki/Full-Explanation-of-the-Ingame-User-Interface#servers---tab)
- [Report System](https://github.com/notnightwolf/cleanopsT7/wiki/Full-Explanation-of-the-Ingame-User-Interface#user-icon)
- Some Quality of Life features - ["Tools" Tab](https://github.com/notnightwolf/cleanopsT7/wiki/Full-Explanation-of-the-Ingame-User-Interface#tools---tab)

## Windows & Linux Installation

- Download the `d3d11.dll` [here](https://raw.githubusercontent.com/notnightwolf/cleanopsT7/main/d3d11.dll).
- Move the `d3d11.dll` into your Black Ops 3 directory (usually located in `C:\Program Files (x86)\Steam\steamapps\common\Call of Duty Black Ops III)`.
  
  <sub>Tip: Right-click the game in Steam > Manage > Browse local files.</sub>
- Launch the game through **Steam** as you normally would.

  - **Linux Note:** If Clean Ops doesn't load, set your Steam Launch Options to: 
  `WINEDLLOVERRIDES="d3d11=n,b" %command%`.

  Watch our quick video guide here: <sub>_Click Image for YouTube Redirect_</sub> [![1770315937961~2(1)](https://github.com/user-attachments/assets/582de237-01fe-42ce-a95d-e417e3debbb3)](https://youtu.be/OsUntxCPDSo)

## Uninstallation & Disabling

If you need to disable Clean Ops or remove it entirely:

-  **Temporary Disable (Vanilla Mode):** Hold the **Shift** key immediately after launching the game through Steam. Continue holding it until a popup appears; Clean Ops will not load for that session.

-   **Via the Clean Ops In-Game UI:** Launch Black Ops 3, open the Clean Ops UI, go to [`Settings -> System`](https://github.com/notnightwolf/cleanopsT7/wiki/Full-Explanation-of-the-Ingame-User-Interface#system), and click the "Delete Clean Ops" button.

-  **Manual Removal:** While Call of Duty: Black Ops 3 is **not** running, navigate to your game's root directory (e.g., `C:\Program Files (x86)\Steam\steamapps\common\Call of Duty Black Ops III`) and delete the `d3d11.dll` file.

    - **Note:** The Clean Ops folder will stay in your game directory but won't do anything without the `d3d11.dll`.

## Documentation
View the full documentation _(Work in Progress)_ for the cleanopsT7 Patch on this repo's [Wiki Page](https://github.com/notnightwolf/cleanopsT7/wiki).

## FAQ

Find answers to common questions and solutions for issues related to the Clean Ops T7 patch on our GitHub Wiki's [FAQ](https://github.com/notnightwolf/cleanopsT7/wiki/Frequently-Asked-Questions)

## Credits
- shiversoftdev
- WNTD
- Scropts
- momo5502

