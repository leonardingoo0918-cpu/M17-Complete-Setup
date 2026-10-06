# M17 Complete Setup Package

## Overview

Complete, ready-to-use M17 handheld setup with:
- ✅ PPSSPP (PSP emulator) with **WORKING ANALOG STICK**
- ✅ All controllers fixed and tested
- ✅ EmulationStation frontend
- ✅ RetroArch optimized
- ✅ Performance tuned for RK3126C

## What You Get

**One folder (`BetterStockSD`) with everything:**
- All emulator configs
- Controller mappings
- System settings
- Ready to copy to SD card

## Quick Install

1. Download ZIP
2. Extract
3. Copy `BetterStockSD` folder to SD card root
4. Insert into M17
5. Boot and play

## Key Fixes

### Analog Stick ✅ NOW WORKING
- Left stick responds to all directions
- Mapped to joystick axes (10-4000 through 10-4003)
- Tested and verified

### All Controls Working
- D-Pad ✅
- Action Buttons (ABXY) ✅
- Triggers (L/R) ✅
- Start/Select ✅
- Analog Stick ✅

## Controller Mapping

```
D-Pad Up    = 1-19   (keyboard) + 10-19 (joystick)
D-Pad Down  = 1-20   (keyboard) + 10-20 (joystick)
D-Pad Left  = 1-21   (keyboard) + 10-21 (joystick)
D-Pad Right = 1-22   (keyboard) + 10-22 (joystick)

Circle (O)  = 1-52   (keyboard) + 10-190 (joystick)
Cross (X)   = 1-54   (keyboard) + 10-189 (joystick)
Square      = 1-29   (keyboard) + 10-191 (joystick)
Triangle    = 1-47   (keyboard) + 10-188 (joystick)

L Trigger   = 1-45   (keyboard) + 10-193 (joystick)
R Trigger   = 1-51   (keyboard) + 10-192 (joystick)

Start       = 1-62   (keyboard) + 10-197 (joystick)
Select      = 1-66   (keyboard) + 10-196 (joystick)

Analog Stick (Left)
Up    = 10-4003 (joystick Y+)
Down  = 10-4002 (joystick Y-)
Left  = 10-4001 (joystick X-)
Right = 10-4000 (joystick X+)
```

## Performance Settings

- **CPU Core:** Interpreter + JIT
- **CPU Speed:** 333MHz
- **Graphics:** OpenGL
- **Frame Skip:** Enabled
- **Internal Resolution:** 1x (native)
- **Audio:** Enabled with resampling
- **V-Sync:** Off

## Folder Structure

```
BetterStockSD/
├── .config/
│   └── ppsspp/
│       └── PSP/SYSTEM/
│           ├── ppsspp.ini          ← Main config
│           ├── controls.ini        ← Controller mapping (FIXED)
│           └── [other PPSSPP files]
├── .emulationstation/
│   └── [frontend configs]
├── .retroarch/
│   └── [RetroArch configs]
└── storage/
    └── roms/
        └── psp/                     ← Place your games here
```

## Installation

### See INSTALL.md for detailed steps

**TL;DR:**
1. Copy `BetterStockSD` to SD card root
2. Insert into M17
3. Boot
4. Done ✅

## Games Installation

Place PSP game files in:
```
/storage/roms/psp/
```

Supported formats:
- `.iso` (full dumps)
- `.cso` (compressed)
- `.bin/.cue` (multi-file)

## First Boot

1. System will boot to EmulationStation
2. You'll see game categories (Game, Music, Video, etc.)
3. Navigate to GAME section
4. Your PSP games will appear
5. Press A/Circle to launch
6. Analog stick should work in-game

## Testing Controls

**In PPSSPP Menu:**
- Press D-Pad → should navigate
- Press analog stick → should respond in all directions
- Press buttons → should work

**In Game:**
- Analog stick controls character movement
- D-Pad for menu navigation
- Buttons for actions

## Troubleshooting

### Analog stick not working?
- ✓ Verify `controls.ini` is copied
- ✓ Check `.config` folder is on SD
- ✓ Restart EmulationStation
- ✓ Test in PPSSPP menu first

### Games too slow?
- Enable Frame Skip (PPSSPP Settings → Graphics)
- Check CPU speed (should be 333MHz)
- Reduce internal resolution

### No games showing?
- Verify `.emulationstation` folder is on SD
- Place games in `/storage/roms/psp/`
- Restart EmulationStation

## Original M17 Hardware

- **Processor:** RK3126C (quad-core ARM)
- **GPU:** Mali-400
- **RAM:** 512MB
- **Display:** 4.3" 480x272
- **Controls:** Built-in analog stick + D-pad

## Version Info

- **Package Version:** 1.0
- **PPSSPP Version:** Latest optimized
- **Compatibility:** M17 handheld (RK3126C)
- **Status:** Fully tested and working ✅

---

**Ready to play? Download and extract!**
