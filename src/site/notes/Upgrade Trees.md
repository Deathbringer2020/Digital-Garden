---
{"dg-publish":true,"permalink":"/upgrade-trees/","title":"Upgrade Trees","tags":["guide","minecraft","leveling","upgrades","skills"],"dg-note-properties":{"title":"Upgrade Trees","tags":["guide","minecraft","leveling","upgrades","skills"],"aliases":["Skill Trees","All Upgrades"]}}
---


# Upgrade Trees

Every skill tree on one page. Each tree is pulled live from its skill note, so it's always up to date.

**How to read the trees**

| Box | Meaning |
|---|---|
| 🟣 Purple (rounded) | The skill and its point type |
| 🔵 Blue | A normal upgrade you can buy repeatedly or step by step |
| 🟡 Gold | A big milestone or one-time unlock |
| 🟢 Green (dotted arrow) | Another skill or class that boosts this upgrade |
| ⚪ Grey (dashed) | Reset or a free visual option |
| Solid arrow → | Buy the first one to reach the next |

## Overview

```mermaid
flowchart TD
    P(["🧑 You"]):::root
    P --> CL["🎓 Classes<br/>Tank · Melee · Bare-Handed · Ranged"]:::cap
    P --> CO["⚔️ Combat"]:::up
    P --> DE["🛡️ Defense"]:::up
    P --> MI["⛏️ Mining"]:::up
    P --> IN["🎒 Inventory"]:::up
    P --> MO["👢 Movement"]:::up
    P --> EN["✨ Enchanting"]:::up
    P --> BR["⚗️ Brewing"]:::up
    P --> FA["🌾 Farmer"]:::up
    P --> FI["🎣 Fishing"]:::up
    CO & DE & MI & IN & MO & EN & BR & FA & FI -.-> CP["⭐ every 10 skill levels<br/>= +1 Class point"]:::link
    CP -.-> CL

    classDef root fill:#6d28d9,stroke:#4c1d95,color:#ffffff
    classDef up fill:#e0f2fe,stroke:#0284c7,color:#0c4a6e
    classDef cap fill:#fde68a,stroke:#d97706,color:#78350f
    classDef link fill:#dcfce7,stroke:#16a34a,color:#14532d
```

## 🎓 Classes

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/skills/classes/#upgrade-tree" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Upgrade Tree

```mermaid
flowchart TD
    R(["🎓 CLASSES<br/>Class points"]):::root
    R --> U["Unlock a class<br/>1st: FREE · 2nd: 10 · 3rd: 20 · 4th: 30"]:::cap
    U --> T1["🛡️ Tank<br/>Max HP ×1.20"]:::up
    U --> M1["⚔️ Melee<br/>Damage ×1.20 + life steal"]:::up
    U --> B1["👊 Bare-Handed<br/>Fist damage ×1.25"]:::up
    U --> G1["🏹 Ranged<br/>Projectile damage ×1.20"]:::up
    T1 --> T2["Tank Lv 2, 3, …<br/>+5% max HP · +1% regen<br/>1 pt each · no max"]:::up
    M1 --> M2["Melee Lv 2, 3, …<br/>+5% damage · +1% life steal per 10 Lv<br/>1 pt each · no max"]:::up
    B1 --> B2["Bare-Handed Lv 2, 3, …<br/>+5% fist damage<br/>1 pt each · no max"]:::up
    G1 --> G2["Ranged Lv 2, 3, …<br/>+5% projectile damage<br/>1 pt each · no max"]:::up
    R -.-> X["🚪 Reset<br/>refunds every Class point"]:::reset

    classDef root fill:#6d28d9,stroke:#4c1d95,color:#ffffff
    classDef up fill:#e0f2fe,stroke:#0284c7,color:#0c4a6e
    classDef cap fill:#fde68a,stroke:#d97706,color:#78350f
    classDef reset fill:#e5e7eb,stroke:#6b7280,color:#374151,stroke-dasharray:5 4
```


</div></div>


## ⚔️ Combat

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/skills/combat-skill/#upgrade-tree" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



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


</div></div>


## 🛡️ Defense

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/skills/defense-skill/#upgrade-tree" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



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


