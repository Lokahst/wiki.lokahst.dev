---
title: Quests
description: Quest journal, objectives, requirements, and rewards
updated: October 5, 2026
---

The default quest config contains `88` definitions; `50` are enabled for normal play. Disabled entries are not available from the quest journal. Each player can have up to `5` active quests.

## Quest Journal

Open the Quest Journal from `/lotn`. It separates active and available quests, shows objective progress, and lets the player track one quest. The tracked quest also appears in the boss bar when enabled.

## Availability

A quest may require a character level, completed quest, discovery, permission, or skill level. Repeatable quests may also have a cooldown. Quest progress and rewards require `lotn.progress.quests`.

## Completion

Quest completions are recorded in player Codex data. Depending on the quest, rewards can include character XP, skill XP, items, money, or unlocked shout words.

## Available by Default

The enabled quests are grouped in the config under these categories:

- **Main:** Main Quest: Kill the Ender Dragon
- **Boss:** Master Hunt: Wither
- **Legendary and Legacy:** Legendary Northern Expedition; Legacy Proving Ground
- **Combat:** Monster Slayer; One-Handed Mastery; Archery Mastery
- **Smithing:** Blacksmith's Work
- **Fishing:** Fisherman's Catch; Rare Waters
- **Shouts:** Shout Mastery I, II, and III
- **Survival:** Survivor I, II, and III
- **Voice:** Whirlwind Sprint; Unrelenting Force; Battle Cry; Clear Skies; Aura Whisper; Drain Vitality; Become Ethereal; Fire Breath; Storm Call; Dragon Aspect
- **Artisan:** Stonework; Iron Miner; Ironworker; Full Arsenal; Fine Craftsmanship; Superior Craftsmanship; Exquisite Craftsmanship; Flawless Craftsmanship; Epic Craftsmanship; Legendary Craftsmanship; Armed to the Teeth; The Smelter; Busy Hands; Armorer; Stonecutter; Deep Delver; Iron Reserves; Master Smith; Seasoned Crafter; Rich Veins; Forged to Perfection; Master of Materials; The Grand Workshop; Legendary Artisan

Quest objectives, requirements, repeatability, and rewards are shown in the journal and are configurable in `quests.yml`.