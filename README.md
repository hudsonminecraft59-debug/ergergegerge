# Verdant (Fabric, Minecraft 1.21.11)

Client-side mod with a forest-green click GUI. Press **Right Shift** in a world to open it
(rebind in Options > Controls > Key Binds > Verdant).

## Visuals
- **Storage ESP** - chests, trapped chests, ender chests, hoppers, shulker boxes (barrels optional)
- **Spawn Finder** - mob spawners
- **Sus Chunks** - chunks whose blocks add up to a "base score" (shulkers, hoppers, beacons, many chests...). Chat alert when a new one is found.
- Every module: range, through-walls, outline width/opacity, fill, **tracer lines**, distance fade, rainbow mode

## Combat (off by default)
- **Kill Aura** - hits the closest target in reach (players / hostile mobs / animals), waits for the attack cooldown
- **Auto Crit** - works with Kill Aura: waits until you are falling, optional auto jump

## Colors
Per-block on/off plus a hue / saturation / brightness editor with presets and "Apply to all".

Settings save to `config/verdant.properties`.

## Needs
Fabric Loader, Fabric API for 1.21.11, Java 21. Install only on your own client (not on the server).
Many servers ban ESP and combat mods - check the rules first.

## Build
`gradle build` (Gradle 9.2+). The jar is in `build/libs/` - use the one without `-sources`.
