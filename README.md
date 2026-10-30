# Details! CoA v1.1.0 — Expanded combat

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