</div></div>


## ⛏️ Mining

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/skills/mining-skill/#upgrade-tree" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



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


</div></div>


## 🎒 Inventory

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/skills/inventory-skill/#upgrade-tree" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



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


</div></div>


## 👢 Movement

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/skills/movement-skill/#upgrade-tree" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



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


</div></div>


## ✨ Enchanting

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/skills/enchanting-skill/#upgrade-tree" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Upgrade Tree

```mermaid
flowchart TD
    R(["✨ ENCHANTING<br/>Enchanting points"]):::root
    R --> RV["💀 Revive<br/>cancel one death every 3 h<br/>25 pts · one-time"]:::cap
    R --> DG["🪶 Dodge Chance<br/>+1% to dodge a hit<br/>3 pts each · max 50"]:::up
    R --> XP["🧪 EXP Gain<br/>+5% XP from orbs<br/>1 pt each · max 50"]:::up
    R -.-> X["🚪 Reset<br/>refunds every point"]:::reset

    classDef root fill:#6d28d9,stroke:#4c1d95,color:#ffffff
    classDef up fill:#e0f2fe,stroke:#0284c7,color:#0c4a6e
    classDef cap fill:#fde68a,stroke:#d97706,color:#78350f
    classDef reset fill:#e5e7eb,stroke:#6b7280,color:#374151,stroke-dasharray:5 4
```


</div></div>


## ⚗️ Brewing

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/skills/brewing-skill/#upgrade-tree" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Upgrade Tree

`L` = how many times you've already bought that upgrade.

```mermaid
flowchart TD
    R(["⚗️ BREWING<br/>Brewing points"]):::root
    R --> BT["🔥 Burning Time<br/>−5% burn time<br/>2 pts each · max 20"]:::up
    R --> LV["⬆️ Potion Level<br/>+1 max brewable level"]:::group
    R --> DU["⏱️ Potion Duration<br/>+1 duration doubling"]:::group
    LV --> L1["Speed · Jump Boost<br/>Slowness<br/>3 + L"]:::up
    LV --> L2["Weakness<br/>5 + L"]:::up
    LV --> L3["Regeneration<br/>Strength<br/>8 + L"]:::up
    LV --> L4["Poison<br/>8 + 2L"]:::up
    LV --> L5["Instant Health<br/>5 + 10L"]:::cap
    LV --> L6["Instant Damage<br/>25 + 25L"]:::cap
    DU --> D1["Speed · Jump Boost · Slowness<br/>Night Vision · Fire Resistance<br/>Water Breathing · Slow Falling<br/>Invisibility<br/>2 + L"]:::up
    DU --> D2["Weakness<br/>5 + L"]:::up
    DU --> D3["Regeneration<br/>6 + L"]:::up
    DU --> D4["Strength · Poison<br/>8 + L"]:::up
    R -.-> X["🚪 Reset<br/>refunds every point<br/>clears your positive effects"]:::reset

    classDef root fill:#6d28d9,stroke:#4c1d95,color:#ffffff
    classDef group fill:#ede9fe,stroke:#7c3aed,color:#4c1d95
    classDef up fill:#e0f2fe,stroke:#0284c7,color:#0c4a6e
    classDef cap fill:#fde68a,stroke:#d97706,color:#78350f
    classDef reset fill:#e5e7eb,stroke:#6b7280,color:#374151,stroke-dasharray:5 4
```

### Burning Time

| Upgrade | Icon | Effect | Cost | Max |
|---|---|---|---|---|
| Burning Time | Flint and steel | −5% burn duration per level (you start at **200%**) | 2 | 20 |

10 upgrades = normal burn time. 20 upgrades = you barely burn at all.

### Potion Level ("Can brew potions of level X")

Each upgrade raises the **highest level** of that potion you can **brew and use** by 1. With 0 upgrades your limit is level II; each upgrade adds one more (III, IV, …).

