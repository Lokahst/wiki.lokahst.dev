---
title: Extended Administration
description: Tools available in /lotnea
updated: October 5, 2026
---


`/lotnea` opens the admin menu. It requires `lotn.admin` and cannot be used from the console. The menu's administration sections check their corresponding `lotn.admin.*` permissions.

## Target Player

The menu targets the administrator by default. Use the target selector to choose another online player; the other controls then edit the selected player's data.

## Character

- Change race
- Open the anvil name editor to rename the character
- Reset the character name to the Minecraft username

## Skills

- Inspect every skill
- Add 1 level, add 10 levels, or set one skill to its maximum
- Max every skill, reset one skill, or reset every skill
- Manage skill rewards

## Vitals and Injuries

- Heal Health, Stamina, and Magicka
- Add 1 or 10 vitality choices, or set the pending pool to 1,000
- Apply Health, Stamina, or Magicka upgrades in 1 or 10 choice batches
- Break or heal the target's leg

## Alchemy

- Unlock all recipes
- Give the highest available quality of a selected potion
- Unlock individual recipes

## Fishing

- Discover all fish
- Reset the Fishdex

## Shouts

- Unlock all shouts
- Lock all shouts
- Reset all cooldowns
- Add one word to an individual shout or lock that shout

## Voice Knowledge

- Add 1 or 10 Voice Knowledge
- Set the balance to 1,000 or clear it

## Enchantments

- Discover all enchantments
- Apply a compatible LotN enchantment to the held item
- Remove all LotN enchantments from the held item

## Quests and Progression

- Accept or track quests, force completion, or reset quest progress
- Reset character level and skill progression (right-click the reset control)

## Server Settings

- Toggle vanilla enchanting tables
- Toggle vanilla enchanted books
- Toggle XP action bars

Reloading LotN is a separate control on the main admin menu.

## Command-Line Administration

The `/lotn` command also provides `reload`, `inspectmob`, `voiceknowledge`, `legendaryadmin`, `legacyadmin`, `questadmin`, and `bosscontribution` actions. Every `/lotn` action requires `lotn.use`; see [Commands and Permissions](commands-and-permissions.md) for the subcommands and permission nodes.
