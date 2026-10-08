# MODLOG

## Route
Reimplemented Isaac rules fused into the real Elden Ring host, with local asset/data
conversion from the player's own Isaac installation.

## Why
The requested experience is Elden Ring gameplay with a full Isaac loadout system.
Running both retail games simultaneously is heavier than necessary for this vertical
slice; the host owns the player, camera, collision and world while the Isaac layer owns
loadout state and its derived effects.

## First slice oracle
A successful run must demonstrate:
- Isaac-style opening appears.
- Initial tears fire in real Elden Ring combat.
- At least one Isaac item changes tear behaviour.
- A familiar produces an observable gameplay effect.
- A pickup changes the persistent run loadout.
- The player reaches and can fight one real Elden Ring boss.
- Missing Isaac installation fails gracefully without pretending Isaac content loaded.

## Evidence level
Not yet run in a real game. This scaffold is not a substitute for an in-game test.
