---
{"dg-publish":true,"permalink":"/configuration/","title":"Configuration","tags":["admin","minecraft","leveling","config","plugin"],"dg-note-properties":{"title":"Configuration","tags":["admin","minecraft","leveling","config","plugin"],"aliases":["Config","Server Setup","Balancing Values"]}}
---


# Configuration

## Is there a config file?

**No.** The plugin has no editable settings. Every value on this page is **built in**. To change them, the plugin has to be rebuilt.

## Data & files

| What | Where | Notes |
|---|---|---|
| Skill levels, XP, spent points, upgrades, locked slots | Saved with each **player's own data** (the world's player data) | Survives restarts; deleting a player's data resets their progress |
| Buffed wolves | `plugins/Leveling/pets.yml` | A list of wolf IDs per player ID. Starts empty and fills itself |
| Mob-kill, crafting and pickup caps; Revive cooldown | Memory only | Reset on every server restart |

## Scoreboards created by the plugin

| Objective | Shown | Purpose |
|---|---|---|
| `combat_Level` | Below player names ("Combat Level") | Displays each player's Combat level |
| `walking` / `sprinting` | Hidden | Counts walked/sprinted distance for [[Skills/Movement Skill\|Movement Skill]] XP; reset every 5 s |

> [!WARNING]
> Don't delete these objectives or reuse the below-name slot for another plugin. That breaks the Combat Level display or Movement XP.

## Built-in balancing values

### XP curves

| Skill | First level | Added per level |
|---|---|---|
| Combat | 100 | +25 |
| Movement | 500 | +20 |
| All other skills | 100 | +10 |
| Classes | 10 | +0 |

### XP caps

| Source | Reward | Cap | Window |
|---|---|---|---|
| Monster kill | 5 XP → 1 XP after 60 kills | 1,000 kills | 10 min |
| Crafting | 15 XP | 20 crafts | 20 min |
| Item pickup | 5 XP | 64 pickups | 20 min |
| Movement | ≈0.5 XP/block at base speed | soft cap 10 XP per 5 s | 5 s |

### Timers

| Feature | Interval |
|---|---|
| Max-HP regeneration & Movement XP check | every 5 s |
| Revive cooldown | 3 h |
| Custom brew time | 20 s × potion level |

### First-join stats

See [[Starting Stats\|Starting Stats]].

---
Related: [[Commands\|Commands]] · [[Permissions\|Permissions]] · [[Known Issues\|Known Issues]] · [[Skills and Skill Points\|Skills and Skill Points]]
