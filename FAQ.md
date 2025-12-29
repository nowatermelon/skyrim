# Bread Frequently Asked Questions

## Contents
(sorted alphabetically)
- [How do I change the dodge hotkey?](#How-do-I-change-the-dodge-hotkey)
- [How do I change the resolution?](#how-do-i-change-the-resolution)
- [How do I change the voice type?](#how-do-i-change-the-voice-type)
- [How do I obtain mod items?](#How-do-I-obtain-mod-items)
- [I can't level up or fast travel.](#I-cant-level-up-or-fast-travel)
- [Is it save to remove xxx mod?](#is-it-save-to-remove-xxx-mod)
- [Some enemies are too high level.](#Some-enemies-are-too-high-level)
- [Wabbajack says something failed to download/low speed.](#Wabbajack-says-something-failed-to-download-low-speed)
- [Where are the crash logs?](#Where-are-the-crash-logs)
- [Why is it called bread? I prefer milk.](#Why-is-it-called-bread-I-prefer-milk)
- [Why is the cave so dark?](#Why-is-the-cave-so-dark)

---
### How do I change the dodge hotkey?
Edit "DodgeHotkey =" in `TK Dodge RE.ini`, and as mentioned in [README](https://github.com/nowatermelon/skyrim/blob/main/README.md#post-installation), you can locate the ini file through filter.

---
### How do I change the resolution?
Use INI Editor in MO2.

<img src="https://github.com/nowatermelon/skyrim/blob/main/_resources/resolution.png" width="40%">

*Note: If the resolution setting doesn't work, find `Bread\stock game\SkyrimSE.exe`, right-click it and go to `properties-compatibility`, then set it up like this:* 

<img src="https://github.com/nowatermelon/skyrim/blob/main/_resources/resolution2.png" width="60%">

---
### How do I change the voice type?
You can download a voice pack you like (such as [2B](https://www.nexusmods.com/skyrimspecialedition/mods/94254) and load it in MCM. See [PC Head Tracking and Voice Type](https://www.nexusmods.com/skyrimspecialedition/mods/11993).

---
### How do I obtain mod items?
Press `delete` to use [Modex](https://www.nexusmods.com/skyrimspecialedition/mods/137877).

[[Top]](#contents)

---
### I can't level up or fast travel.
With [Sunhelm](https://www.nexusmods.com/skyrimspecialedition/mods/39414) enabled, you need to sleep to level up. Additionally, with [Journeyman](https://www.nexusmods.com/skyrimspecialedition/mods/92220), you need to use a travel bag to fast travel.

[[Top]](#contents)

---
### Is it save to remove xxx mod?
A quick way to check is after removing the mod, see if any plugins warn about a missing master file. If so, you’ll see a triangle alert icon, that usually means you may need to regenerate the corresponding outputs like Bodyslide, PGPpatcher, DynDOLOD, etc.

Even without missing masters, it’s not entirely risk-free and your saves could still run into issues. Better keep backups.

<img src="https://github.com/nowatermelon/skyrim/blob/main/_resources/missingmaster.png" width="40%">

[[Top]](#contents)

---
### Some enemies are too high level.
This is a recommended setting for [Skyvalor](https://www.nexusmods.com/skyrimspecialedition/mods/106240). You can search for `SkyPatcher.ini` and change `iEnableUnlevelNPCs=1` to 0 to disable the removal of enemy level caps.

[[Top]](#contents)

---
### Wabbajack says something failed to download/low speed.
If the files are related to base game or DLCs, check the [Installation](https://github.com/nowatermelon/skyrim/blob/main/README.md#Installation) part. Otherwise, manually download the missing files and place them into the `Downloads` folder. See [Wabbajack Wiki](https://wiki.wabbajack.org/user_documentation/Troubleshooting%20FAQ.html) for detailed information.

Sometimes it might simply be a network issue that clears up on its own after a while. Try restarting Wabbajack later to resume downloading.

For files hosted on the [Wabbajack CDN](https://build.wabbajack.org/authored_files), consider a manual download using the Debug option if speeds are poor.

<img src="https://github.com/nowatermelon/skyrim/blob/main/_resources/wabbajackcdn.png" width="60%">

[[Top]](#contents)

---
### Where are the crash logs?
Open the `My Games` folder.

<img src="https://github.com/nowatermelon/skyrim/blob/main/_resources/mygame.png" width="40%">

Then go to the `SKSE` folder within it and search for "crash". You'll see files like `crash-2025-11-22-01-56-21.log`.

[[Top]](#contents)

---
### Why is it called bread? I prefer milk.
Actually, it's got nothing to do with bread... It's just a Chinese pun mixing my channel name with the word "modlist".

[[Top]](#contents)

---
### Why is the cave so dark?
Immersion has some cost, you may need to use torches, lanterns, etc.

[[Top]](#contents)
