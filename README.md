# ARK Mod Spawn Code Generator

![Image](https://github.com/user-attachments/assets/b5653971-29b2-42c8-a381-f8ce9680495a)

A simple yet powerful tool designed to generate spawn codes for **ARK: Survival Evolved** mods by scanning the mod's asset files.

## Features
*   **Smart Detection**: Automatically finds `.uasset` and compressed `.uasset.z` files.
*   **Comprehensive Output**: Generates codes for:
    *   **Items**: `admincheat GiveItem "BlueprintPath" ...`
    *   **Creatures (Wild)**: `admincheat SpawnDino "BlueprintPath" ...`
    *   **Creatures (Tamed)**: `admincheat GMSummon "BlueprintPath" ...`
    *   **Engrams**: Auto-unlock entries for your `Game.ini`.
*   **Clean Output**: Results are saved to a neat `SpawnCode.txt` file.
*   **Portable**: Single small executable (< 1MB), no installation required.

## How to Use
1.  Place the `ARK Mod Spawn Code Generator.exe` file inside your mod's **WindowsNoEditor** folder
2.  Run the program.
3.  Wait for the process to finish (it scans all subdirectories).
4.  Open the newly created `SpawnCode.txt` file to find your codes.

