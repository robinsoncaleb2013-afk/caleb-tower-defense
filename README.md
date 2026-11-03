# Caleb's Tower Defense

**Stand Against the Horde** — a hybrid tower defense + troop battler built for [robinsonaisystems.com/caleb](https://robinsonaisystems.com/caleb).

## Features

- **135 Story Levels** that ramp in difficulty and complexity
- **50 Towers & Troops** split into two groups:
  - **Towers** fire projectiles (cannon, archer, mage, tesla, mortar, frost, laser, poison, railgun, flame, ballista…)
  - **Troops** spawn units that march toward the enemy (soldier, knight, rogue, berserker, healer, tank, assassin…)
- **3-Stage Evolution** — double-click a placed tower to evolve it (costs gold)
- **75 Monster Types** + **45 Bosses** (one boss every 3 levels)
- **Loadout system**: RNG unlocks go into your backpack; pick exactly **5** for your team. Duplicates are removed. One of each tower type only.
- **Base upgrades**: more HP, armor, and at Base Level 10 a **Self-Defense Bomb** (5 damage to base, large AoE clear)
- **Modes**: Story · Sandbox · Infinite · Local Co-op Multiplayer
- **Controls**: Mouse/touch to place. Mobile buttons for spawn & bomb. PC + mobile friendly.
- **Visuals**: spinning towers, glowing projectiles, particles, cinematic RDO-style main menu

## How to Play

1. Open `index.html` in a modern browser (or host the folder on your site).
2. **Loadout** — choose 5 units from your backpack.
3. **Story Mode** — survive waves, beat bosses, unlock new towers.
4. Place towers on the field (tap/click). Troops spawn near the base and auto-attack.
5. Double-click a tower to evolve it (when you have gold).
6. Pause → Base Upgrades for HP / armor / bomb.

## Hosting on robinsonaisystems.com/caleb

Upload the contents of this repo (especially `index.html`) to the `/caleb` path on the site, or point a GitHub Pages / static host at this repository.

```bash
# Local test
npx serve .
# or just open index.html
```

## Tech

Pure HTML5 Canvas + vanilla JS. No build step. Works offline after first load (Google Fonts optional).

## Credits

Built for Caleb · Robinson AI Systems
