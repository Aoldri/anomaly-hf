# 2.1.1
## Bug Fixes
- Fix loner traders not having loner-specific items
- Fix crashing on 4:3 resolutions when opening radial menu

# 2.1.0
## Features
- Create save game migration system
  - Old saves using 1.1.4 should now just work™

## Bug Fixes
- Remove debug prints in WTF module

## Code Refactoring
- Remove deprecated callbacks

## Builds
- Tick default options in fomod

# 2.0.0
## Breaking Changes
- This update requires 1.5.2 modded exes
- Significantly refactored code, including script binders which means any third-party furniture will need to be updated for this version

## New Features
- Added a mode to placement system: Automatic Surface Alignment
- Added a mode to placement system: Intuitive Controls
- Created a primitive data store for furniture (e.g. fuel)
- Added 'World Objects': Ability to add objects that spawn once in the world
  - Lights will have infinite duration
  - Objects cannot be picked up
  - See guide for how to add world objects
- Added 'Creative Mode': Ability to select and place objects without needing to use their item variant
- Enabled Autoplay on the piano to continue outside of the UI
- Added Quick Use on single tap and a generic Radial Menu on hold when using the interact key on furniture

## New Objects
- Weapon Displays, by Utjan

## Bugfixes
- Fixed supply level 3 overriding supply level 2 for renegades
- Fixed bounding box not detecting dynamic objects

## Other
- Restructured the mod into the FOMOD format, placing various objects into distinct thematic modules
- Restructured MCM settings into categories, which will probably revert settings from previous versions

# 1.1.4
- Fixed crash when interacting with lights with a non 16:9 resolution
- Fixed Gun Case stashes not appearing in trader inventories

# 1.1.3
- Fixed crash when transferring a lot of zero-weight items between stash and inventory

# 1.1.2
- Fixed music sheets with strange pauses (they had spaces preceding new lines)

# 1.1.1
- Removed wpn_aks74u and wpn_protecta from list of weapons for repair task in WTF

# 1.1.0
- Fixed strange pauses when using Autoplay on piano sheets
- Fixed sheets cutting off part-way when switching between sheets in Piano UI
- Removed debugging prints that would flood the error log (Sorry!)

# 1.0.0
- Changed radio to move the needle texture independently on the background image
- Added guides for adding decorative props, more furniture with existing functionality, piano sheets, and radio stations.
- Added code and ui for decorative props
- Added example for decorative props (very cursed, not very funny)
- Made WTF optional and moved into an optional folder
- Made Portable Workshops available at Supply Level 3 at all factions
- Made Psi Light available at Ecologists and Monolith at Supply Level 3
- Checked HF and WTF works with 1.5.2 (send logs if something breaks)
- Added (D)LTX file for stash capacities to differentiate between player's backpack stashes and world stashes
- Decreased sound of the gas lamp
- Revamped placement system of objects (lazy to record, very cool though)
  - to show bounding box and rotation of object via particles
  - to allow looking around the object prior to placing
  - to allow adjustment of the object up and down
  - to nudge spawned objects so they fall when placed (rip earphones)
- Added more translation strings
- Added trade profile to make all factions the same in selling the furnitures.