# Mashup Contract

## Ownership
- Elden Ring owns player position, camera, movement, collision, enemy state and boss state.
- Isaac layer owns run/loadout state, item effects, tear modifiers, familiar state and trinkets.

## State
`LoadoutState`:
- tears: base projectile profile + modifiers
- items: collected item IDs and active effects
- familiars: active familiar IDs and cooldown/state
- trinkets: equipped trinket IDs
- resources: hearts/charges/counters needed by implemented effects

## Lifecycle
1. Detect Isaac installation.
2. Read/convert only required local data.
3. Initialize a fresh loadout in the opening room.
4. Enter Elden Ring world.
5. Tick Isaac rules alongside host gameplay.
6. Apply derived effects to host-side projectiles/entities.
7. Serialize run state only for the active session.

## Failure
If Isaac is not installed or required source data is unavailable, show an explicit
in-game diagnostic and disable the Isaac layer. Never substitute unrelated content while
claiming it came from Isaac.

## Network
Single-player/offline vertical slice only. No official online services are touched.
