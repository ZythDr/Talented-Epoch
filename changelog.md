# Changelog

All notable changes to the Talented port for Project Epoch.

## [0.2.1] - 2026-05-11

### Fixed

- Fixed a syntax error in the generated talent database (`Data.lua`) that caused UI load and login failures.

---

## [0.2.0] - 2026-05-11

### Added

- Implemented Project Epoch custom, normalized pet talent tree mapping for Ferocity, Tenacity, and Cunning specs.
- Added full custom 12-talent layout grid alignments, prerequisites, and verified Spell IDs for pet talents. (Level Requirements display in Talented Frame still WIP)
- Added localized talent name and icon asset bindings for all three pet spec trees.

### Removed

- Removed all traces of Death Knights from Talented.

---

## [0.1.0] - 2026-05-11

### Added

- Completed talent database with full custom spell ID mappings for Mage, Druid, and Warlock classes.
- Full custom talent database coverage across all 9 classes (589 out of 589 talents resolved).

### Fixed

- Fixed layout compilation conflicts where classes shared identical talent names but used different spell IDs (e.g., Precision, Deflection, Toughness).
- Silenced false-positive "Unresolved talent" system chat messages on login and UI reload.

---

## [0.0.2] - 2026-04-25

### Added

- Custom layout templates and spell ID mappings for Warrior, Paladin, Hunter, Rogue, Priest, and Shaman trees.

### Fixed

- Restored proper button alignments, row/column grids, and dependency arrows to match Project Epoch talent structures.

---

## [0.0.1] - 2026-03-31

### Added

- Initial port of the Talented addon to the Project Epoch client (WotLK 3.3.5 base).
- Offline template compilation framework.
