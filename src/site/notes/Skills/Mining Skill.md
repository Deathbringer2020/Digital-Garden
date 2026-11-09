---
{"dg-publish":true,"permalink":"/skills/mining-skill/","title":"Mining Skill","tags":["guide","minecraft","leveling","skills","mining","armor","upgrades"],"dg-note-properties":{"title":"Mining Skill","tags":["guide","minecraft","leveling","skills","mining","armor","upgrades"],"aliases":["Mining","Armor Tiers"]}}
---


# Mining Skill

**Menu icon:** Iron pickaxe · **XP curve:** 100, +10 per level

## Earning XP

Mine ores **without Silk Touch**:

| Ore (incl. deepslate) | XP | | Ore | XP |
|---|---|---|---|---|
| Copper | 1 | | Redstone | 6 |
| Coal | 2 | | Lapis | 6 |
| Iron | 4 | | Diamond | 15 |
| Gold | 4 | | Emerald | **50** |
| Nether gold | 1 | | Nether quartz | 1 |

Ancient Debris gives no XP and no luck bonus.

## Upgrade Tree

```mermaid
flowchart TD
    R(["⛏️ MINING<br/>Mining points"]):::root
    R --> MS["Mining Speed<br/>faster with the right tool<br/>2 pts each"]:::up
    R --> ML["Mining Luck<br/>+5% extra-drop chance<br/>1 pt each · no max"]:::up
    R --> A1["Armor Lv 1 · 3 pts<br/>Leather · Chainmail<br/>Copper · Turtle helmet"]:::up
    A1 --> A2["Armor Lv 2 · 5 pts<br/>+ Iron · Gold"]:::up
    A2 --> A3["Armor Lv 3 · 10 pts<br/>+ Diamond"]:::up
    A3 --> A4["Armor Lv 4 · 15 pts<br/>+ Netherite 🏆"]:::cap
    R -. Elytra is in .-> EL["👢 Movement tree"]:::link
    R -.-> X["🚪 Reset<br/>refunds every point"]:::reset

    classDef root fill:#6d28d9,stroke:#4c1d95,color:#ffffff
    classDef up fill:#e0f2fe,stroke:#0284c7,color:#0c4a6e
    classDef cap fill:#fde68a,stroke:#d97706,color:#78350f
    classDef link fill:#dcfce7,stroke:#16a34a,color:#14532d
    classDef reset fill:#e5e7eb,stroke:#6b7280,color:#374151,stroke-dasharray:5 4
```

## Upgrades

| Upgrade | Icon | Effect | Cost | Max |
|---|---|---|---|---|
| Mining Speed | Golden pickaxe | Mine faster with the correct tool | 2 | none |
| Mining Luck | Rabbit's foot | Chance for **extra ore drops** | 1 | none |
| Armor Level | Netherite chestplate | Unlocks the next **armor tier** | 3 / 5 / 10 / 15 | 4 |

### Mining Luck scaling

Each level adds **+5% chance** of 1 extra drop. Every **20 levels** turns into one *guaranteed* extra drop, and the chance starts over:

| Luck level | Extra drops per ore |
|---|---|
| 10 | 50% chance of +1 |
| 20 | +1 guaranteed |
| 30 | +1 guaranteed, 50% chance of +2 |
| 40 | +2 guaranteed |

The extra drop is the ore's normal item (raw iron, diamond, coal, …).

### Armor tiers

> [!IMPORTANT]
> **You can't wear any armor at Armor Level 0.** Anything you equip goes back into your inventory (or drops if it's full).

| Armor Level | Cost | You can wear |
|---|---|---|
| 1 | 3 | Leather, Chainmail, Copper, Turtle helmet |
| 2 | 5 | + Iron, Gold |
| 3 | 10 | + Diamond |
| 4 | 15 | + Netherite |

Full Netherite costs **33 points** in total. The **Elytra** is unlocked in the [[Skills/Movement Skill\|Movement Skill]].

## Reset

The iron door removes Mining Speed, Mining Luck and all armor tiers, and refunds all points.

---
Related: [[Upgrade Trees\|Upgrade Trees]] · [[Skills/Movement Skill\|Movement Skill]] · [[Skills/Defense Skill\|Defense Skill]] · [[Skills and Skill Points\|Skills and Skill Points]]
