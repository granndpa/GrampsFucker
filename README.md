# GrampsFucker

A memory scanning tool for detecting cheat clients in Minecraft. Scans `javaw.exe` processes to identify known cheat clients via signature matching.

![Demo](https://imgur.com/a/8dxSOS0)

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

## Current Detections

| Clients |
|--------|
| Doomsday |
| Prestige |

### Generic Modules Detected
- KillAura, AimAssist, TriggerBot, AutoClicker
- ShieldBreaker, ClickGUI, HudEditor
- BlinkManager, PacketLogger, AngelWings
- MotionBlur, JumpCircles, Plinko
- CinematicCamera, AutoSpear, AntiBot
- FakeLag, BowAimBot, ElytraFly
- NoSlowDown, TargetStrafe, AutoAnchor
- CrystalAura, LagCompensation, NoHurtCam
- NoWeather, NoFog, NoScoreboard, NoBossBar

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
