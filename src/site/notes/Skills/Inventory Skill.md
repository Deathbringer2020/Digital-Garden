---
{"dg-publish":true,"permalink":"/skills/inventory-skill/","title":"Inventory Skill","tags":["guide","minecraft","leveling","skills","inventory","upgrades"],"dg-note-properties":{"title":"Inventory Skill","tags":["guide","minecraft","leveling","skills","inventory","upgrades"],"aliases":["Inventory","Slot Unlocks"]}}
---


# Inventory Skill

**Menu icon:** Chest · **XP curve:** 100, +10 per level

At the start only your **hotbar** works. The other 27 slots hold red **"Slot Locked"** barriers. You can't move them, they don't drop when you die, and they come back when you respawn.

## Earning XP

| Action | XP | Limit |
|---|---|---|
| Craft (each craft; a shift-click counts once) | 15 | 20 per 20 minutes |
| Pick up an item (each pickup, any stack size) | 5 | 64 per 20 minutes |

## Upgrade Tree

Click the **barrier** icon to unlock **one slot** at a time. Slots open from the bottom-right of your inventory upward. The tooltip shows your progress (`x/27`) and the next price.

```mermaid
flowchart TD
    R(["🎒 INVENTORY<br/>Inventory points"]):::root
    R --> S1["Slot 1<br/>FREE"]:::cap
    S1 --> S2["Slots 2–3<br/>1 pt each"]:::up
    S2 --> S4["Slots 4–5<br/>2 pts each"]:::up
    S4 --> S6["Slots 6–7<br/>3 pts each"]:::up
    S6 --> S8["Slots 8–9<br/>4 pts each"]:::up
    S8 --> ROW["✅ First row done<br/>20 pts total"]:::group
    ROW --> S10["Slot 10<br/>6 pts"]:::up
    S10 --> S11["Slots 11–26<br/>7 → 22 pts<br/>+1 pt per slot"]:::up
    S11 --> S27["Slot 27<br/>23 pts<br/>🏆 Full inventory · 281 pts total"]:::cap
    R -.-> X["🚪 Reset<br/>re-locks all slots<br/>drops their items"]:::reset

    classDef root fill:#6d28d9,stroke:#4c1d95,color:#ffffff
    classDef group fill:#ede9fe,stroke:#7c3aed,color:#4c1d95
    classDef up fill:#e0f2fe,stroke:#0284c7,color:#0c4a6e
    classDef cap fill:#fde68a,stroke:#d97706,color:#78350f
    classDef reset fill:#e5e7eb,stroke:#6b7280,color:#374151,stroke-dasharray:5 4
```

| Unlock # | Cost | | Unlock # | Cost |
|---|---|---|---|---|
| 1 | **0 (free)** | | 10 | 6 |
| 2–3 | 1 each | | 11 | 7 |
| 4–5 | 2 each | | 12 | 8 |
| 6–7 | 3 each | | … | +1 each |
| 8–9 | 4 each | | 27 | 23 |

## Reset

Resetting locks all 27 slots again and **drops everything in them on the ground**. Put your items in a chest first.

---
Related: [[Upgrade Trees\|Upgrade Trees]] · [[Beginner Guide\|Beginner Guide]] · [[Starting Stats\|Starting Stats]] · [[Skills and Skill Points\|Skills and Skill Points]]
