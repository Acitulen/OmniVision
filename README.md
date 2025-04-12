# DebugMod
This mod adds the multifunctional console menu for comfortable modding, debugging and manipulation.  
  
**⚠️WARNING⚠️ This mod is designed to function with VotV-082b_0016. Using older or newer versions of the game may cause errors!**  

If you have any suggestions or found a bug you can send it as "issue" in my [github repository](https://github.com/Acitulen/OmniVision).

# Configs:

**Ctrl+Shift+C** - open mod configs.  

**ScreenUpdateRadius** - Distance to the player at which the screen updates. ***High values may cause performance issues.**  
**ScreenUpdateDelay** - Camera image refresh delay (in seconds). ***Low values may cause performance issues.**

# Preview



<details>
<summary>Demonstration</summary>

* **CCTV mode:**  

![Preview](https://github.com/Acitulen/OmniVision/blob/1.0.0/Preview/Preview2.png?raw=true)

* **360 camera:**  

![Preview](https://github.com/Acitulen/OmniVision/blob/1.0.0/Preview/Preview3.png?raw=true)

</details>

# Features: 
## *:
- *
- 

## Manual instalation guide.

<details>
<summary>Install unreal shimloader</summary>

1. Copy `dwmapi.dll` into the `GAME/Binaries/Win64` directory. Its new path should be `GAME/Binaries/Win64/dwmapi.dll`.
2. Copy the contents of the `UE4SS` folder in the package into `GAME/Binaries/Win64`.

`GAME/Binaries/Win64` should now contain the following *new* files and folders:
- `GAME-Win64-Shipping.exe`
- `ue4ss.dll`
- `UE4SS-settings.ini`
- `dwmapi.dll` ← *This is the unreal-shimloader binary. It will load UE4SS for you.*
- `Mods/`
</details>

<details>
<summary>Install OmniVision</summary>

1. Copy `DebugMod.pak` from the `pak` folder to `GAME/Content/Paks/LogicMods` directory. 
2. Copy the contents of the `mod` folder in `GAME/Binaries/Win64/Mods/Acitulen-DebugMod` directory.  
*you have to create `Acitulen-DebugMod` folder manually.
</details>
