# Details! Damage Meter — CoA

**Maintainer:** Uncle Bone  
**Contact:** https://github.com/downingwow  
**Game:** Ascension — Conquest of Azeroth / Conquest Reborn (WoW 3.3.5a-based client)

A Conquest Reborn adaptation of Details! Damage Meter that tracks damage, DPS, healing, HPS, combat encounters, and pet/guardian contributions. The addon includes the original Details! multi-module package. Third-party copyright and license notices remain intact.

## Latest local test build: v1.0.3 (TEST)

- Preserve trash and unrecognized custom-boss encounter history across logout/reload, subject to configured save limit.
- Increased default saved history to 50 for new profiles (existing profile preferences remain).
- Harden summon event handling against missing GUIDs and unnamed creatures.
- Improve pet display fallback using cached pet name, summon spell name, or client spell name.
- Correct the existing Tinker spec 51 label to **Demolition**.
- Update maintainer/contact/repository metadata to Uncle Bone / downingwow.

**Status:** Test build; static ZIP integrity checked, not validated inside Conquest Reborn. Complete all-class spell-ID import and verification of custom summons remain open tasks.

### Data references
- [CoA AzerothCore](https://github.com/Conquest-of-AzerothCore/azerothcore-wotlk-coa)
- [DealsBeam Ascension DB](https://github.com/DealsBeam/ascension-db)
- [CoA preservation data](https://github.com/Bharph/coa-preservation-data)
- [CoA Databank](https://github.com/f3rr311/CoA-Databank)
- [Talent scraper](https://github.com/v1cferr/ascension-coa-scraper)
- [CoA talents](https://coa-development.org/talents)
- [Ascension database](https://ascension-db.ascension-archive.workers.dev/)
- [Historical BisBeard glyph data](https://github.com/kevinvongmany/bisbeard-db)

The above repositories are research references and are **not** claimed to be exact verified Conquest Reborn game-client exports. This README is not a substitute for the source distribution: use the packaged test ZIP and back up SavedVariables first.
