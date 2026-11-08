---
{"dg-publish":true,"permalink":"/custom-potion-brewing/","title":"Custom Potion Brewing","tags":["guide","minecraft","leveling","brewing","potions"],"dg-note-properties":{"title":"Custom Potion Brewing","tags":["guide","minecraft","leveling","brewing","potions"],"aliases":["Custom Brewing","Potion Upgrades"]}}
---


# Custom Potion Brewing

Vanilla potions stop at level II. With the [[Skills/Brewing Skill\|Brewing Skill]] you can brew **higher levels** (Speed III, Strength IV, …) and **longer durations** in a normal brewing stand. Custom brews run on a timer, use **XP levels** as a cost, and need **unlocked upgrades**.

## What you need

1. **Three identical potions** in all three bottle slots: same form (drinkable, splash or lingering), same effect, same level, same duration. Water, Awkward, Thick and Mundane potions don't work.
2. The right **ingredient** in the top slot, in a large enough stack (see below).
3. Enough **vanilla XP levels** (your green XP bar).
4. The matching **Brewing upgrade** in `/menu`.

Fuel isn't used by custom brews. As soon as everything is in place you'll see **`Started Brewing`**. When it's done: **`Finished Brewing`**, the three bottles are replaced, the ingredients and XP levels are taken, and you get 20 Brewing XP. If you take out the ingredient or change the potions mid-brew, you'll see **`Stopped Brewing`**.

> [!WARNING]
> Requirements are checked again when the brew **finishes**. If you spent your XP levels or the ingredient stack got too small in the meantime, the brew silently fails.

## Raising the level

| Ingredient | Potion |
|---|---|
| Sugar | Speed |
| Rabbit's foot | Jump Boost |
| Blaze powder | Strength |
| Glistering melon slice | Instant Health |
| Ghast tear | Regeneration |
| Spider eye | Poison |
| Fermented spider eye | Weakness, Instant Damage *or* Slowness (whichever potion is in the bottles) |

**From level N to level N+1 costs:**

| | Formula | Example: II → III | III → IV | IV → V |
|---|---|---|---|---|
| Ingredients | N + 1 | 3 | 4 | 5 |
| XP levels | 2 × (N + 1) | 6 | 8 | 10 |
| Brew time | N × 20 s | 40 s | 60 s | 80 s |
| Upgrade needed | Level upgrade ≥ N − 1 | 1 | 2 | 3 |

**Each level step halves the duration.** On the first custom step (from vanilla II) the potion gets a fixed new duration:

| Potion | Level III duration (drinkable/splash) | Lingering |
|---|---|---|
| Speed, Jump Boost, Strength | 32 s | 8 s |
| Regeneration, Poison | 8 s | 2 s |
| Weakness (I → II, start from the *long* 4:00 Weakness) | 64 s | 16 s |
| Instant Health / Damage | instant | instant |

Slowness starts from vanilla **Slowness IV**.

## Doubling the duration (Redstone)

Put **redstone** in the top slot to **double the duration** while keeping the level.

- Works on custom potions (level III and up) of Speed, Jump Boost, Strength, Regeneration, Poison, Slowness and Weakness.
- Works on the **long (8:00)** vanilla Night Vision, Fire Resistance, Water Breathing, Slow Falling and Invisibility. The 3:00 versions are rejected.
- Each doubling counts as one **duration step**. Higher steps (and higher potion levels) need more redstone, more XP levels (2 per step) and 20 s more brewing time, plus the matching **Duration upgrade**.

## Who can use custom potions?

Only players with **enough Brewing upgrades themselves**. If a custom potion's level or duration is above your own upgrades, drinking it is blocked and thrown splash/lingering potions bounce back into your inventory:

> `Potion to high level cant drink`

Vanilla potions (Speed II, Fire Resistance 8:00, …) can always be used by everyone.

---
Related: [[Skills/Brewing Skill\|Brewing Skill]] · [[Skills/Defense Skill\|Defense Skill]] · [[Known Issues\|Known Issues]]
