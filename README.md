# 💀 COMPLEX TOMB SKYBLOCK
### Smart Mob Hunting · Minecraft Java 1.21.4 Fabric

**Hunt smarter. Move naturally. Stay in control.**

Complex Tomb Skyblock is a client-side mob-hunting mod designed to automate target detection, navigation, combat, and patrol within a configurable hunting area.

## ⚔️ Core Features

**🎯 Smart Mob Targeting**
- Automatically detects eligible mobs within the configured hunting radius.
- Uses a mob whitelist based on Minecraft Registry IDs, such as `minecraft:zombie`.
- Selects suitable targets and switches targets when necessary.

**👁️ Natural Look & Tracking**
- Observes a target for approximately **0.75 seconds** before approaching.
- Uses smooth head rotation with gradual acceleration and deceleration.
- Tracks moving targets instead of snapping instantly toward them.

**🧭 Intelligent Navigation**
- Planned A* pathfinding to navigate around obstacles.
- Recalculates routes when blocked or stuck.
- No teleportation or walking through walls.
- Stops and reports an issue when no safe route can be found.

**🔎 Search & Patrol**
- Looks around when no suitable targets are nearby.
- Actively searches for mobs within the permitted area.
- Can perform short patrols when additional searching is needed.
- Avoids wandering indefinitely beyond the hunting boundary.

**🏠 Home & Hunting Radius**
- Set a home position as the central reference point.
- Configure the hunting radius.
- Return home using normal movement rather than teleportation.

**🖥️ Lightweight GUI**
- A compact interface inspired by Minecraft's vanilla style.
- Displays mob names and Registry IDs without custom mob images.
- Search for mobs and add or remove them from the whitelist.
- Adjust observation time, hunting radius, and movement behavior.
- Planned GUI keybind: `Right Shift`.

## ⌨️ Command Preview

- `/amh add zombie` — Add Zombie to the whitelist.
- `/amh remove zombie` — Remove Zombie from the whitelist.
- `/amh list` — Display the mob whitelist.
- `/amh sethome` — Set your home position.
- `/amh home` — Return home.
- `/amh radius 32` — Set the hunting radius to 32 blocks.
- `/amh start` — Start hunting.
- `/amh stop` — Stop hunting.
- `/amh status` — Check the current status.

## ⚙️ Compatibility

- **Minecraft:** Java Edition 1.21.4
- **Mod loader:** Fabric
- **Java:** 21
- **Architecture:** Client-side; no separate server-side mod is required.

The server remains authoritative. Server rules and anti-cheat systems may restrict automated movement or combat.

## 🚧 Project Status

The features above describe the planned design. Implementation, build availability, and compatibility have not yet been verified.

**Complex Tomb Skyblock — Smarter hunting, smoother movement, and full control over your hunt.**
