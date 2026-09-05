# LAST LIGHT

**Life · Vision · Weapon**

LAST LIGHT is a minimalist mobile survival game built as an installable Progressive Web App. Your light is simultaneously your life, your vision, and your ammunition. Every shot makes the world darker. Defeated enemies leave light behind, forcing you to decide how aggressively to reclaim it while the swarm closes in.

## v7 — Balance & Mastery Pass

- Reworked difficulty so **Ember / Dark / Void** alter speed, spawn pressure, ambient light drain, and mote lifetime rather than simply fast-forwarding enemies.
- Rebalanced multi-hit enemy light economy, especially Shell, Leech, and Void.
- Reworked **Last Spark** into a true clutch mechanic: it requires a meaningful fall from bright light and can trigger only once per stage.
- Refined one-finger controls: **drag always means move; a quick tap aims and fires toward the nearest visible enemy in that direction**.
- Retuned progression to **0 → 10 → 40 → 100 → 225 → 400 → 700** for enemy unlocks.
- Added a special **1000-point mastery state: THE LIGHT REMEMBERS**. It grants a dramatic transition into endless play rather than introducing another ordinary enemy.
- Rebuilt the procedural score around a stronger eight-beat **LAST LIGHT** hook that becomes more complete as the run deepens.
- Added true projectile-hit tracking so game-over **Accuracy** is mathematically correct even against multi-hit enemies.
- Preserved Overlight, close-kill rewards, edge whispers, reveal audio, and stage grace.

## Progression

| Score | Enemy | Points |
|---:|---|---:|
| 0 | Shade | 1 |
| 10 | Wisp | 2 |
| 40 | Shell | 3 |
| 100 | Moth | 4 |
| 225 | Splitter | 5 |
| 400 | Leech | 6 |
| 700 | Void | 7 |
| 1000 | **THE LIGHT REMEMBERS** | Endless mastery |

Three difficulties are available: **Ember**, **Dark**, and **Void**. Dark is the intended baseline experience.

## Controls

- **Drag** to move.
- **Quick-tap toward a visible enemy** to fire.
- Every shot costs light.
- Kills leave light motes; close kills leave richer motes.
- Excess light can forge an **Overlight** one-hit halo.

## Deploy with GitHub Pages

Upload all files in this folder to the root of the repository. Under **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then save. GitHub Pages will redeploy automatically after later commits.

On iPhone, open the GitHub Pages URL in Safari. To install it, use **Share → Add to Home Screen**.
