---
{"dg-publish":true,"permalink":"/skills/defense-skill/","title":"Defense Skill","tags":["guide","minecraft","leveling","skills","defense","upgrades"],"dg-note-properties":{"title":"Defense Skill","tags":["guide","minecraft","leveling","skills","defense","upgrades"],"aliases":["Defense"]}}
---


# Defense Skill

**Menu icon:** Shield · **XP curve:** 100, +10 per level

## Earning XP

You get **1 XP for every half-heart you heal** (rounded): eating, natural regeneration, Regeneration potions, beacons, golden apples, totems, instant health.

> [!TIP]
> Natural regeneration heals in tiny steps that often round to 0 XP. Big heals (potions, golden apples) level Defense much faster.

## Upgrade Tree

```mermaid
flowchart TD
    R(["🛡️ DEFENSE<br/>Defense points"]):::root
    R --> SURV["Survivability"]:::group
    R --> REG["Regeneration"]:::group
    SURV --> HP["Base Health<br/>+1 max HP (½ ❤)<br/>2 pts each · no max"]:::up
    SURV --> AR["Armor<br/>+1 armor point<br/>3 pts each · max 10"]:::up
    SURV --> AT["Armor Toughness<br/>+1 toughness<br/>3 pts each · max 10"]:::up
    SURV --> KR["Knockback Resistance<br/>+50%<br/>5 pts each · 2 = immune"]:::cap
    REG --> RF["Regeneration Food<br/>25% → +5% each<br/>3 pts each · no max"]:::up
    REG --> RP["Regeneration Potion<br/>25% → +5% each<br/>3 pts each · no max"]:::up
    REG --> MR["Regen Max HP<br/>heal 0.5% max HP / 5 s<br/>5 pts each · max 20"]:::cap
    HP -. multiplied by .-> TK["🛡️ Tank class"]:::link
    RF -. boosted by .-> TK
    RP -. boosted by .-> TK
    R -.-> HS["Health Scaling<br/>visual only · free"]:::reset
    R -.-> X["🚪 Reset<br/>refunds every point"]:::reset

    classDef root fill:#6d28d9,stroke:#4c1d95,color:#ffffff
    classDef group fill:#ede9fe,stroke:#7c3aed,color:#4c1d95
    classDef up fill:#e0f2fe,stroke:#0284c7,color:#0c4a6e
    classDef cap fill:#fde68a,stroke:#d97706,color:#78350f
    classDef link fill:#dcfce7,stroke:#16a34a,color:#14532d
    classDef reset fill:#e5e7eb,stroke:#6b7280,color:#374151,stroke-dasharray:5 4
```

## Upgrades

| Upgrade | Icon | Effect per upgrade | Cost | Max |
|---|---|---|---|---|
| Base Health | Apple | +1 max HP (half a heart). Start: 10 HP | 2 | none |
| Armor | Iron chestplate | +1 armor point (works even without armor) | 3 | 10 |
| Armor Toughness | Netherite chestplate | +1 armor toughness | 3 | 10 |
| Knockback Resistance | Stick | +50% knockback resistance | 5 | 2 upgrades = full immunity |
| Regeneration Food | Cooked beef | Food-based healing: starts at 25%, +5% per upgrade | 3 | none (normal speed at 15) |
| Regeneration Potion | Potion | Regeneration-effect healing: starts at 25%, +5% per upgrade | 3 | none |
| Regen Max HP | Golden chestplate | Heals **0.5% of your max HP every 5 seconds** per upgrade | 5 | 20 (= 10% per 5 s) |
| Health Scaling | Lime glazed terracotta | **Visual only.** Left-click +20, right-click −20; lowest setting = off | free | n/a |

> [!TIP]
> The **Tank** class multiplies your max health and boosts both regeneration upgrades. See [[Skills/Classes\|Classes]].
> Regeneration above level VI gets a small extra boost, so very strong potions still pay off. See [[Custom Potion Brewing\|Custom Potion Brewing]].

## Reset

The iron door resets max HP to 10, armor, toughness, knockback resistance and all regeneration upgrades to 0, and refunds all points.

---
Related: [[Upgrade Trees\|Upgrade Trees]] · [[Skills/Classes\|Classes]] · [[Starting Stats\|Starting Stats]] · [[Skills and Skill Points\|Skills and Skill Points]]
