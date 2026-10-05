---
title: Shouts
description: How to unlock, select, and use shouts
updated: October 5, 2026
---

New characters start with `0` unlocked shout words by default. The setting is `framework.default-unlocked-words` in `shouts.yml`. Words can be unlocked through quests or administration; `config.yml` also contains a legacy starting-word setting that is not used for new profiles.

## Selecting and Activating

1. Open Shouts from `/lotn`.
2. Select an unlocked shout.
3. Double-shift to activate.

The two sneak presses must happen within `350` milliseconds. Shouts cannot be used while dead or in Spectator mode. Using one consumes Magicka and starts its cooldown.

| Shout | Words | Magicka | Cooldown | Effect |
|---|---|---|---|---|
| Unrelenting Force | `Fus Ro Dah` | 20 / 27 / 35 | 12 / 15 / 19s | Pushes and damages enemies in a cone.<br>Range: 7 / 9 / 12 blocks; damage: 3 / 5 / 8 |
| Whirlwind Sprint | `Wuld Nah Kest` | 18 / 24 / 30 | 9 / 11 / 14s | Launches the player forward and stops before unsafe blocks.<br>Distance: 6 / 10 / 15 blocks |
| Fire Breath | `Yol Toor Shul` | 25 / 32 / 40 | 18 / 22 / 27s | Damages and ignites enemies in a cone.<br>Range: 7 / 9 / 12 blocks; fire: 3 / 5 / 7.5s; damage: 4 / 7 / 11 |
| Become Ethereal | `Feim Zii Gron` | 28 / 34 / 42 | 38 / 43 / 48s | Prevents incoming damage while offensive actions are disabled.<br>Duration: 3 / 5 / 7.5s |
| Storm Call | `Strun Bah Qo` | 45 / 55 / 65 | 300 / 600 / 1200s | Starts a storm and strikes nearby enemies.<br>Duration: 20 / 40 / 60s |
| Aura Whisper | `Laas Yah Nir` | 18 / 24 / 30 | 75 / 120 / 180s | Reveals nearby mobs through walls.<br>Range: 10 / 20 / 30 blocks; duration: 9 / 16 / 25s |
| Battle Cry | `Kaan Drem Ov` | 35 / 43 / 52 | 180 / 300 / 480s | Forces nearby mobs to stop combat temporarily.<br>Range: 16 / 22 / 30 blocks; duration: 7 / 13 / 20s |
| Clear Skies | `Lok Vah Koor` | 16 / 20 / 25 | 120 / 180 / 240s | Clears weather and active Storm Call.<br>Clear weather: 300 / 600 / 1200s |
| Dragon Aspect | `Mul Qah Diiv` | 55 / 65 / 75 | 900 / 1800 / 3600s | Increases worn armor rating by 10 / 16 / 22%.<br>Duration: 120 / 210 / 300s |
| Drain Vitality | `Gaan Lah Haas` | 28 / 35 / 44 | 34 / 40 / 48s | Damages nearby targets and restores Health; higher words can also restore Stamina.<br>Range: 8 / 10 / 13 blocks; damage: 3 / 5 / 8; duration: 4 / 6.5 / 9.5s |

Slash-separated values are for the first, second, and third words unlocked for that shout.

## Special Rules

- Fire Breath deals only 15% of normal damage to dragons.
- The third word of Storm Call lasts 60 seconds and attempts strikes every 3 to 6 seconds within 64 blocks.
- Battle Cry suppresses nearby mob combat for 20 seconds.
- Dragon Aspect needs at least one worn armor piece.
- High Elves have 15% longer shout cooldowns.