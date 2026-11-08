---
{"dg-publish":true,"permalink":"/leveling-plugin/","title":"Leveling Plugin","tags":["plugin","minecraft","guide","leveling","rpg","skills","home","gardenEntry"],"dg-note-properties":{"title":"Leveling Plugin","tags":["plugin","minecraft","guide","leveling","rpg","skills","home","gardenEntry"],"aliases":["Home","Leveling","Overview"]}}
---


# Leveling Plugin

> [!TIP] New here?
> Read the [[Beginner Guide\|Beginner Guide]] first. It explains your first hour in about five minutes.

## 1. Overview

**Leveling** turns survival Minecraft into a skill-based RPG. You start out weaker than in vanilla. You have half the hearts, you walk slower, you can't wear armor and almost your whole inventory is locked. Everything you do (fighting, mining, walking, crafting, fishing, farming, brewing, enchanting, healing) gives XP in a matching **skill**. Every skill level gives you **1 skill point** for that skill. You spend points in the `/menu` to buy back your strength, and later to go far past vanilla limits.

How it changes the game:

- **Progression matters again.** Armor, the Elytra, inventory space and even your base walking speed have to be earned. See [[Starting Stats\|Starting Stats]].
- **You build your own character.** Ten skill trees and four combat [[Skills/Classes\|Classes]] let you build a tank, a glass-cannon archer, a bare-fisted brawler or a speedy explorer.
- **PvP has stakes.** Killing a player steals their Combat XP, and the shown Combat Level under every name tag lets you judge a fight. See [[PvP and Death Penalty\|PvP and Death Penalty]].
- **Brewing goes beyond vanilla.** Brew Speed III+, Strength IV, Regeneration V and longer potions with the [[Custom Potion Brewing\|Custom Potion Brewing]] system.
- **Upgrades can be reset for free at any time**, so experimenting is safe.

## 2. Obsidian Tags

`#plugin` `#minecraft` `#guide` `#leveling` `#rpg` `#skills` `#pvp` `#brewing` `#classes` `#admin` `#commands`

Every note in this vault has these tags in its frontmatter, so you can filter by `#guide` (player notes) or `#admin` (server notes).

## 3. Commands

| Command | Permission | Description & Syntax | Example |
|---|---|---|---|
| `/menu` | Everyone | Opens the Leveling menu with all your skills, levels and XP. Click a skill to open its upgrade tree. | `/menu` |
| `/menuothers` | Server operator (OP) | Shows another online player's skill overview (view only). Syntax: `/menuothers <player>` | `/menuothers Steve` |
| `/setlevel` | Server operator (OP) | Sets a player's level in one skill, optionally with XP. Syntax: `/setlevel <player> <skill> <level> [xp]` | `/setlevel Steve mining 15 40` |

Full details, valid skill names and pitfalls: [[Commands\|Commands]] · Who may use what: [[Permissions\|Permissions]]

## 4. Gameplay Mechanics & Features

### The core loop (step by step)

1. **Do things** → earn XP in the matching skill. See the XP table in [[Skills and Skill Points\|Skills and Skill Points]].
2. **Level up** → you get a chat message (`Mining Level 3 Reached`) and **+1 skill point** in that skill.
3. **Every skill level also gives 1 Classes XP.** Every 10 skill levels across all skills give you **1 Class point**. See [[Skills/Classes\|Classes]].
4. **Open `/menu`** → click a skill icon → click an upgrade to buy it with that skill's points.
5. **Change your mind?** The iron door in every tree resets that tree and refunds all its points.

### Skill trees

| Skill | Menu icon | What you get | Note |
|---|---|---|---|
| Classes | Player head | Tank, Melee, Bare-Handed, Ranged multipliers | [[Skills/Classes\|Classes]] |
| Combat | Iron sword | Attack damage, attack speed, knockback, bow & fist damage | [[Skills/Combat Skill\|Combat Skill]] |
| Mining | Iron pickaxe | Mining speed, ore luck, **armor tiers** | [[Skills/Mining Skill\|Mining Skill]] |
| Defense | Shield | Max HP, armor, toughness, regeneration | [[Skills/Defense Skill\|Defense Skill]] |
| Inventory | Chest | **Unlock inventory slots** | [[Skills/Inventory Skill\|Inventory Skill]] |
| Movement | Leather boots | Walking speed, **Elytra unlock** | [[Skills/Movement Skill\|Movement Skill]] |
| Enchanting | Enchanting table | Revive, dodge chance, more vanilla XP | [[Skills/Enchanting Skill\|Enchanting Skill]] |
| Brewing | Potion | Fire safety, stronger & longer potions | [[Skills/Brewing Skill\|Brewing Skill]] |
| Farmer | Diamond hoe | Crop luck, buffed wolf pets | [[Skills/Farming Skill\|Farming Skill]] |
| Fishing | Fishing rod | Fishing luck, oxygen, underwater mining | [[Skills/Fishing Skill\|Fishing Skill]] |

### Special systems

- [[Starting Stats\|Starting Stats]]: what is weaker than vanilla and how you get it back
- [[PvP and Death Penalty\|PvP and Death Penalty]]: XP stealing, the "frozen" state after losing levels, Revive
- [[Custom Potion Brewing\|Custom Potion Brewing]]: brewing potions above vanilla levels
- Combat Level display: every player's Combat level is shown under their name tag

## 5. Configuration Options

The plugin has **no config file to edit**. All balancing values are built in. Player progress is saved with each player's own data. Tamed wolf pets are tracked in `plugins/Leveling/pets.yml`.

The full list of built-in values (XP curves, caps, costs) and the scoreboards the plugin creates: [[Configuration\|Configuration]]. Behaviour admins should know about before going live: [[Known Issues\|Known Issues]].

---
Related: [[Beginner Guide\|Beginner Guide]] · [[Skills and Skill Points\|Skills and Skill Points]] · [[Commands\|Commands]] · [[Permissions\|Permissions]] · [[Configuration\|Configuration]]
