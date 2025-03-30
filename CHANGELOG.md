# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.4.0] - 2025-03-30

### Added

- Abras Magic Maps - AMM_Hexes (adjusted spawns, adjusted viewport, added more saws, hanging saws now move through maze non-deterministically [they may get stuck for a while]; static saws now animated)
- Bopl Battle Maps - DiagSpam (no spawns)
- Bopl Battle Maps - Ice10 (no spawns)
- mapsforbigmen - indatortjong (no spawns, saws piling up before reaching stage)

### Fixed

- Some maps displaying the wrong name in-game.

### Changed

- Description to indicate 8 player support.
- rpm_birdhouse: adjusted rope placement, spawn placeement; added spawns to support 8 players
- rpm_fix_AMM_thinBridge: added spawns to support 8 players
- rpm_fix_Crusher: added spawns to support 8 players
- rpm_fix_empty: added spawns to support 8 players
- rpm_fix_Rattunnels: added spawns to support 8 players
- rpm_fix_v4_map8_såg trap: added spawns to support 8 players; adjusted viewport

## [1.3.0] - 2025-03-29

### Added

- CoolDromianMaps - loveisintheair (no spawns)
- CoolDromianMaps - temple (no spawns)
- KingCookedBread Map Pack - Crusher (machine getting stuck on impact, moving slowly, failing to start)
- List of included maps w/ link to original mod to README to assist with disabling broken levels and to give credit to original artists.

### Changed

- Icon art.
- Package description.

## [1.2.0] - 2025-03-27

### Added

- The Spectra Levels - v4 map1 (no spawns, added bridge and animation consistent with finished level)
- The Spectra Levels - v4 map5 sågar å sånt (no spawns, adjusted spacing of saws so they dont become stuck, added return chute)
- The Spectra Levels - v4 map7 zing zing (no spawns, adjusted animation timings to be visible and slightly out of sync, added platforms instead of flat balls)
- The Spectra Levels - v4 map8 såg trap (adjusted "trap" spacing so saws no longer get stuck [and have a slight chance of falling down activation tunnel])
- The Spectra Levels - v4 map10 massa låda (no spawns)
- WackyMapObjects, UnboundLib, MM Hook, and BepInEx to dependencies.

### Changed

- rpm_birdhouse: added weights to bottom of cage for stability.

## [1.1.0] - 2025-03-26

### Added

- Changelog
- Abras Magic Maps - AMM_Catapult (catapult collapsing, immediately firing saws)
- Abras Magic Maps - AMM_DodgeSaw (flat saw falling before it reaches the stage)
- Abras Magic Maps - AMM_FloatBox (machine not working)

### Fixed

- rpm_birdhouse: physics causing instant death
- rpm_fix_empty: rightmost wall misaligned.

### Changed

- Map names to rpm_{fix (if maps is a fix)}_{original map name}.

## [1.0.1] - 2025-03-25

### Changed

- Added joints to puppet.

## [1.0.0] - 2025-07-14

### Added

- Abras Magic Maps - AMM_Maze (saws not moving/getting stuck)
- Abras Magic Maps - AMM_Puppet (puppet getting stuck)
- Abras Magic Maps - AMM_thinBridge (no spawns)
- CoolDromianMaps - empty (no spawns)
- mapsforbigmen - Rattunnels
- birdhouse (original map? I can't find an original and it's been a while since I've opened these)

