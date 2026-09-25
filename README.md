# Eiyuden Chronicle: Hundred Heroes — Copywriting Overhaul

A comprehensive copywriting and text overhaul for **Eiyuden Chronicle: Hundred Heroes**. This mod combines a faithful, natural English story/dialogue retranslation with exhaustive, transparent in-game mechanics and item descriptions.

---

## Table of Contents

- [Overview](#overview)
- [What the Mod Changes](#what-the-mod-changes)
  - [1. Dialogue & Story Retranslation](#1-dialogue--story-retranslation)
  - [2. Description Overhaul](#2-description-overhaul)
  - [3. UI & Terminology Consistency](#3-ui--terminology-consistency)
- [Included Files](#included-files)
- [Installation Guide](#installation-guide)
- [Uninstallation](#uninstallation)
- [Compatibility & Save Safety](#compatibility--save-safety)
- [Update Log](#update-log)
- [Credits & Acknowledgments](#credits--acknowledgments)

---

## Overview

While playing *Eiyuden Chronicle: Hundred Heroes*, two issues with the official English release consistently broke immersion for me:
1. **Overly liberal localization**: The dialogue often relies on anachronistic modern internet slang, memes, and phrasing deviations that take away from the world's fantasy tone and faithful character personalities.
2. **Opaque descriptions**: Vague tooltips (such as "slightly increases damage" or "moderately restores HP") that obscure actual numbers, percentages, turn counts, and mechanics needed to make informed tactical choices.

I put together this overhaul for my own playthrough to address both—bringing back a faithful, grounded dialogue flow closer to the original Japanese script, paired with transparent, data-driven descriptions across all items, abilities, and Rune-Lenses.

---

## What the Mod Changes

### 1. Dialogue & Story Retranslation
- **Faithful Character Voices**: Restores character dialogue closer to the original Japanese intent and emotional tone, removing out-of-place contemporary slang.
- **Natural Phrasing**: Polished English flow while respecting character quirks (e.g., Nowa, Seign, Marisa, Garr, Mio, and the rest of the 100+ heroes) without excessive exaggeration.
- **Lore & Story Consistency**: Ensures worldbuilding terms, character relationships, and emotional beats stay true to the story.

### 2. Description Overhaul
- **Rune-Lenses & Skills**: Exact percentage boosts, SP/MP costs, elemental affinities, target types, and status effect chances instead of ambiguous wording.
- **Consumable & Battle Items**: Specific healing numbers, stat adjustments, and duration turn counts.
- **Weapons, Armor & Accessories**: Detailed stat breakdowns and hidden passive bonuses revealed directly in tooltips.
- **Support & Passive Abilities**: Clear details on party-wide passive buffs, activation triggers, and percentages.
- **Cooking Mini-Game**: Transparent ingredient preferences, taste categories, and dish attributes.
- **Town & HQ Building Upgrades**: Explicit prerequisites and material/yield stats for fortress town facilities.

### 3. UI & Terminology Consistency
- Standardized ability and status effect names across skill menus, combat logs, and party status screens.

---

## Included Files

This repository contains two pre-packaged Unity AssetBundle files:

| File Name | Purpose |
| :--- | :--- |
| `localization-string-tables-english(en)_assets_all.bundle` | Retranslated English dialogue, story lines, and UI string tables |
| `dc45330cf35da75eac71f243c0f8c2fd.bundle` | Master game data tables including detailed descriptions for runes, items, and abilities |

---

## Installation Guide

> [!NOTE]
> **Platform Notice**: This mod has **only been tested on the Steam version** of the game. It has not been tested on GOG, Xbox / PC Game Pass, or other platforms.

> [!IMPORTANT]
> **ALWAYS backup your original files first!**
> Before replacing any files, copy your existing `.bundle` files to a safe backup folder so you can restore them at any time.

### Instructions (Steam)

1. Open your **Steam Library**.
2. Right-click **Eiyuden Chronicle: Hundred Heroes** > **Manage** > **Browse local files**.
3. In the game folder that opens, navigate to:
   ```text
   EiyudenChronicle_Data\StreamingAssets\aa\StandaloneWindows64\
   ```
   *(Note: Depending on your update version, the folder may be named `Eiyuden Chronicle Hundred Heroes_Data`)*
4. Locate the existing files:
   - `dc45330cf35da75eac71f243c0f8c2fd.bundle`
   - `localization-string-tables-english(en)_assets_all.bundle`
5. **Back them up** (e.g., copy them to an `Original_Backup` folder).
6. Copy both bundle files from this repository and **paste & overwrite** them into that `StandaloneWindows64` directory.
7. Launch the game and enjoy!

---

## Uninstallation

To revert back to the vanilla game:
1. Delete the modified `.bundle` files from `StandaloneWindows64\`.
2. Restore your previously backed up files.
3. *Alternative (Steam)*: Right-click the game in Steam > **Properties** > **Installed Files** > **Verify integrity of game files**.

---

## Compatibility & Save Safety

- **Save File Safe**: Modifying string tables and description bundles does **not** alter your save file structure. You can install or remove this mod at any time during an ongoing playthrough without corrupting save files.
- **Game Updates**: If the official game receives an update through Steam, the game launcher may overwrite the modified bundle files. If that occurs, simply re-copy the modded bundle files back into the directory.

---

## Update Log

### v1.0.0
- **Initial Release of Copywriting Overhaul**.
- Merged retranslated English dialogue and story text from the [AI EN Retranslation Project](https://www.nexusmods.com/eiyudenchronicle/mods/21).
- Merged transparent, detailed item, ability, Rune-Lens, and HQ descriptions from [Description Overhaul Proiectus](https://www.nexusmods.com/eiyudenchronicle/mods/22).
- Resolved overlapping string table entries to ensure compatibility with recent game patch updates.
- Tested and verified on the latest Steam PC release.

---

## Credits & Acknowledgments

This project builds upon the hard work and dedication of the *Eiyuden Chronicle* modding community:

- **AI EN Retranslation Project**:
  - Mod Page: [Nexus Mods #21](https://www.nexusmods.com/eiyudenchronicle/mods/21)
  - For the dialogue and story retranslation adjustments that restore natural character expression and faithful tone.

- **Description Overhaul Proiectus**:
  - Mod Page: [Nexus Mods #22](https://www.nexusmods.com/eiyudenchronicle/mods/22)
  - Created by **Kurelyn Proiecta** (**Lynnemie** and **MahouKurein**).
  - For researching game formulas, data values, and writing in-depth descriptions for items, Rune-Lenses, support passives, and mini-game mechanics.

- **Rabbit & Bear Studios & 505 Games**:
  - For developing and publishing *Eiyuden Chronicle: Hundred Heroes*.
