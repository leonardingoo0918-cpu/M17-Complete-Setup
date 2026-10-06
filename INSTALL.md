# M17 Complete Setup - Installation Guide

## Quick Start

1. **Download** the ZIP from this repo
2. **Extract** it
3. **Copy the `BetterStockSD` folder** to your SD card root
4. **Insert SD into M17**
5. **Boot and enjoy** - everything should work

## What's Included

- ✅ PPSSPP PSP emulator with **FIXED ANALOG STICK**
- ✅ Working D-Pad and all buttons
- ✅ EmulationStation frontend
- ✅ RetroArch optimized for RK3126C
- ✅ All controller mappings correct
- ✅ Performance tuned for smooth gameplay

## Installation Steps

### On Windows:
1. Insert M17 SD card via USB card reader
2. Extract the ZIP
3. Copy the `BetterStockSD` folder to the SD card root
4. Eject safely
5. Insert back into M17 and power on

### On Linux/Mac:
```bash
# Mount SD card (replace sdX with your device)
sudo mount /dev/sdX1 /mnt/m17

# Copy the folder
cp -r BetterStockSD/* /mnt/m17/

# Unmount
sudo umount /mnt/m17
```

## File Structure

After copying, your SD card should look like:
```
SD Card Root/
├── BetterStockSD/
│   ├── .config/
│   │   └── ppsspp/
│   │       └── PSP/SYSTEM/
│   │           ├── ppsspp.ini
│   │           └── controls.ini
│   ├── .emulationstation/
│   ├── storage/
│   └── [other M17 files]
```

## Controller Test

Once booted:
1. Go to PPSSPP Settings → Controls
2. Test D-Pad - should respond
3. Test Analog Stick - should respond in all directions
4. Test buttons (A, B, X, Y) - should all work
5. Test L/R triggers - should work

## Game Installation

Place your PSP games in:
```
/storage/roms/psp/
```

Supported formats:
- .iso
- .cso
- .bin/.cue

## Performance Tips

- Frame Skip: Enabled (better performance)
- Internal Resolution: 1x (native, best for small screen)
- Graphics Backend: OpenGL
- CPU: 333MHz for most games

## Troubleshooting

**Analog stick not working?**
- Check that `controls.ini` is copied correctly
- Verify M17 hardware detection in system settings
- Try calibrating in PPSSPP controls menu

**Games running slow?**
- Enable Frame Skip in PPSSPP settings
- Reduce internal resolution
- Check CPU speed setting (333MHz recommended)

**Controls not responding in menu?**
- Restart EmulationStation
- Check controller connection
- Verify .config folder is present with hidden files enabled

## Support

If something doesn't work:
1. Make sure all hidden folders (starting with `.`) are copied
2. Check file permissions (should be readable)
3. Verify folder structure matches exactly
4. Try re-flashing the SD card

---

**M17 Complete Setup v1.0** - Ready to use!
