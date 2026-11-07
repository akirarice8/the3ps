# The 3 P's Heroic Adventure

## Concept
A Mario-style 2D side-scrolling platformer built in HTML5 Canvas and JavaScript. Penelope the Magic Elf and Parker the Magical Fairy set out to rescue their sister Piper the Pixie Fairy, who has been captured and imprisoned by Maleficent the Evil Witch.

## Worlds
1. **Floating Sky Islands** — bright sky islands with clouds, flowers, and mushrooms. The opening world.
2. **Maleficent's Dark Castle** — dark dungeons, secret passages, and haunted corridors. The final world where Piper is held.

## Heroes

### Penelope (Magic Elf Archer)
- **Weapon:** Arrows that never miss and freeze enemies on contact (ice/freeze arrows).
- **Helper:** Flaming Fire Fox companion that shoots fireballs at enemies.

### Parker (Magical Fairy Spellcaster)
- **Weapon:** Magic wand that shoots poison vines with thorns.
- **Helper:** Magical Cat companion that shoots lightning from its tail.

## Enemies

| Enemy | Attack |
|-------|--------|
| **Web Spiders** | Shoot webs that trap and immobilize players. |
| **Ghosts** | Shoot goop that lands on the ground and makes it sticky, slowing movement. |
| **Haunted Trees** | Throw poison apples at players. |
| **Poison Butterflies** | Drop poison dust below their flight path as they move across the screen. |
| **Robots** | Throw sharp wrenches at players. |

## Ending
Defeat Maleficent — she drops the special prison key. Use the key to unlock Piper's prison. Piper the Pixie Fairy is free!

## Technical Rules
- Single-page HTML5 Canvas and JavaScript (`index.html` only — no build step, no frameworks).
- Must work on iPad with on-screen touch controls (D-pad left/right, JUMP, SHOOT, SWAP buttons).
- Keyboard controls: **Up Arrow** = jump, **Spacebar** = shoot, **Tab** = swap character.
- Deployed on Netlify at **https://the3ps.netlify.app/** (auto-deploys from the `main` branch on push).
- **Always `git add`, commit with a clear message, and `git push origin main` at the end of every task.**
