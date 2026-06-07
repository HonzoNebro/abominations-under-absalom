# Abomination Under Absalom

A Foundry VTT module for Pathfinder Second Edition.

## Compatibility

Version 2.0.1 is prepared for Foundry VTT 14 and PF2e 8.1.2. It intentionally does not claim support for Foundry VTT 12 or 13.

## Foundry VTT 14 Migration Checklist

The compendium packs in this repository were originally produced by Foundry VTT 12 and PF2e 6.x. Before publishing v2.0.0, complete the data migration in a clean Foundry VTT 14 instance:

1. Install Foundry VTT 14 and PF2e 8.1.2.
2. Install this module as `Data/modules/abomination-under-absalom`.
3. Open a clean PF2e world with only this module enabled.
4. Unlock or import each pack, allow Foundry and PF2e migrations to complete, and reexport the migrated packs.
5. Validate `adventure`, `bestiary`, `items`, `feats`, `spells`, `monster-effects`, `monster-abilities`, `rollable-tables`, and `macros`.
6. Audit `packs/monster-effectsabilities`; consolidate any unique migrated documents into `monster-effects` and keep the orphan pack out of the release artifact.
7. Import the adventure and test scenes, walls, doors, regions, journals, UUID links, and hazard/pylon/airlock macros.

## Release Packaging

Publish the v2.0.1 download as a release asset named `abomination-under-absalom.zip`. The zip must contain a top-level folder named `abomination-under-absalom`, matching the module id in `module.json`.
