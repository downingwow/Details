# Details! CoA v1.1.0 — Combat and research integration (TEST)

Maintainer: Uncle Bone | https://github.com/downingwow/Details

## Changes
- Pet-only damage starts a new segment for confirmed owned pets, including group pets, on hostile targets.
- Resolve pet ownership on first damage event if combat log has no SPELL_SUMMON, using current pet GUID, cached ownership, or party/raid pet scan.
- Preserve verified Primalist focus/synergy attribution from uploaded 2026-10-29 Conquest Reborn combat log.
- Retain previous pet names, summon nil-guard, segment persistence patches, default 50 segments, contact metadata, and Demolition label.
- Keep runtime combat parsing dynamic for all client-reported spell IDs; don't ship giant unvalidated SQL tables in addon memory.

## Source index
https://github.com/downingwow/CoA-Research
https://github.com/Conquest-of-AzerothCore/azerothcore-wotlk-coa
https://github.com/DealsBeam/ascension-db
https://github.com/Bharph/coa-preservation-data
https://github.com/f3rr311/CoA-Databank
https://github.com/v1cferr/ascension-coa-scraper
https://ascension-db.ascension-archive.workers.dev/
https://coa-development.org/talents

## Scope limits
This build does NOT claim exhaustive imported class/spec/spell IDs or verified full Tinker Mechanics/Invention/Demolition pet/turret mapping.
It is not in-game validated. Back up SavedVariables. Original Details! attribution/licenses retained.
