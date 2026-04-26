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
roblox-anticheat/
└── src/
    └── ServerScriptService/
        └── Anticheat/
            ├── Config/
            │   └── AnticheatConfig.lua          (ModuleScript)
            ├── Core/
            │   ├── AnticheatManager.lua         (Script)          ← Main entry point
            │   └── PlayerData.lua               (ModuleScript)
            ├── Movement/
            │   ├── SpeedChecker.lua             (ModuleScript)
            │   ├── TeleportChecker.lua          (ModuleScript)    ← Separate teleport detection
            │   ├── FlyChecker.lua               (ModuleScript)
            │   ├── NoclipChecker.lua            (ModuleScript)
            │   ├── JumpChecker.lua              (ModuleScript)
            │   └── BunnyHopChecker.lua          (ModuleScript)
            ├── Combat/
            │   ├── ReachChecker.lua             (ModuleScript)
            │   ├── AimChecker.lua               (ModuleScript)
            │   └── TriggerChecker.lua           (ModuleScript)
            └── Utilities/
                ├── Punishments.lua              (ModuleScript)
                ├── Helpers.lua                  (ModuleScript)
                └── ViolationLogger.lua          (Script)          ← Optional logging
```
  <img width="1920" height="1080" alt="Ungtihtled" src="https://github.com/user-attachments/assets/195192b5-f0c9-45d5-9525-508989cd5ea5" />
