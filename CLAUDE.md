# esimv1-earth2100

Project-specific orientation only. House policy (devlog, git, UX, writing, deploy) comes from the
harness and is not repeated here.

## What this is

Earth 2100: the planet to 2100 under several assumptions about emissions, with people, heat, tipping elements and knock-on effects, as an esimv1 scenario.

## Where things are

- One project folder, `planet-2100` (the address has always been `/anselm/planet-2100`; the title is Earth 2100).
- After the engine's `manifests/p4-planet-people.toml` changes: `esim project update ./planet-2100 --manifest
  <core>/manifests/p4-planet-people.toml`, then rerun every variant (about 5 s each, more with the cell layers).
- The cell layers need `esim warm cells` once (about 100 minutes, 3.3 GB in the engine's cache).
- On canada1 the working clone is `~/projects/2026/earth-simulator-1/scenarios/esimv1-earth2100`, linked into the hub's
  `projects/anselm/`. History and facts before 22 November 2026: `anselm/esimv1`, `CLAUDE.md` and `devlog/`.

