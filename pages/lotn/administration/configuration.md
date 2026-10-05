---
title: Configuration
description: Config files, world filters, and reloading
updated: October 5, 2026
---


LotN loads `17` YAML config files. Invalid values may be limited, ignored, or replaced with a fallback. Most problems are also printed to the console.

| File | Main sections |
|---|---|
| `achievements.yml` | enabled, entries |
| `alchemy.yml` | schema-version, enabled, messages, study, brewing, quality-thresholds, ingredients, recipes |
| `bosses.yml` | schema-version, enabled, respect-existing-custom-name, format, names, dragon |
| `codex.yml` | schema-version, enabled, main, pages |
| `combat.yml` | schema-version, critical, ambient-effects, bleed, poison, burn, frost, shock, damage-variation, mob-shield-damage, combat-effects |
| `config.yml` | schema-version, chat, console, difficulty, combat-contributions, death-xp-loss, ipms, item-provenance, codex, leveling, level-display, legacy, systems, shouts, worlds, storage, character-creation, vitals, world-settings, trading, weight |
| `discoveries.yml` | schema-version, enabled, check-cell-size, milestones, rewards |
| `effects.yml` | schema-version, enabled, combat, fishing, quests, travel, loot, discoveries, alchemy, general |
| `enchantments.yml` | schema-version, debug, tiers, compatibility, drops, skill-modifiers, armor-caps, physical-damage-causes, immunities, discovery, families, lore, gui, visuals, messages |
| `equipment.yml` | schema-version, debug, armor, quality, tempering, definitions |
| `fishing.yml` | schema-version, fishing, rarities, fish, junk, treasures, sell |
| `mobs.yml` | schema-version, scaling, player-selection, levels, tiers, families, hologram, armor, equipment-profiles, rewards |
| `quests.yml` | schema-version, settings, word-seeking, tier-boundaries, boss-contribution, legacy-scaling, migration, quests |
| `display.yml` | schema-version, enabled, update-interval-ticks, show-title, show-numbers, title, quest-bar, lines, compass |
| `skills.yml` | schema-version, legendary, migration, multipliers, debug, item-progression, anti-exploit, notifications, categories, gui, integrations, xp-values, skills |
| `survival.yml` | schema-version, frostbite, injuries, messages |
| `shouts.yml` | schema-version, framework, voice-bearers, shouts |

## World Filtering

`config.yml` has `worlds.whitelist` and `worlds.blacklist`.

- An empty whitelist allows every world unless blacklisted.
- A non-empty whitelist allows only listed worlds.
- The blacklist always blocks matching worlds.

Alchemy, progression, survival, and several other systems use these world rules.

## System Toggles

The `systems` section in `config.yml` controls the major features, including Skills, Quests, Discovery, Codex recording, Codex viewing, Achievements, Fishing, Temperature, Injuries, Weight, Fast Travel, Mob Scaling, Alchemy, and the compass. `systems.codex` controls discovery recording; `systems.codex-viewer` independently controls access to the Codex menu.

Shout framework settings are in `shouts.yml`. New profiles use its `framework.default-unlocked-words` setting; the legacy `shouts.unlocked-words-by-default` value in `config.yml` is not the setting used for new profiles.

## Reload

The `/lotnea` main menu has a dedicated **Reload LOTN** action. Systems with reload support refresh their values, registries, and scheduled tasks. Invalid material, sound, particle, entity, or recipe names may still be rejected.

## Schema Versions

Most config files include `schema-version`. Keep it in place, because LotN uses it when loading and migrating config or player data.
