---
{"dg-publish":true,"permalink":"/skills/movement-skill/","title":"Movement Skill","tags":["guide","minecraft","leveling","skills","movement","upgrades"],"dg-note-properties":{"title":"Movement Skill","tags":["guide","minecraft","leveling","skills","movement","upgrades"],"aliases":["Movement","Elytra Unlock"]}}
---


# Movement Skill

**Menu icon:** Leather boots · **XP curve:** 500, +20 per level (the slowest skill to level)

## Earning XP

Every 5 seconds the game counts how far you **walked and sprinted**. Swimming, flying, riding and gliding don't count.

- At starting speed you get about **1 XP per 2 blocks**.
- XP is scaled to your speed, so faster players need to travel a bit further for the same XP.
- Up to 10 XP per 5 seconds counts in full. Anything above that counts only 1/10.

## Upgrade Tree

```mermaid
flowchart TD
    R(["👢 MOVEMENT<br/>Movement points"]):::root
    R --> S1["Base Movement Speed<br/>Lv 1–5 · +0.01 speed<br/>5 pts each"]:::up
    S1 --> V["✅ Normal walking speed<br/>reached at Lv 5"]:::group
    V --> S6["Advanced Movement Speed<br/>Lv 6+ · +0.01 speed<br/>8 pts each · no max"]:::cap
    R --> EL["🪽 Elytra Unlock<br/>wear an Elytra<br/>25 pts · one-time"]:::cap
    R -.-> X["🚪 Reset<br/>refunds every point"]:::reset

    classDef root fill:#6d28d9,stroke:#4c1d95,color:#ffffff
    classDef group fill:#ede9fe,stroke:#7c3aed,color:#4c1d95
    classDef up fill:#e0f2fe,stroke:#0284c7,color:#0c4a6e
    classDef cap fill:#fde68a,stroke:#d97706,color:#78350f
    classDef reset fill:#e5e7eb,stroke:#6b7280,color:#374151,stroke-dasharray:5 4
```

## Upgrades

| Upgrade | Icon | Effect | Cost | Max |
|---|---|---|---|---|
| Base Movement Speed | Golden boots | +0.01 walking speed (start 0.05, normal 0.10) | **5** for the first 5, then **8** each | none |
| Elytra Unlock | Elytra | Lets you equip an Elytra | 25 | one-time |

- 5 speed upgrades (25 points) bring you back to **normal speed**.
- Every upgrade after that makes you **faster than normal**.
- Without the Elytra Unlock, an Elytra in your chest slot goes straight back into your inventory.

## Reset

The iron door sets your speed back to 0.05, re-locks the Elytra and refunds all points.

---
Related: [[Upgrade Trees\|Upgrade Trees]] · [[Skills/Mining Skill\|Mining Skill]] · [[Starting Stats\|Starting Stats]] · [[Skills and Skill Points\|Skills and Skill Points]]
