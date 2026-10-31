# Details! CoA v1.1.7 — Specialization and tooltip fixes

> **[⬇ Download v1.1.7]( https://github.com/downingwow/Details/releases/download/v1.1.7/Details-v1.1.7.zip )**


Updates since v1.1.0:

- Adds class-scoped specialization mapping for 21 custom classes and 70 specialization records, with talent-tree aliases for older internal names.
- Validates specialization names against the actor's class and resolves global ChrSpecs IDs exactly instead of treating class-local tab positions as global IDs.
- Removes the unreliable local-player numeric fallback that could identify Wildwalker as Grovekeeper. If the client supplies no usable name or talent data, the tooltip shows Unknown instead of guessing.
- Displays class and specialization as text in actor tooltips.
- Reads equipped item levels directly, retains legitimate zero/one heirloom levels, and waits for complete item data rather than counting uncached links as zero.
- Retains pet-only segment starts, first-hit pet-owner resolution, Primalist attribution, persistent combat history and the existing multi-folder addon package.

Install all Details* folders side by side in Interface/AddOns. Enable the main Details addon in the AddOns menu if needed. Keep and back up WTF/SavedVariables.

Published on the requested stable release channel. The supplied build still carries test labels and has not been fully validated in the live Conquest Reborn client. Historical mappings are not proof of every current specialization ID.

Maintainer: Uncle Bone — https://github.com/downingwow
Original licenses and attribution are retained.

## Earlier combat changes

### v1.1.0 — Expanded combat

- Pet-only hostile damage starts a combat segment for confirmed owned pets, including group pets.
- Resolves ownership on the first damage event through pet GUIDs, cached ownership or party/raid pet scans when SPELL_SUMMON is absent.
- Preserves Primalist focus/synergy attribution from the supplied Conquest Reborn combat log.
- Retains summon-name/nil safeguards, combat-segment persistence, a default 50-segment history for new profiles, maintainer metadata and the Demolition label.
- Keeps combat parsing dynamic for client-reported spell IDs; no giant unvalidated SQL database is loaded into addon memory.

This is the complete supplied multi-folder package. Some optional legacy plugins ship disabled TOCs; they remain disabled. Install all Details* folders side by side, then enable Details in the AddOns menu (its TOC defaults to disabled). Keep existing SavedVariables.

Full live-client validation and exhaustive Tinker pet/turret mappings remain pending. Original Details! attribution and bundled licenses are retained.

Maintainer: Uncle Bone — https://github.com/downingwow

## Support and attribution

Report errors with your addon version, UI addons and full Lua traceback at https://github.com/downingwow/Details/issues. Target: Ascension Conquest Reborn / WoW 3.3.5a (Interface 30300). Original source notices and bundled third-party licenses are preserved.

