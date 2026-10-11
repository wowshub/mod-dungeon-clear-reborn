# mod-dungeon-clear — RebornWOW fork

This is the RebornWOW version of [jrad7/mod-dungeon-clear](https://github.com/jrad7/mod-dungeon-clear)
by Jared Wright and contributors, AGPL-3.0-or-later (see `LICENSE`). It is what runs on the
RebornWOW server, published here as the AGPL requires.

## Where it comes from
- Based on upstream `60f3d98b8` (2026-10-01). The upstream history is kept below our commits.
- Our changes are the commits after that one. They are exported from the module folder
  `modules/mod-dungeon-clear` of
  [wowshub/AzerothCore-wotlk-with-PlayerBots-NPCBots](https://github.com/wowshub/AzerothCore-wotlk-with-PlayerBots-NPCBots),
  where the server is actually built. Each commit message names the source commit.
- Branch `upstream-jrad7` mirrors upstream `master`, for merging upstream updates with plain `git merge`.

## RebornWOW changes (summary)
- Self-bot ("Auto-play") from the panel; rezzers are only party members who know a rez spell.
- Finished objectives survive a wipe; event moves never cut through walls (Halls of Stone).
- GM test runs: run list, bot inspect, panel cap control, spectate follow.
- Companion client addon: [wowshub/mod-dungeon-clear-addon](https://github.com/wowshub/mod-dungeon-clear-addon).
