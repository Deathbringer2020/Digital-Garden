---
{"dg-publish":true,"permalink":"/commands/","title":"Commands","tags":["admin","minecraft","leveling","commands","plugin"],"dg-note-properties":{"title":"Commands","tags":["admin","minecraft","leveling","commands","plugin"],"aliases":["Befehlsübersicht","Command Overview"]}}
---


# Commands

| Command | Permission | Description & Syntax | Example |
|---|---|---|---|
| `/menu` | Everyone | Opens your **Leveling** menu: all skills with level and XP. Left-click a skill to open its upgrade tree. If you're in skill debt, it opens the "Remove … Upgrades" screen instead. See [[PvP and Death Penalty\|PvP and Death Penalty]]. Syntax: `/menu` | `/menu` |
| `/menuothers` | OP | Opens a **read-only overview** of another online player's levels and XP. Syntax: `/menuothers <player>` | `/menuothers Alex` |
| `/setlevel` | OP | Sets a player's **level** (and optionally current **XP**) in one skill. XP is set to 0 if left out. Syntax: `/setlevel <player> <skill> <level> [xp]` | `/setlevel Alex combat 10` · `/setlevel Alex mining 15 40` |

## Skill names for `/setlevel`

Lower case, exactly as written:

| Name | Skill |
|---|---|
| `classes` or `cl` | [[Skills/Classes\|Classes]] |
| `combat` | [[Skills/Combat Skill\|Combat Skill]] |
| `defense` | [[Skills/Defense Skill\|Defense Skill]] |
| `inventory` | [[Skills/Inventory Skill\|Inventory Skill]] |
| `movement` | [[Skills/Movement Skill\|Movement Skill]] |
| `mining` | [[Skills/Mining Skill\|Mining Skill]] |
| `enchanting` | [[Skills/Enchanting Skill\|Enchanting Skill]] |
| `brewing` | [[Skills/Brewing Skill\|Brewing Skill]] |
| `farming` | [[Skills/Farming Skill\|Farming Skill]] |
| `fishing` | [[Skills/Fishing Skill\|Fishing Skill]] |
| `traiding` (sic) | Trading (hidden, no gameplay yet) |
| `building` | Building (hidden, no gameplay yet) |

## Feedback messages

| Message | Meaning |
|---|---|
| `Have to be OP` | You're not an operator |
| `No Player given` | Player name missing |
| `Invalid Player` | Player not online or misspelled |
| `Invalid Arguments` | Fewer than 3 arguments for `/setlevel` |
| `not found` | Unknown skill name |
| `To meany Arguments` | More than 4 arguments |

> [!WARNING]
> - `/setlevel` does **not** refund points already spent. If you lower a level below the points a player has spent, they're in debt. For Combat/Classes that triggers the frozen state on their next respawn.
> - The Combat Level under the name tag updates the next time the player earns or loses Combat XP.
> - Admin commands only work in-game, not from the server console.

---
Related: [[Permissions\|Permissions]] · [[Configuration\|Configuration]] · [[Leveling Plugin\|Leveling Plugin]]
