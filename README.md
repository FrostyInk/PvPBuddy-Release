# PvP Buddy

A [Nexus](https://github.com/RaidcoreGG/Nexus) addon for Guild Wars 2. A live PvP scoreboard with detailed
per-player stats for both teams, while the match is running.

**Beta.** Stats are still being checked against the game's own scoreboard, so expect rough edges.

## Installation

1. Install [Nexus](https://github.com/RaidcoreGG/Nexus) if you haven't already.
2. Download `PvPBuddy.dll` from the
   [latest release](https://github.com/FrostyInk/PvPBuddy-Release/releases/latest) and place it in
   `<Guild Wars 2>/addons/`.
3. Launch the game. Nexus loads the addon automatically.
4. Press `CTRL+SHIFT+P` to open the board. You can change the keybind in Nexus's keybind settings.

## What it does

- **Both teams, live.** Every player with their profession or elite spec icon, character name and account.
- **Five views,** each with its own sort:
  - **Overview:** downs and kills, assists, downed and deaths, damage, healing, caps, decaps.
  - **Combat:** downs and kills, takedowns, assists, downed and deaths, damage, cleave, damage taken.
  - **Support:** ally and self healing, barrier, downed healing, revives, rallies, damage taken.
  - **Objectives:** caps, decaps, holds, map objectives, rotations, time on point, contested, outnumbered.
  - **Control:** CC, interrupts, boon strips, cleanses, blocks, evades.
- **Badges** for each team's standouts (Damage, Downs, Finisher, Objectives, Anchor, Outnumbered, Medic,
  Survivor).
- **MVP per team,** weighted so a support, a duelist or a roaming thief can win it, not only top damage.
- Hover a number for its exact value or breakdown, hover a name for profession and spec.

Damage on stealthed enemies can't be seen by the game client, so Damage reads low against stealth-heavy teams.

## Settings

- **Highlight yourself** on the board.
- **Board scale** from 75% to 200%. Text is rebuilt at the chosen size, so it stays sharp.
- **Board font.** Put `.ttf` or `.otf` files in `<Guild Wars 2>/addons/PvPBuddy/fonts` (the addon creates the
  folder), press **Rescan**, and pick one. A matching italic file, such as `MyFont-Italic.ttf` next to
  `MyFont-Regular.ttf`, is used for account names.

Settings are saved in `<Guild Wars 2>/addons/PvPBuddy/settings.ini`.

## Fair play

PvP Buddy only reads what the game already shows your client. It never changes game memory, sends input or
automates anything.

## Credits

Icons: [Uicons by Flaticon](https://www.flaticon.com/uicons). Profession icons © ArenaNet.

## Author

Ashen
