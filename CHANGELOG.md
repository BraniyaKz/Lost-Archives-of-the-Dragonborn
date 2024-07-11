# The-Lost-Archives-of-the-Dragonborn
A Skyrim Special Edition Modlist by BraniyaKz.

--- 0.0.1 ---
[Major Changes]
- Downloaded Mod Organizer (v2.5.1rc2) and installed it to "*/The Lost Archives of the Dragonborn/" directory.
- Created a Stock Game folder and installed the following:
  - Skyrim Special Edition game (v1.6.640).
  - SkyrimSE.exe and binkw64.dll (v1.5.97).
- Created a Portable Instance of Skyrim Special Edition for the Steam version.
- Downloaded LOOT (v0.23.0) and installed into MO2's "*/loot/..." directory, overwriting loot.dll.
- Stripped MO2 installation of all non-Skyrim/SE/VR game files.
- Removed built-in BSA-handling plugins.
- Removed FNIS-related plugins.
- Removed orphaned Language files.
- Removed all non-Skyrim Stylesheets.

[Executables]
- SKSE.exe auto-detected and added by MO2.
- Added the following:
  - LOOT.exe
- Hid the following:
  - SkyrimSE.exe
  - Skyrim SE Launcher.exe

[Separators]
-> [ Master Files, DLC's, & Resources ]
-> [ Modding Tools, Utilities, & Libraries ]
-> [ General Compatibility, Patches, & Fixes ]
-> --- Generated Output & Saved Settings ---

[Mods]
- Skyrim Script Extender (SKSE) (v2.0.20)
  - Installed files to "*/stock game/...":
    - skse64_1_5_97.dll
    - skse64_loader.exe
    - skse64_steam_loader.dll
  - Installed SKSE mod.
  - Created "*/SKSE/SKSE.ini" and configured the following:
    - [Debug] -> WriteMinidumps=0
    - [Display] -> iTintTextureResolution=1024
    - [General] -> ClearInvalidRegistrations=1
    - [General] -> EnableDiagnostics=0
    - [Memory] -> DefaultHeapInitialAllocMB=1024
    - [Memory] -> ScrapHeapSizeMB=512
  - Moved .psc files: "*/Scripts/Source/..." -> "*/Source/Scripts/...".
  - WJ-Tagged: "WABBAJACK_NOMATCH_INCLUDE".
- ShaderCache Generated.
  - WJ-Tagged: "WABBAJACK_NOMATCH_INCLUDE".
- Created and configured .meta files for the following:
  - Mod Organizer 2
  - LOOT

[Configuration]
- Created "The Lost Archives of the Dragonborn" Profile.
- MO2 -> Enabled Experimental Archives Parsing.
- MO2 -> Set Theme to "Skyrim".
- MO2 -> Various minor adjustments to settings.
