# GrampsFucker

A memory scanning tool for detecting cheat clients in Minecraft. Scans `javaw.exe` processes to identify known cheat clients via signature matching.

<img width="1111" height="619" alt="image" src="https://github.com/user-attachments/assets/90acc13d-e210-4757-be9d-c6cb6a33128a" />


## ⚠️ Antivirus Flag Warning

It is common for antivirus software to flag tools like GrampsFucker. This happens for several reasons:

- **Behavioral Detection**: The tool reads the memory of other running processes (`javaw.exe`). This is a behavior often associated with malware, causing heuristic-based alerts.
- **Obfuscation**: To protect the code from being easily copied or reversed, the executable is obfuscated. Obfuscation techniques are frequently used by malware to evade detection, which can trigger false positives.
- **Generic Signatures**: The obfuscation and packing methods used can match generic signatures for "hack tools" or "riskware" in antivirus databases.

**Important**: This tool is **not malware**. It does not steal data, damage your system, or perform any malicious actions.


## Features

- **Memory Scanning** - Scans JVM memory of running Minecraft instances
- **Signature-Based Detection** – Detects known cheat clients by matching unique strings in memory
- **Generic Module Detection** – Identifies common cheat modules (KillAura, AimAssist, etc.)
- **Clean UI** – Simple console interface with progress bar

## Current Client Detections

| Clients |
|--------|
| Prestige Client |
| Dqrkis Client|
| Doomsday Client|
| Argon Client |
| Cyemer Client |
| System Client |

## Detected Modules
<details>
<summary><b>Generic Modules Detected</b> (click to expand)</summary>

#### Combat
- Kill Aura, Crystal Aura, Auto Mace, Auto Anchor, Auto Totem
- Auto Crystal, Auto Spear, Auto Lunge, Lunge Macro
- Aim Assist, Trigger Bot, Tbot, Velocity
- No Fall, No Slow, No Web, Auto Hit Crystal
- Auto Inventory Totem, Auto Refill, Fake Lag, Hover Totem, Totem Offhand
- Anti Velocity, Anti Bot, Shield Drain, Stun Slam, No Jump Delay
- W-Tap, Force Totem, Auto Retotem

#### Movement
- InventoryMove, Fast Bridge, Bridge Assist
- Fast Swim, Fast Place, No Break Delay
- Elytra Swap, Firework Mace, Delete USN

#### Auto / Utilities
- Auto Pot, Auto Eat, Auto XP, Auto Armor, Auto Tool
- Auto Sprint, Auto Swim, Auto Walk, Auto Fish
- Auto Shield Break, Auto Shield, Auto Farm, Auto Steal, Auto Drain, Auto Jump Reset
- Auto Drop, Auto Heal, Auto Replenish
- Auto Reply, Auto Sword, Auto Bow, Auto Pearl, Auto Tpa
- Auto Switch, Auto Disconnect, Auto Log, Auto Accept, Auto Double Hand
- Auto Mend, Auto Repair, Auto Reconnect, Auto Join, Auto Leave
- Key Pearl, No Miss Delay, No Attack Delay, Ping Spoof
- Auto Spawner, Auto Chest

#### Visuals
- Tracers, Chams, Name Tags
- ESP, Player ESP, Entity ESP, Storage ESP
- X Ray

#### Evasion
- Self Destruct, Self Delete, Bypass
- String Cleaner, Anti SS
- USN Journal Cleaner, Delete USN Journal, Generic Self Destruct

</details>

## Usage

1. **Run `GrampsFucker.exe`**
2. Select **option 1** to start the scan
3. Results will display detected clients and modules


## Support

If you encounter any issues, feel free to reach out:

- **Discord**: `im_a_scousie`
- **Server**: [Join my Discord](https://discord.gg/3fkg4J2tK6)

## 🙏 Credits

- Made by **granndpa**
- Credits: **Tonyoh** - [MeowClientFucker](https://github.com/MeowTonynoh/MeowClientFucker)
