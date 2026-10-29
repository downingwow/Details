# Details! CoA — v1.0.3 TEST (local ZIP build)

Maintainer: **Uncle Bone**  
Contact: https://github.com/downingwow

## Changes in the packaged test ZIP
- Preserve trash/custom-encounter combat history across reload/logout, while respecting save limits.
- Increase default saved segment history to 50 for new profiles.
- Guard invalid summon GUIDs and improve pet/guardian names when the combat log reports Unknown.
- Correct Tinker specialization label **Demolition** (existing mapping comment).
- Update addon maintainer, contact and repository metadata.

## QA status and important limits
- The ZIP was built and archive-integrity checked (478 files, no bad entries).
- **Not tested inside Conquest Reborn**. Do not describe the combat changes as fully verified.
- Reference databases have **not yet been imported as an exhaustive verified class/spell mapping**.
- Historical game data may differ from live Ascension spell IDs.
- Original third-party license / attribution files are retained.
- Back up SavedVariables before installation.

The source tree is **not yet uploaded to GitHub** by this change; this release note documents the local ZIP build only.
