# Lutris game works even though DXVK/Vulkan status is unclear

## System
- Arch Linux (fresh install)
- Older laptop (practice system)
- Wine + Lutris

## Problem
After reinstalling Arch Linux, I installed Lutris and tried to run a Windows game.
The game eventually ran, but Lutris did not clearly show DXVK, Vulkan, or VKD3D as enabled.

This made it confusing to understand whether the setup was correct.

## What I did
- Installed Wine, Lutris, and Winetricks
- Created a separate Wine prefix for older games
- Installed common 32-bit libraries required for gaming
- Installed DXVK using the AUR
- Installed Vulkan tools and loaders
- Tested the game through Lutris

## Result
- The game runs and is playable
- Lutris UI does not clearly indicate DXVK/Vulkan usage
- Vulkan tools are installed, but status is not obvious

## What I learned
- A game can work even if tools do not clearly report DXVK or Vulkan status
- Linux gaming setup can be functional without full clarity in the UI
- Step-by-step testing is more important than perfect understanding
- Documentation and verification matter more than memorizing commands

## Notes
I followed documentation and videos for guidance and verified results by testing the game directly.
