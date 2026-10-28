---
title: Commands and Permissions
description: Commands and permission nodes
updated: October 28, 2026
---

## Commands

| Command | Purpose | Permission | Console |
|---|---|---|---|
| `/lotn` | Opens the player menu; supports the player shortcuts below | `lotn.use` | Player only |
| `/lotn help` | Shows command usage | `lotn.use` | Yes |
| `/lotn reload` | Reloads LOTN configuration and supported systems | `lotn.use` and `lotn.admin.reload` | Yes |
| `/lotn menu` | Opens the player menu | `lotn.use` | Player only |
| `/lotn level` | Shows LOTN level and XP, separate from Minecraft XP | `lotn.use` | Player only |
| `/lotn character` | Opens character information | `lotn.use` | Player only |
| `/lotn skills` | Opens Skills | `lotn.use` | Player only |
| `/lotn quests` | Opens the Quest Journal | `lotn.use` | Player only |
| `/lotn codex` | Opens the Codex | `lotn.use` | Player only |
| `/lotn shouts` | Opens Shouts | `lotn.use` | Player only |
| `/lotn alchemy` | Opens Alchemy | `lotn.use` | Player only |
| `/lotn travel` | Opens Fast Travel | `lotn.use` | Player only |
| `/lotn enchantments` | Opens Enchantments | `lotn.use` | Player only |
| `/lotnea` | Opens Extended Administration | `lotn.admin` | Player only |

Except for `help` and `reload`, `/lotn` actions require an in-game player with a completed character. If character setup is incomplete, LOTN opens the setup menu. `/lotnea` takes no arguments.

Staff management actions are available from the `/lotnea` menu; the only administrator subcommand under `/lotn` is `reload`. Use `/lotn help` for the usage text.

## Permissions

| Permission | Purpose | Default |
|---|---|---|
| `lotn.admin` | Opens `/lotnea`; grants `lotn.use` and all `lotn.admin.*` permissions below | op |
| `lotn.use` | Allows LOTN commands and player menus | true |
| `lotn.progress.skills` | Allows skill progression | true |
| `lotn.progress.quests` | Allows quest progress and rewards | true |
| `lotn.progress.discovery` | Allows discovery progress and rewards | true |
| `lotn.alchemy` | Allows use of Alchemy | true |
| `lotn.bypass.survival` | Bypasses LOTN survival penalties | false |
| `lotn.admin.character` | Character administration | op |
| `lotn.admin.skills`, `lotn.admin.vitals` | Skill and vitality administration | op |
| `lotn.admin.breakleg`, `lotn.admin.healleg` | Broken-leg administration | op |
| `lotn.admin.enchants`, `lotn.admin.alchemy`, `lotn.admin.fishing`, `lotn.admin.shouts` | Enchantment, Alchemy, fishing, and shout administration | op |
| `lotn.admin.voiceknowledge`, `lotn.admin.discoveries` | Voice Knowledge and discovery administration | op |
| `lotn.admin.legendary`, `lotn.admin.legacy`, `lotn.admin.quests` | Legendary skills, Legacy, and quest administration | op |
| `lotn.admin.settings`, `lotn.admin.reload`, `lotn.admin.reset` | Settings, reload, and reset actions | op |
| `lotn.admin.diagnostics` | LOTN diagnostics | op |

Every `/lotn` command requires `lotn.use`; granting an individual `lotn.admin.*` permission alone is not enough. `/lotnea` is player-only and requires `lotn.admin`. The `help` and `reload` actions can be run from the console; other `/lotn` actions require a player.
