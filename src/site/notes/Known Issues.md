---
{"dg-publish":true,"permalink":"/known-issues/","title":"Known Issues","tags":["admin","minecraft","leveling","bugs","plugin"],"dg-note-properties":{"title":"Known Issues","tags":["admin","minecraft","leveling","bugs","plugin"],"aliases":["Bugs","Work in Progress"]}}
---


# Known Issues

Gameplay behaviour found while documenting the plugin that doesn't match the tooltips, or that admins should know about. Worth telling players about until it's fixed.

## Upgrades that don't work as described

| Where                                      | What happens                                                                                                                                                             |
| ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [[Skills/Mining Skill\|Mining Skill]] → Mining Speed            | Only the **first two** purchases increase mining speed. Further purchases still cost 2 points but do nothing. Resetting Mining sets the stat *below* its starting value. |
| [[Skills/Fishing Skill\|Fishing Skill]] → Submerged Mining Speed | Purchases cost points but **don't increase** the stat.                                                                                                                   |
| [[Skills/Classes\|Classes]] → Bare-Handed                  | Tooltip promises an attack-speed bonus. Only the damage multiplier works.                                                                                                |
| [[Skills/Classes\|Classes]] → Ranged                       | Tooltip promises stronger potion effects on arrows. Only the damage multiplier works.                                                                                    |
| [[Skills/Classes\|Classes]] → Tank                         | Level 1 and level 2 give the same health multiplier (×1.25).                                                                                                             |
| [[Skills/Defense Skill\|Defense Skill]] → Knockback Resistance   | Tooltip shows `/5`, but 2 upgrades already reach 100%; more are wasted points.                                                                                           |
| [[Skills/Defense Skill\|Defense Skill]] → Regeneration Potion    | Tooltip says +0.1 per upgrade; the real bonus is +0.05.                                                                                                                  |
| [[Skills/Farming Skill\|Farming Skill]] → Farming Luck           | Tooltip says "0.5 Farming Luck"; it actually works like Mining Luck (+5% per level).                                                                                     |
| [[Skills/Inventory Skill\|Inventory Skill]] → Unlock Slot          | Clicking it again after **27/27** (costs 24 points) **deletes the item in the last hotbar slot**.                                                                        |

## Other behaviour

- **Trading** and **Building** skills exist (`/setlevel`) but have no menu and no XP source.
- **Remove Classes Upgrades** screen may show wrong labels on classes you haven't unlocked.
- A custom brew that fails its final check (for example you spent your XP levels while it ran) gives no message. Take the ingredient out and put it back in to restart. See [[Custom Potion Brewing\|Custom Potion Brewing]].
- **Buffed wolves** start with only 8 HP, much less than a vanilla tamed wolf. If a buffed wolf dies while its owner is **offline**, it stays counted against the owner's wolf limit. See [[Skills/Farming Skill\|Farming Skill]].
- `/menuothers` doesn't lock the icons, so an admin can take the display items (iron sword, shield, …) out of it.
- `/menuothers` or `/setlevel` with an offline/misspelled name prints `Invalid Player` and then an error in the console.
- XP caps and the Revive cooldown reset on server restart. See [[Configuration\|Configuration]].
- Commands named `resetUpgrades` / `resetUpgradesAll` appear in the code but do nothing yet.

---
Related: [[Configuration\|Configuration]] · [[Commands\|Commands]] · [[Leveling Plugin\|Leveling Plugin]]
