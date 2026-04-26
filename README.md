# 🍞 Bread - LuaU AntiCheat

**Bread** is a Powerful, Fast Roblox AntiCheat

## ✨ Features

### Core Detections
  - Speed hacks (including teleport, fly, noclip, speed multipliers)
  - Jump power / infinite jump
  - No-clip / phase through walls
  - Air walking / levitation
  - Bunny hopping / advanced movement exploits
- **Combat Anticheat**
  - Reach / hitbox expansion
  - Silent aim / aimbot
  - Triggerbot / auto-clicker

## Directory

```
Anticheat (Folder)
├── Config (Folder)
│   └── AnticheatConfig (ModuleScript)          -- Central settings, thresholds, punishments
├── Core (Folder)
│   ├── AnticheatManager (Script)               -- Main handler: player added/removed, initializes checks
│   └── PlayerData (ModuleScript)               -- Per-player state (last position, violation count, etc.)
├── Movement (Folder)                           -- Covers speed hacks, teleport, fly, noclip, etc.
│   ├── SpeedChecker (Script)                   -- Detects speed multipliers, teleport
│   ├── FlyChecker (Script)                     -- Detects flying/levitation
│   ├── NoclipChecker (Script)                  -- Detects phase through walls
│   ├── JumpChecker (Script)                    -- Jump power + infinite jump
│   └── BunnyHopChecker (Script)                -- Advanced movement / bunny hopping
├── Combat (Folder)                             -- Combat-related exploits
│   ├── ReachChecker (Script)                   -- Hitbox expansion / reach
│   ├── AimChecker (Script)                     -- Silent aim / aimbot (basic heuristics)
│   └── TriggerChecker (Script)                 -- Triggerbot / auto-clicker (if using tools)
├── Utilities (Folder)
│   ├── Punishments (ModuleScript)              -- Kick, warn, teleport back, log violations
│   └── Helpers (ModuleScript)                  -- Raycasting, distance calc, etc.
└── Logs (Optional Folder)
    └── ViolationLogger (Script)                -- Optional: logs to console or DataStore
```
  <img width="1920" height="1080" alt="Ungtihtled" src="https://github.com/user-attachments/assets/195192b5-f0c9-45d5-9525-508989cd5ea5" />
