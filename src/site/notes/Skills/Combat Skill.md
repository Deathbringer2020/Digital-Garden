---
{"dg-publish":true,"permalink":"/skills/combat-skill/","title":"Combat Skill","tags":["guide","minecraft","leveling","skills","combat","pvp","upgrades"],"dg-note-properties":{"title":"Combat Skill","tags":["guide","minecraft","leveling","skills","combat","pvp","upgrades"],"aliases":["Combat"]}}
---


# Combat Skill

**Menu icon:** Iron sword · **XP curve:** 100, +25 per level (the steepest skill)

Your Combat level is shown **under your name tag** for everyone to see.

## Earning XP

- **Hostile monster kill:** 5 XP (zombies, skeletons, creepers, spiders, endermen, …; slimes, ghasts and phantoms don't count).
  - Your first kill starts a **10-minute window**. Kills 1–60 give 5 XP, kills 61–1,000 give 1 XP, after that nothing until the window ends.
- **Player kill:** big rewards, but you can also lose XP. See [[PvP and Death Penalty\|PvP and Death Penalty]].

## Upgrade Tree

```mermaid
flowchart TD
    R(["⚔️ COMBAT<br/>Combat points"]):::root
    R --> AD["Attack Damage<br/>+1 base damage<br/>4 pts each · no max"]:::up
    R --> AS["Attack Speed<br/>+0.1 attack speed<br/>3 pts each · no max"]:::up
    R --> KB["Knockback<br/>+0.5 knockback<br/>2 pts each · max 10"]:::up
    R --> BD["Bow Damage<br/>+1 arrow damage<br/>3 pts each · no max"]:::up
    R --> FD["Bare-Handed Damage<br/>+1 fist damage<br/>3 pts each · no max"]:::up
    AD -. multiplied by .-> MC["⚔️ Melee class"]:::link
    BD -. multiplied by .-> RC["🏹 Ranged class"]:::link
    FD -. multiplied by .-> BC["👊 Bare-Handed class"]:::link
    R -.-> X["🚪 Reset<br/>refunds every point"]:::reset

    classDef root fill:#6d28d9,stroke:#4c1d95,color:#ffffff
    classDef up fill:#e0f2fe,stroke:#0284c7,color:#0c4a6e
    classDef link fill:#dcfce7,stroke:#16a34a,color:#14532d
    classDef reset fill:#e5e7eb,stroke:#6b7280,color:#374151,stroke-dasharray:5 4
```

## Upgrades

| Upgrade | Icon | Effect per upgrade | Cost | Max |
|---|---|---|---|---|
| Attack Damage | Diamond sword | +1 base attack damage (start: 1) | 4 | none |
| Attack Speed | Golden sword | +0.1 attack speed (start: 3.1) | 3 | none |
| Knockback | Stick | +0.5 attack knockback | 2 | 10 |
| Bow Damage | Bow | +1 damage on every arrow you shoot | 3 | none |
| Bare-Handed Damage | Oak fence | +1 damage when your main hand is empty | 3 | none |

> [!TIP]
> Attack Damage boosts every melee weapon *and* your fist. Bow and Bare-Handed Damage get multiplied by the matching [[Skills/Classes\|Classes]].

## Reset

The iron door sets attack damage back to 1, attack speed to 3.1, knockback to 0 and refunds all points.

If you lost Combat levels and your points are negative, `/menu` opens **"Remove Combat Upgrades"** instead. See [[PvP and Death Penalty\|PvP and Death Penalty]].

---
Related: [[Upgrade Trees\|Upgrade Trees]] · [[Skills/Classes\|Classes]] · [[PvP and Death Penalty\|PvP and Death Penalty]] · [[Skills and Skill Points\|Skills and Skill Points]]
