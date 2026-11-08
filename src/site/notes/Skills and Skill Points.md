---
{"dg-publish":true,"permalink":"/skills-and-skill-points/","title":"Skills and Skill Points","tags":["guide","minecraft","leveling","skills","xp"],"dg-note-properties":{"title":"Skills and Skill Points","tags":["guide","minecraft","leveling","skills","xp"],"aliases":["XP Sources","Leveling System","Skill Points"]}}
---


# Skills and Skill Points

## How levels and points work

- Each skill has its own **level** and **XP bar**.
- Reaching a new level gives **+1 skill point** for *that* skill. Points can only be spent in that skill's tree. Mining points buy mining upgrades.
- **Usable points = your level − points you've spent.**
- Each skill level-up (any skill except Classes itself) also gives **1 Classes XP**. Classes needs a flat **10 XP per level**, so **every 10 skill levels = 1 Class point**. See [[Skills/Classes\|Classes]].
- Each tree has a **Reset** (iron door) that refunds all points of that tree for free.
- Only **Combat** (and with it Classes) can lose levels. That happens when you die in PvP. See [[PvP and Death Penalty\|PvP and Death Penalty]].

## How XP requirements scale

The XP needed for the next level rises by a fixed amount each level:

> **XP for next level = Base + Step × current level**

| Skill | Base | Step | Lv 0→1 | Lv 9→10 | Total to Lv 10 | Total to Lv 20 |
|---|---|---|---|---|---|---|
| Combat | 100 | +25 | 100 | 325 | 2,125 | 6,750 |
| Movement | 500 | +20 | 500 | 680 | 5,900 | 13,800 |
| Mining, Defense, Inventory, Enchanting, Brewing, Farmer, Fishing | 100 | +10 | 100 | 190 | 1,450 | 3,900 |
| Classes | 10 | +0 | 10 | 10 | 100 | 200 |

## Where XP comes from

| Skill                | Action                                         | XP                                          | Limits                                                                                |
| -------------------- | ---------------------------------------------- | ------------------------------------------- | ------------------------------------------------------------------------------------- |
| [[Skills/Combat Skill\|Combat Skill]]     | Kill a hostile monster                         | 5                                           | After 60 kills in a 10-minute window: 1 XP each; after 1,000: 0 until the window ends |
| [[Skills/Combat Skill\|Combat Skill]]     | Kill a player                                  | Large, level-based                          | See [[PvP and Death Penalty\|PvP and Death Penalty]]                                                         |
| [[Skills/Defense Skill\|Defense Skill]]    | Regain health                                  | 1 XP per half-heart healed (rounded)        | Max-HP regen and Wither don't count                                                   |
| [[Skills/Inventory Skill\|Inventory Skill]]  | Craft an item (per craft action)               | 15                                          | 20 crafts per 20 minutes                                                              |
| [[Skills/Inventory Skill\|Inventory Skill]]  | Pick up an item (per pickup)                   | 5                                           | 64 pickups per 20 minutes                                                             |
| [[Skills/Movement Skill\|Movement Skill]]   | Walk or sprint                                 | ≈0.5 XP per block at base speed             | Checked every 5 s; above 10 XP per 5 s it's reduced to 1/10                           |
| [[Skills/Mining Skill\|Mining Skill]]     | Mine ores (no Silk Touch)                      | 1–50                                        | See table in the skill note                                                           |
| [[Skills/Farming Skill\|Farming Skill]]    | Harvest fully grown wheat / carrots / potatoes | 1                                           | none                                                                                  |
| [[Skills/Fishing Skill\|Fishing Skill]]    | Catch something                                | 4–24                                        | none                                                                                  |
| [[Skills/Enchanting Skill\|Enchanting Skill]] | Enchant at a table                             | = the level cost of the enchant             | none                                                                                  |
| [[Skills/Brewing Skill\|Brewing Skill]]    | A vanilla brew finishes                        | 20, split among all players within 5 blocks | none                                                                                  |
| [[Skills/Brewing Skill\|Brewing Skill]]    | Finish a custom brew                           | 20                                          | none                                                                                  |

> [!NOTE]
> The Movement XP is divided by your current base speed. Faster players need to travel further for the same XP, so speed upgrades don't make grinding Movement easier.

## Hidden skills

The admin command `/setlevel` also knows **Trading** and **Building**. These skills exist but have no menu page and no way to earn XP yet. See [[Known Issues\|Known Issues]].

---
Related: [[Leveling Plugin\|Leveling Plugin]] · [[Skills/Classes\|Classes]] · [[PvP and Death Penalty\|PvP and Death Penalty]] · [[Configuration\|Configuration]]
