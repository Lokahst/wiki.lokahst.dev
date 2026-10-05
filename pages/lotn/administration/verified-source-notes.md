---
title: Verified Source Notes
description: Changes confirmed in the current build
updated: October 5, 2026
---


Older documentation may describe features that were removed or changed. The list below matches the uploaded build.

## Confirmed Current Behavior

- The registered command roots are `/lotn` and `/lotnea`. `/lotn` includes player and administrator subcommands as well as the player menu.
- Alchemy, Enchantments, Shouts, Fast Travel, Fishdex, and Fish Exchange are available through the `/lotn` menu; related `/lotn` subcommands also exist.
- The Enchantments menu browses tiers and discoveries. It does not apply enchantments for normal players.
- The current enchantment system has eight families and five tiers, not the older named-enchantment list.
- Vanilla enchanting tables and enchanted books are enabled by default.
- The Codex menu contains a character record plus World, Combat, Fishing, and Survival statistics pages. Achievements are in the Quest Journal, not a Codex page.
- Current mob shield damage begins at 35% through, not 10%.
- The Fish Exchange is the working sale interface. Fish item lore now shows only rarity and value.
- Fishing no longer generates or stores fish weight and length.
- Wayfaring stops at level 3. Its only rewards are the three Fast Travel Point unlocks.
- Overall character level is capped at 10,000; vitality choices are awarded only through level 99.
- The default skill XP formula uses a base of 500 (growth 1.18), not 100.
- The quest file contains 88 definitions; 50 are enabled by default. Several older adventure quests are disabled.
- Shouts have three word tiers with different costs, cooldowns, and effects. New profiles start with zero unlocked words.
- The current boss display names are Yrrakhael, Morzhar, Eshven Thal, and Nethgath.
- Alchemy recipes allow duplicate ingredients by default.
- Broken-leg chance uses effective-fall-distance brackets and is adjusted by landing surface, difficulty, health, and enchantment mitigation.
- Death XP loss is enabled by default, but character-level loss is disabled.
- Splash and lingering Alchemy effects and rotating merchant offers require integrations that are disabled by default.
- Fast Travel has a 30-second cooldown by default.
- Water Currents are not present in this source build or its system toggles.
- Tools are present in the equipment registry, but the current tempering preview only accepts weapons and armor.