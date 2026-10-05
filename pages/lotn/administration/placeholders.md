---
title: Placeholders
description: PlaceholderAPI placeholders
updated: October 5, 2026
---

PlaceholderAPI is optional. LotN uses the `lotn` expansion, so placeholders follow this format:

```text
%lotn_<placeholder>%
```

## Fixed Placeholders

| Placeholder | Value |
|---|---|
| `%lotn_player_name%` | Minecraft username |
| `%lotn_character_name%`<br>`%lotn_character%` | LotN character name |
| `%lotn_race%` | Race display name |
| `%lotn_race_id%` | Race ID |
| `%lotn_level%`<br>`%lotn_player_level%` | Overall level |
| `%lotn_level_max%` | Maximum overall level |
| `%lotn_xp%`<br>`%lotn_level_xp%` | Current overall XP |
| `%lotn_xp_required%`<br>`%lotn_level_xp_required%` | XP needed for next level |
| `%lotn_xp_percent%`<br>`%lotn_level_xp_percent%` | Percentage progress toward the next level |
| `%lotn_xp_lifetime%`<br>`%lotn_level_xp_lifetime%` | Lifetime overall XP |
| `%lotn_attributes_can_increase%` | Whether attributes can still be increased |
| `%lotn_legacy_rank%` | Legacy rank |
| `%lotn_bossbar_state%` | Active level-boss-bar channel, or `none` |
| `%lotn_skill_average%` | Average skill level |
| `%lotn_skill_total_levels%` | Sum of all skill levels |
| `%lotn_skill_highest_name%` | Highest skill name |
| `%lotn_skill_highest_level%` | Highest skill level |
| `%lotn_wayfaring_fast_travel_points%` | Unlocked Fast Travel Point limit |
| `%lotn_pending_vitality_choices%` | Unused vitality choices |
| `%lotn_injury_broken_leg%` | Broken leg state |
| `%lotn_health%`<br>`%lotn_hp%` | Displayed Health |
| `%lotn_max_health%`<br>`%lotn_max_hp%` | Maximum Health |
| `%lotn_stamina%` | Current Stamina |
| `%lotn_max_stamina%` | Maximum Stamina |
| `%lotn_magicka%` | Current Magicka |
| `%lotn_max_magicka%` | Maximum Magicka |
| `%lotn_weight%`<br>`%lotn_carry_weight%` | Current carry weight |
| `%lotn_max_weight%`<br>`%lotn_max_carry_weight%` | Maximum carry weight |
| `%lotn_armor%`<br>`%lotn_armor_rating%` | Current armor rating |
| `%lotn_active_quest%` | Tracked quest name |
| `%lotn_active_quest_objective%`<br>`%lotn_active_quest_progress%` | Tracked objective progress |
| `%lotn_quests_active%` | Active quest count |
| `%lotn_quest_tracked%`<br>`%lotn_quests_tracked%` | 1 when a quest is tracked |
| `%lotn_quests_completed%` | Completed quest count |
| `%lotn_economy_balance%`<br>`%lotn_balance%` | Vault balance |
| `%lotn_discoveries%` | Discovery count |
| `%lotn_fish_caught%` | Fish caught |
| `%lotn_temperature%` | Current temperature |
| `%lotn_biome%` | Current biome |
| `%lotn_world%` | Current world |
| `%lotn_in_game_date%`<br>`%lotn_date%` | LotN date |
| `%lotn_in_game_time%`<br>`%lotn_time%` | LotN time |

## Skill Placeholders

Replace `<skill>` with a skill ID, for example `one_handed`, `archery`, `smithing`, or `wayfaring`.

| Pattern | Value |
|---|---|
| `%lotn_skill_<skill>_level%` | Current skill level |
| `%lotn_skill_<skill>_xp%` | Current XP inside the skill level |
| `%lotn_skill_<skill>_next_xp%` | XP required for the next skill level |
| `%lotn_skill_<skill>_xp_required%` | Alias of next XP |
| `%lotn_skill_<skill>_progress%` | Percentage progress toward the next level |

## Target Placeholders

Target placeholders use the living entity hit by the player's view ray, within the configured mob hologram look range.

| Placeholder | Value |
|---|---|
| `%lotn_target_name%` | Name |
| `%lotn_target_variant%` | Variant |
| `%lotn_target_family%` | Family |
| `%lotn_target_level%` | Level |
| `%lotn_target_hp%` | HP |
| `%lotn_target_max_hp%` | Maximum HP |
| `%lotn_target_hp_percent%` | HP percentage |
| `%lotn_target_tier%` | Tier |
