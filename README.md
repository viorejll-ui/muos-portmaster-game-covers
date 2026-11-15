# PortMaster Game Covers for muOS

Cover images for **23 PortMaster game and application launchers** in the muOS Ports menu. Tested on an **Anbernic RG40XX H running muOS**.

[**Download artwork ZIP**](muOS_Ports_23_images.zip?raw=true)

![Preview of all 23 images](assets/preview.jpg)

## Installation

1. Download and extract `muOS_Ports_23_images.zip` on your phone or computer.
2. Open the muOS web file manager and navigate to:

   **Primary Storage → MUOS → info → catalogue → External - Ports → box**

3. Choose **Upload Files** and upload the **PNG files inside the extracted `box` folder**. Do not upload the ZIP itself into `box`.
4. Skip any existing images you want to keep.
5. On the handheld, leave the Ports menu and open it again.

No changes to game files or launch scripts are required.

### Filename matching

The image name must match the launcher's filename, replacing `.sh` with `.png`. Preserve spaces, punctuation and capitalization.

| Launcher | Image |
| --- | --- |
| `Grand Theft Auto San Andreas.sh` | `Grand Theft Auto San Andreas.png` |
| `StardewValley.sh` | `StardewValley.png` |

If you renamed a launcher, rename its PNG to match.

## Included entries

- Battle for Wesnoth
- Devilutionx
- Fheroes2
- Flip Clock
- Flynn Son of Crimson
- Grand Theft Auto 3
- Grand Theft Auto San Andreas
- Grand Theft Auto Vice City
- Half-Life
- Halo
- Max Payne
- Moonlight New
- Netsurf
- Quake 2 - Capture The Flag
- Quake 2 - Ground Zero
- Quake 2 - The Reckoning
- Quake 2 - Zaero
- Quake 2
- Quake 3
- Quake
- StardewValley
- Switchfin
- Unreal Tournament 99

## Artwork and display

These custom covers were generated with **ChatGPT's image-generation tools under the creative direction of viorejll-ui**. I selected the references, guided the composition and style, and requested revisions to the characters, frames, logos, boxes and discs.

The collection uses a coordinated framed-cover style. Games generally include a box and disc; applications use a frame without physical media. Quake II expansions have their own themed artwork.

- The device-ready PNG files use a **320 × 240 canvas**, with transparency preserved.
- Use the resized files for the handheld. Full-resolution artwork can appear cropped in the menu.
- Display size also depends on your muOS theme and artwork settings.
- Tested on an Anbernic RG40XX H running muOS; other devices and themes have not been verified.

## Troubleshooting

If an image does not appear:

1. Check that the PNG is directly inside `External - Ports/box`, not inside another `box` folder.
2. Check that its filename matches the `.sh` launcher exactly, apart from the extension.
3. Clear any search text in the web file manager: its filter can hide the folder contents.
4. Leave and reopen the Ports list.

## Creation, inspiration and credits

**Creative direction and reference selection:** [viorejll-ui](https://github.com/viorejll-ui)  
**Image generation and revisions:** ChatGPT, following my instructions and feedback.

The visual inspiration came from the games' original cover art, logos, characters and screenshots, together with classic PC game boxes and printed CDs. The aim was to turn those references into a coordinated collection for my handheld's Ports menu.

The following sources informed the initial reference collection; they are inspiration and reference credits, rather than the creators of these generated covers:

| References | Source |
| --- | --- |
| PortMaster game and application images | [PortMaster-New](https://github.com/PortsMaster/PortMaster-New/tree/main/ports) |
| Grand Theft Auto III and Vice City reference images | [nosro1/ports](https://github.com/nosro1/ports/tree/main/images) |
| Halo handheld-port reference | [Halo CE handheld port](https://github.com/kirklandsig/halo-ce-anbernic-rg35xx) |
| Grand Theft Auto: San Andreas and Unreal Tournament references | Steam store artwork (app IDs 12120 and 13240) |
| Additional visual references | Screenshots and artwork I supplied during the design process |

These are AI-generated fan covers, not official packaging or original in-game screenshots. Game names, characters, logos and trademarks belong to their respective owners. No ownership of those underlying properties is claimed, and this repository does not grant a license to them.

This repository contains artwork and installation instructions only; it includes no game data. It is an unofficial community project, not an official muOS or PortMaster release.
