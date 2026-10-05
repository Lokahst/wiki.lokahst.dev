---
title: Commands and Permissions
description: Commands and permission nodes
updated: October 5, 2026
---


## Commands

| Command | Purpose | Permission | Console |
|---|---|---|---|
| /lotn | Opens the player menu; also supports the subcommands below | `lotn.use` plus any required admin node | Depends on the action |
| /lotnea | Opens Extended Administration | lotn.admin | Player only |

### `/lotn` subcommands

Player actions: `/lotn help`, `/lotn menu`, `/lotn level`, `/lotn character`, `/lotn skills`, `/lotn quests`, `/lotn codex`, `/lotn shouts`, `/lotn alchemy`, `/lotn travel`, and `/lotn enchantments`. `/lotn level` shows LOTN progression XP; Minecraft XP stays separate.

Administrator actions:

| Command | Arguments |
|---|---|
| `/lotn reload` | None |
| `/lotn inspectmob` | None |
| `/lotn voiceknowledge` | `<get / add / remove / set> <player> [amount]` |
| `/lotn legendaryadmin` | `<player> <skill> [inspect / advance / set] [rank]` |
| `/lotn legacyadmin` | `<player> <enter / rollback / status>` |
| `/lotn questadmin` | `<player> <inspect / complete / reset> [quest]` |
| `/lotn bosscontribution` | `<boss-uuid>` |

Use `/lotn help` for the player command list and available administrator commands. Its usage text does not show every administrator argument; see the syntax above.

## Permissions

| Permission | Purpose | Default |
|---|---|---|
| `lotn.admin` | Grants `lotn.use` and the administrator permissions | op |
| `lotn.use` | Allows access to LotN commands and menus | True |
| `lotn.progress.skills` | Allows skill progression | True |
| `lotn.progress.quests` | Allows quest progress and rewards | True |
| `lotn.progress.discovery` | Allows discovery progress and rewards | True |
| `lotn.bypass.survival` | Bypasses LotN survival penalties | False |
| `lotn.alchemy` | Allows use of the Alchemy system | True |
| `lotn.admin.character` | Character administration | op |
| `lotn.admin.breakleg`, `lotn.admin.healleg` | Broken-leg administration | op |
| `lotn.admin.skills`, `lotn.admin.vitals` | Skill and vitality administration | op |
| `lotn.admin.enchants`, `lotn.admin.alchemy`, `lotn.admin.fishing`, `lotn.admin.shouts` | Enchantment, Alchemy, fishing, and shout administration | op |
| `lotn.admin.inspectmob`, `lotn.admin.voiceknowledge` | Mob inspection and shout-word administration | op |
| `lotn.admin.legendary`, `lotn.admin.legacy`, `lotn.admin.quests` | Progression, legacy, and quest administration | op |
| `lotn.admin.settings`, `lotn.admin.reload`, `lotn.admin.reset` | Settings, reload, and reset actions | op |

Every `/lotn` action requires `lotn.use`; granting an individual `lotn.admin.*` permission alone is not enough. `/lotnea` is player-only and requires `lotn.admin`. Administrator permissions are listed above.

`help`, `reload`, and commands that operate on online players can be run from the console. Player menus and `inspectmob` require an in-game player; mob inspection also requires a target within 12 blocks.
