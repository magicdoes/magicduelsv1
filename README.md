# MagicDuels 1.3.0

MagicSMP duel plugin for Paper 26.2 / Java 25.

## Duel flow
1. `/duel <player>` or `/duel <player> <wager>` sends a request.
2. The challenged player sees the wager before accepting.
3. `/duel accept` opens the gamemode GUI.
4. The challenged player clicks a gamemode.
5. Both players' real inventories are saved and replaced with the selected gamemode kit.
6. Both players teleport to the arena, fight, and then get their original inventory/location back.

## Default gamemodes
- Sword PvP
- Axe PvP
- Archer
- Netherite
- Crystal PvP

All gamemode icons, GUI slots, armor and inventory items can be edited in `config.yml`.

## Player commands
- `/duel <player>`
- `/duel <player> <wager>`
- `/duel accept`
- `/duel deny`
- `/duel status`

Wagers accept `1k`, `25k`, `1.5m`, `2m`, `1b`, etc.

## Admin commands
- `/duel setspawn 1`
- `/duel setspawn 2`
- `/duel reload`

## GitHub build
Upload the contents of the `MagicDuels` folder to the root of your GitHub repository, then use **Actions -> Build MagicDuels -> Run workflow**.

Download the `MagicDuels-1.3.0` artifact after the build finishes and put the JAR in the server's `plugins` folder.
