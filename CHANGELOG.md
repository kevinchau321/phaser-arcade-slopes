# Arcade Slopes Change Log

## v0.2.0-alpha - 19th August 2016
- Initial circular physics body support.
- Typescript definitions (thanks @IkonOne).

## v0.1.1 - 26th June 2016
- Implemented corner collision pulling (#3).
- Fixed incompatibility with Phaser 2.4.9 and 2.5.0 (#5).
- Updated the readme regarding changes to physics body sizes before enabling
  slopes (#6).

## v0.1.0 - 22nd May 2016
- Collision pulling; an alternative approach to sticky slopes.

## v0.1.0-beta - 15th May 2016
- Friction for physics bodies and tiles
- Collision callback support, including `physics.arcade.collide()` calls,
  tile-specific callbacks and layer-level tile callbacks
- Initial sticky slopes functionality
- Arcade body properties that configure interaction with tiles
- Tile slope type name retrieval

## v0.1.0-alpha3 - 11th May 2016
- Further improved heuristics

## v0.1.0-alpha2 - 10th May 2016
- Fixed heuristics not working after disabling and re-enabling the plugin at
  runtime
- Fixed some heuristics rules

Lesson learned: Heuristics are unreliable!

## v0.1.0-alpha - 8th May 2016
- Initial functionality (in development since 19th April 2016)
  - 24 new tile types
  - SAT-driven collision solver using SAT.js
  - SAT restraints based on heuristics that prevent AABBs catching on hidden
    edges
  - Works with sprites, groups and particle emitters!