| Potion | Menu icon | Cost of next upgrade |
|---|---|---|
| Speed | Sugar | 3 + L |
| Jump Boost | Rabbit's foot | 3 + L |
| Slowness | Iron block | 3 + L |
| Weakness | Wooden sword | 5 + L |
| Instant Health | Glistering melon | 5 + 10 × L |
| Regeneration | Ghast tear | 8 + L |
| Strength | Blaze powder | 8 + L |
| Poison | Spider eye | 8 + 2 × L |
| Instant Damage | Iron sword | 25 + 25 × L |

### Potion Duration ("Can double the time")

Each upgrade lets you **double** that potion's duration once more (by brewing with redstone) and still use it.

| Potion | Menu icon | Cost of next upgrade |
|---|---|---|
| Speed | Sugar cane | 2 + L |
| Jump Boost | Rabbit hide | 2 + L |
| Slowness | Iron ingot | 2 + L |
| Night Vision | Golden carrot | 2 + L |
| Fire Resistance | Magma cream | 2 + L |
| Water Breathing | Pufferfish | 2 + L |
| Slow Falling | Phantom membrane | 2 + L |
| Invisibility | Glass | 2 + L |
| Weakness | Copper sword | 5 + L |
| Regeneration | Dried ghast | 6 + L |
| Strength | Blaze rod | 8 + L |
| Poison | Fermented spider eye | 8 + L |

> [!IMPORTANT]
> Your upgrades also limit **using** potions. A custom potion above your own level or duration can't be drunk or thrown (`Potion to high level cant drink`). Thrown ones come back to you. A strong potion handed to a low-level friend won't work for them!


</div></div>


## 🌾 Farmer

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/skills/farming-skill/#upgrade-tree" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Upgrade Tree

```mermaid
flowchart TD
    R(["🌾 FARMER<br/>Farmer points"]):::root
    R --> FL["Farming Luck<br/>+5% extra crop chance<br/>1 pt each · no max"]:::up
    R --> WP["🐺 Wolf Pets"]:::group
    WP --> WA["Wolf Amount<br/>+1 buffed wolf (1 free)<br/>10 pts each · max 10"]:::cap
    WP --> WD["Wolf Damage<br/>+1 attack damage<br/>4 pts each · no max"]:::up
    WP --> WH["Wolf Health<br/>+1 max HP<br/>1 pt each · no max"]:::up
    WD -. applies to .-> W["Your buffed wolves<br/>base: 8 HP · 6 damage"]:::link
    WH -. applies to .-> W
    R -.-> X["🚪 Reset<br/>refunds every point"]:::reset

    classDef root fill:#6d28d9,stroke:#4c1d95,color:#ffffff
    classDef group fill:#ede9fe,stroke:#7c3aed,color:#4c1d95
    classDef up fill:#e0f2fe,stroke:#0284c7,color:#0c4a6e
    classDef cap fill:#fde68a,stroke:#d97706,color:#78350f
    classDef link fill:#dcfce7,stroke:#16a34a,color:#14532d
    classDef reset fill:#e5e7eb,stroke:#6b7280,color:#374151,stroke-dasharray:5 4
```


</div></div>


## 🎣 Fishing

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/skills/fishing-skill/#upgrade-tree" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Upgrade Tree

```mermaid
flowchart TD
    R(["🎣 FISHING<br/>Fishing points"]):::root
    R --> FL["Fishing Luck<br/>+5% extra catch chance<br/>1 pt each · no max"]:::up
    R --> UW["🌊 Underwater"]:::group
    UW --> OX["Oxygen Bonus<br/>air lasts longer<br/>3 pts each · no max"]:::up
    UW --> SM["Submerged Mining Speed<br/>mine faster underwater<br/>3 pts each"]:::up
    R -.-> X["🚪 Reset<br/>refunds every point"]:::reset

    classDef root fill:#6d28d9,stroke:#4c1d95,color:#ffffff
    classDef group fill:#ede9fe,stroke:#7c3aed,color:#4c1d95
    classDef up fill:#e0f2fe,stroke:#0284c7,color:#0c4a6e
    classDef reset fill:#e5e7eb,stroke:#6b7280,color:#374151,stroke-dasharray:5 4
```


</div></div>


---
Related: [[Leveling Plugin\|Leveling Plugin]] · [[Skills and Skill Points\|Skills and Skill Points]] · [[Beginner Guide\|Beginner Guide]]
