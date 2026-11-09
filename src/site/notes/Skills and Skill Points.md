---
{"dg-publish":true,"permalink":"/skills-and-skill-points/","title":"Skills and Skill Points","tags":["guide","minecraft","leveling","skills","xp"],"dg-note-properties":{"title":"Skills and Skill Points","tags":["guide","minecraft","leveling","skills","xp"],"aliases":["XP Sources","Leveling System","Skill Points"]}}
---


# Skills and Skill Points

## How levels and points work

- Each skill has its own **level** and **XP bar**.
- A new level gives **+1 skill point** for *that* skill. Points can only be spent in that skill's tree.
- **Usable points = your level − points you've spent.**
- Every skill level-up (except Classes itself) also gives **1 Classes XP**. Classes needs a flat **10 XP per level**, so **every 10 skill levels = 1 Class point**. Your **first class is free**, so you can unlock it at level 0. See [[Skills/Classes\|Classes]].
- Each tree has a **Reset** (iron door) that refunds all its points for free.
- Only **Combat** (and with it Classes) can lose levels, when you die in PvP. See [[PvP and Death Penalty\|PvP and Death Penalty]].

## How XP requirements scale

The XP needed for the next level grows by a fixed amount each level:

> **XP for next level = Base + Step × current level**

| Skill | Base | Step | Lv 0→1 | Lv 9→10 | Total to Lv 10 | Total to Lv 20 |
|---|---|---|---|---|---|---|
| Combat | 100 | +25 | 100 | 325 | 2,125 | 6,750 |
| Movement | 500 | +20 | 500 | 680 | 5,900 | 13,800 |
| Mining, Defense, Inventory, Enchanting, Brewing, Farmer, Fishing | 100 | +10 | 100 | 190 | 1,450 | 3,900 |
| Classes | 10 | +0 | 10 | 10 | 100 | 200 |

## Where XP comes from

| Skill | Action | XP | Limits |
|---|---|---|---|
| [[Skills/Combat Skill\|Combat Skill]] | Kill a hostile monster | 5 | After 60 kills in 10 minutes: 1 XP each; after 1,000: 0 until the 10 minutes are up |
| [[Skills/Combat Skill\|Combat Skill]] | Kill a player | Large, level-based | See [[PvP and Death Penalty\|PvP and Death Penalty]] |
| [[Skills/Defense Skill\|Defense Skill]] | Regain health | 1 XP per half-heart healed (rounded) | Healing from *Regen Max HP* doesn't count |
| [[Skills/Inventory Skill\|Inventory Skill]] | Craft an item (per craft) | 15 | 20 crafts per 20 minutes |
| [[Skills/Inventory Skill\|Inventory Skill]] | Pick up an item (per pickup) | 5 | 64 pickups per 20 minutes |
| [[Skills/Movement Skill\|Movement Skill]] | Walk or sprint | ≈0.5 XP per block at base speed | Above 10 XP per 5 seconds it drops to 1/10 |
| [[Skills/Mining Skill\|Mining Skill]] | Mine ores (no Silk Touch) | 1–50 | none |
| [[Skills/Farming Skill\|Farming Skill]] | Harvest fully grown wheat / carrots / potatoes | 1 | none |
| [[Skills/Fishing Skill\|Fishing Skill]] | Catch something | 4–24 | none |
| [[Skills/Enchanting Skill\|Enchanting Skill]] | Enchant at a table | = the enchant's level cost | none |
| [[Skills/Brewing Skill\|Brewing Skill]] | A normal brew finishes | 20, shared by everyone within 5 blocks | none |
| [[Skills/Brewing Skill\|Brewing Skill]] | A custom brew finishes | 20 | none |

> [!NOTE]
> Movement XP is scaled to your speed. Faster players need to travel a bit further for the same XP.

---
Related: [[Leveling Plugin\|Leveling Plugin]] · [[Upgrade Trees\|Upgrade Trees]] · [[Skills/Classes\|Classes]] · [[PvP and Death Penalty\|PvP and Death Penalty]]
