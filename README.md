# Isaac in the Lands Between

Vertical-slice design scaffold for an offline Elden Ring mashup.

## Goal
Real Elden Ring remains the host. The player starts in an Isaac-style opening room,
receives a small Isaac loadout, then enters the Lands Between and expands that loadout
through pickups, trinkets, familiars and synergies.

## Vertical slice
1. Isaac-style opening room
2. Initial tears + one item/familiar
3. Transition into a small Elden Ring exploration/combat area
4. Isaac pickups and synergy changes
5. One Elden Ring boss encounter
6. Run-state HUD/loadout feedback

## Requirements
- Elden Ring PC
- Binding of Isaac: Rebirth installed locally
- Offline launch through the Melty-managed Elden Ring mod loader
- No Isaac retail assets are redistributed; converters/readers operate on the player's own installation.

## Current status
Design and integration contract scaffold only. A real game build requires access to the
target Elden Ring installation, Isaac installation, Melty build/publish interface, and
an in-game test environment. None is exposed in this ChatGPT session, so no executable
mod or "tested" claim is made here.
