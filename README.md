# The Last Survivor

An offline, single-player browser survival RPG starring Darwin.

## Run

Serve the `dist` directory with any static file server, then open its local URL. No installation, build, package manager, external assets or internet connection is required.

Example: `npx serve dist`

## Controls

- WASD / arrows: move
- E: gather or collect water
- Q: Analyse the nearest resource or current region
- Escape: close a panel
- Plus / minus: zoom the world camera
- Mouse/touch: inventory, crafting, quests, Shop, map and save controls

Explore to lift fog, Analyse resources, gather supplies, craft equipment and complete quests. Quest rewards provide XP and Credits. Credits purchase equipment through the magical Online Shop. Survival statistics continue to change as time advances.

Saves are versioned and stored in browser localStorage. Autosave occurs every 10 seconds, with a fallback snapshot for safe recovery.

## Test

Run `node tests/core.test.js` from the project root.

See `ROADMAP.md` for the exact completion boundary and `CHANGELOG.md` for changes from Brambleroot.
