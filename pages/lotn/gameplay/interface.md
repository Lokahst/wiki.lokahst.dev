---
title: Interface
description: Scoreboard, quest bar, action bars, and mob holograms
updated: October 6, 2026
---

## Scoreboard

The scoreboard is enabled by default and refreshes every `20` ticks. Score numbers are hidden.

```text
lines:
  - "&a&lCharacter"
  - "&fName: &7{character_name}"
  - "&fCoins: &e{balance}"
  - "&8&m━━━━━━━━━━━━━━━━━━━━"
  - "&7&lEquipment"
  - "&fArmor Rate: &e{armor_rating}"
  - "&fCarrying: &e{weight}"
  - "&8&m━━━━━━━━━━━━━━━━━━━━"
  - "&9&lProgression"
  - "&fLevel: &b{level}"
  - "&fExperience: &7{xp}&8/&7{xp_required}"
  - "&8&m━━━━━━━━━━━━━━━━━━━━"
  - "&d&lWorld"
  - "&fDate: &7{date}"
  - "&fTemp: &7{temp_c}°C"
```

## Quest Bar

The tracked quest boss bar is enabled by default and refreshes every `10` ticks. It uses `YELLOW` with the `SEGMENTED_10` style.

## Action Bars

Overall XP and skill XP are shown in the action bar by default. Skill level-ups also use chat messages, sounds, and particles.

## Mob Holograms

Mob holograms show the mob's LotN name, level, and health. They appear when a player looks at the mob or enters combat with it.

## Compass

The direction compass is enabled by default. It updates every `2` ticks and shows the seven nearby compass directions; diagonal markers can be enabled or disabled in `display.yml`.
