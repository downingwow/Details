# Details! Damage Meter — CoA

**Maintainer:** Uncle Bone  
**Contact:** https://github.com/downingwow  
**Bug reports:** https://github.com/downingwow/Details/issues  
**Game:** Ascension / Conquest of Azeroth / Conquest Reborn (WoW 3.3.5a-based)

A customized Details! damage and healing meter for Conquest Reborn. Tracks damage, DPS, healing, HPS, combat segments, spell breakdowns, pets and guardians. Original third-party licenses and attribution must be retained.

## Current build: v1.1.0 TEST (2026-10-29)

The complete test ZIP was generated in the addon development conversation. **It is not attached to this GitHub repository as a release asset**, and the complete source tree has not been uploaded here. Do not install the repository README alone.

### Implemented
- Primalist pet identification verified in-game with a Devilsaur.
- Pet damage ownership from observed CoA combat-log focus/synergy events.
- Pet-only pull combat starts on damaging events, with first-hit owner resolution from the client pet GUID, cache, or group pet scan (test needed).
- Protect against invalid summon GUIDs and missing creature names.
- Combat history retention patches; 50 default saved segments for new profiles (needs live zone/reload verification).
- Tinker Demolition display-label correction.
- Contact and feedback point to Uncle Bone / downingwow.

### Still not complete
- Exhaustive imported/verified all-class spell IDs, specs and Tinker Mechanics/Invention/Demolition combat mechanics.
- Full coverage of custom turrets/constructs/guardians, absorbs, and proc ownership.
- In-game QA of v1.1.0 and zone/reload encounter persistence.

## Research
Use [CoA-Research](https://github.com/downingwow/CoA-Research) for source indexes, SQL archives, class spellbooks, talent data and BisBeard references. Historical references are not authoritative current Conquest Reborn spell IDs.

See [test changelog](CHANGELOG-CoA.md). Back up SavedVariables before installing a test ZIP.
