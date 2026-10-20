# Obsidian Noclip

Mod for Obsidian.

This mod enables noclip in Geometry Dash 2.209 through the standalone Obsidian mod loader. While the mod is ON, player collisions with hazards do not cause a death. Switching the mod OFF restores the original collision behavior.

## Install from Obsidian

1. Open Geometry Dash.
2. Open the Obsidian menu.
3. Open **MODS** and press **REFRESH** if this repository is not listed yet.
4. Find **NOCLIP** and press **INSTALL**.
5. Open **LIBRARY** and switch **NOCLIP** to ON.
6. Start a level and test the mod. Switch it OFF to restore normal deaths.

## Manual installation

1. Download `noclip.obs` from this repository.
2. Copy it into `Geometry Dash\Obsidian\mods`.
3. Restart Geometry Dash, or open **LIBRARY** and press **REFRESH**.
4. Switch **NOCLIP** to ON.

## Compatibility

- Obsidian standalone loader
- Geometry Dash 2.209 on Windows 64-bit

Obsidian checks the supported game build and the target function before enabling the patch. If that check fails, the mod stays OFF instead of writing to an unknown game version.

## Source

```text
OBSIDIAN/2
name=NOCLIP
description=Pass hazards
code:
noclip = true;
```
