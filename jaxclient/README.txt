JaxClient 1.1.0 - Fabric client mod for Minecraft 1.21.4

BUILD
- GitHub Actions uses Java 25 to run the configured Fabric Loom plugin.
- The mod is still compiled for Java 21 (Minecraft 1.21.4 runtime compatibility).
- Push to main, then open Actions and download the JaxClient-1.1.0 artifact.

INSTALL
1. Use a Fabric profile for Minecraft Java 1.21.4.
2. Install Fabric API 0.119.4+1.21.4.
3. Put the built jaxclient-1.1.0.jar in the instance mods folder.

CONTROLS
- Right Shift: open/close ClickGUI
- B: toggle Fullbright
- V: toggle AutoSprint
- Other module states can be toggled in the ClickGUI and are saved in config/jaxclient.json.

MODULES
RENDER
- Fullbright: client-side night vision effect.
- Direction: eight-point compass HUD.

MOVEMENT
- AutoSprint: sprints while forward is held and sneak is not held.

UTILITY / HUD
- FPS Counter, Ping, Clock, Coordinates, Keystrokes, Keybind List, Armor Status.
- Biome: displays the current biome.
- Speedometer: horizontal speed in blocks per second.
- World Time: in-game time and day count.
- Food Status: food level and saturation.
- Auto Tool: selects the fastest mining-speed hotbar item for the block under the crosshair.
- Armor Alert: checks every five seconds and notifies when equipped armor reaches roughly 10% durability or less.

Open the menu with Right Shift. HUD modules are toggled in the Utility tab. All additions are client-side display or local convenience functions. They do not grant server-side permissions or bypass server rules.
