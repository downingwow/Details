# Details! CoA v1.1.7 — Specialization and tooltip fixes

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

