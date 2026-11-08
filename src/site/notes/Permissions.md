---
{"dg-publish":true,"permalink":"/permissions/","title":"Permissions","tags":["admin","minecraft","leveling","permissions","plugin"],"dg-note-properties":{"title":"Permissions","tags":["admin","minecraft","leveling","permissions","plugin"],"aliases":["Rechte","Permission Nodes"]}}
---


# Permissions

The plugin uses **no custom permission nodes**. Access works like this:

| Who | Can use |
|---|---|
| Every player | `/menu` and everything inside it (buying, resetting, Health Scaling) |
| Server operators (`/op <name>`) | `/menuothers`, `/setlevel` |

To give a moderator the admin commands, they must be **OP**. Permission plugins like LuckPerms can't grant these commands on their own, because the plugin checks for OP status directly.

> [!NOTE]
> The plugin's `plugin.yml` (which may define command aliases or default permissions) wasn't part of the files this documentation was based on. Check it if you see behaviour that doesn't match this page.

---
Related: [[Commands\|Commands]] · [[Configuration\|Configuration]]
