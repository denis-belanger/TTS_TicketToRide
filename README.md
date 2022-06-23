# Ticket to Ride Scripted
![Ticket to Ride - Thumbnail](https://user-images.githubusercontent.com/66279959/175208890-d2d928e6-2e08-4df4-82be-6421bd8b1c3e.png)

**Ticket to Ride Scripted** Tabletop Simulator mod can be found in the Steam Workshop:
- https://steamcommunity.com/sharedfiles/filedetails/?id=2754116876

Tabletop Simulator is required to play the mod and can be found in the Steam Store:
- http://store.steampowered.com/app/286160/Tabletop_Simulator/

## Instructions
1. Install Atom:
   - https://api.tabletopsimulator.com/atom/#installing-atom
2. Install the Tabletop Simulator plugin for Atom:
   - https://api.tabletopsimulator.com/atom/#installing-the-official-plugin
3. In Atom, go to **File → Settings → Packages** and search for ***tabletopsimulator-lua***.
4. Click **Settings**, then check ***#include other files***.
5. Under ***Base path for files you wish to bundle or #include***, enter the path to your Git folder.
6. In Tabletop Simulator, load **Splendor Scripted + Expansions** from the Steam Workshop, make a new save file, then load that save file.
7. In Atom, go to **File → Add Project Folder...** and select the this repository's folder under your Git folder.
   - You should now be able to edit the scripts as separate files, rather than one monolithic global file.
8. After making any changes to any scripts, go to **Packages → Tabletop Simulator → Save and Play** to save your changes to the save file.

## Recommended optional packages
- https://atom.io/packages/minimap
- https://atom.io/packages/minimap-git-diff
- https://atom.io/packages/linter
- https://atom.io/packages/Sublime-Style-Column-Selection
