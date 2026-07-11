# Skyrim Awesome Savefiles

Save files that place you in Helgen Keep, right before you leave. Skip the opening cart ride and start your journey.

## What you get

- One save per playable race (10 races)
- Location: Helgen Keep, exit tunnel
- Character already created for that race
- Main quest past the dragon attack
- Level 1, default gear (vanilla)
- No mods required to load

## Who this helps

- Players who want to skip the intro and pick a race
- Modders who need the same starting point for tests (DynDOLOD, load order checks)

## Requirements

- Skyrim Special Edition or Anniversary Edition (same save works on both)
- Skyrim Legendary Edition uses a different save format. Legendary Edition saves are not included in this repo yet.
- Not for Skyrim VR

## Embed the save

### Step 1: Get the file

1. Open the folder for your race in [`races/`](races/)
2. Click the `.ess` file
3. Click **Download** or **Download raw file**

### Step 2: Open your Saves folder

Press `Win + R`, paste one of these paths, then press Enter.

| Edition | Path |
|---------|------|
| Special Edition / Anniversary Edition | `%USERPROFILE%\Documents\My Games\Skyrim Special Edition\Saves` |
| Legendary Edition | `%USERPROFILE%\Documents\My Games\Skyrim\Saves` |

If the `Saves` folder does not exist, launch Skyrim once and quit. The game will create it.

### Step 3: Drop the file in

Drag the downloaded `.ess` file into the Saves folder. You can also copy and paste it there.

You can rename the file if you want a different name on the load screen.

### Load the save

1. Start Skyrim
2. Main menu → **Load** → pick the save

### Optional: copy with PowerShell

Change the file name and source folder if needed.

```powershell
Copy-Item -Path "$env:USERPROFILE\Downloads\<save-name>.ess" -Destination "$env:USERPROFILE\Documents\My Games\Skyrim Special Edition\Saves\"
```

On Mac or Linux with Proton, use the same path inside your game prefix: `Documents/My Games/Skyrim Special Edition/Saves/`.

## Available saves

Each folder holds one save for that race.

| Folder | Race |
|--------|------|
| [`argonian/`](races/argonian/) | Argonian |
| [`breton/`](races/breton/) | Breton |
| [`darkelf/`](races/darkelf/) | Dark Elf (Dunmer) |
| [`highelf/`](races/highelf/) | High Elf (Altmer) |
| [`imperial/`](races/imperial/) | Imperial |
| [`khajiit/`](races/khajiit/) | Khajiit |
| [`nord/`](races/nord/) | Nord |
| [`orc/`](races/orc/) | Orc |
| [`redguard/`](races/redguard/) | Redguard |
| [`woodelf/`](races/woodelf/) | Wood Elf (Bosmer) |

## After you load

You stand in Helgen Keep, about to walk out into Skyrim. Follow the quest marker to Riverwood when you are ready. This is a good point to install mods or regenerate DynDOLOD.

## Notes

- Back up your own saves before copying a new one in
- The character name on the load screen matches the save file
- Modded playthroughs may need matching plugins. These saves are vanilla
- Report issues on [GitHub](https://github.com/lukegabriel520/Skyrim-Awesome-Savefiles/issues)
