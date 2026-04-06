# Pixel Platformer

![Pixel Platformer Screenshot](placeholder.png)

A purely vanilla JavaScript, HTML5 Canvas-based side-scrolling platformer with gravity, jumping, collectibles, enemies, and multiple levels. Everything is rendered purely procedurally without external assets or dependencies.

**Play the Demo:** [https://stonedhawk.github.io/pixel-platformer](https://stonedhawk.github.io/pixel-platformer)

## Features
- **10 Distinct Levels:** Journey through Green Hills, Underground Caverns, Sky Fortress, Snowy Peaks, Deep Dungeons, Canopy Jungles, Abandoned Factories, Volcanic Cores, The Void, and the Final Boss Arena.
- **Epic Boss Battle:** Face off against a multi-hit boss on Level 10 with a dedicated HP bar and unique combat mechanics.
- **Refined Physics:** Slower, smoother, and floatier movement with larger reaction windows. Features coyote time (6 frames), tile-based collision, and silky-smooth camera lerping.
- **Dynamic Elements:** Collect coins for bonus points, stomp on patrolling enemies (and the boss!) for high scores, and avoid deadly spike hazards.
- **Parallax Backgrounds:** 10 unique procedural backgrounds spanning various biomes, including starfields, rising volcanic embers, and mountain ranges.
- **Stats Integration:** Comprehensive scoring, life counters, and time-based bonuses per level.

## How to Play

| Action | Controls |
| :--- | :--- |
| **Move Left** | `A` or `Left Arrow` |
| **Move Right** | `D` or `Right Arrow` |
| **Jump** | `W`, `Up Arrow`, or `Spacebar` |
| **Menu / Next Level** | `Spacebar` |

*Lose all 3 lives and it's Game Over! Try to get the highest score by beating the time limit, grabbing coins, and squishing enemies.*

## Tech Stack
- Vanilla JavaScript
- HTML5 Canvas API (`requestAnimationFrame` Game Loop)
- Zero external dependencies. Everything runs natively in a single `index.html`.

## License
MIT License. Copyright (c) 2026 Rahul Shah.
