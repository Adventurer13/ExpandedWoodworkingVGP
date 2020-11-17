# Change Log

**Current:** [v1.2.2.0](https://github.com/Adventurer13/ExpandedWoodworkingVGP/releases/tag/v1.2.2.0 )

## [1.2.2.0] - Unreleased
### New
- Beauty values for each wood and lumber.
- Assorted Tree support within VGPXtraTrees.
- Support for VGP Garden Drinks UF.
- Mango Tree support within VGP More Veggies.

### Fixed
- Fine Ironwood floor to use lumber instead of logs.
- Woodworking tables use updated recipe sounds when crafting lumber. 
- PatchOperation clean-up.

## [1.1.1.0] - 2020-03-08
### New
- Assembly file using .NET Framework 4.7.2 and added UnityEngine.CoreModule as a reference.
- Folder structure separating versions 1.0 and 1.1 of Rimworld and using LoadFolders.xml for 1.1 and future versions.
- Add package Id: Adventurer.ExpandWoodworkVGP and updated About.xml to work with the Auto-sort button.
- Updated Bamboo and Ironwood stats.
- Changed def 'LumberIronwood' to 'VG_LumberIronwood'. Affects recipe def as well.
- VGP Garden Fabric patch to allow Tier 1 loom table to be made out of logs as well.
- Optional Dyes barrel patch for VGP Garden Dyes (requires user to uncomment patch to use).

### Fixed
- Base Lumber Recipe to be in-line with main mod.
- VGP Garden Drinks patch to modify the drinks table to no longer require mixed lumber for a general increase in cost.
- VGP Garden Tools patch to include bulk compost as well.

## [1.0.1.3] - 2019-11-24
### Fixed
- Acacia mass statFactor not applying when using VGP and CE.
- Russian localisation (by DiamondGrace}

## [1.0.1.2] - 2019-06-11
### New
- Added mass statFactors to VGP VG and Xtra Trees logs and lumber for Combat Extended compatibility.

### Removed
- Old fuel patching system within VGPXtraTrees.

## [1.0.1.1] - 2019-02-18
### New
- Ironwood floor uses lumber.

### Fixed
- Multi-version changes.
- Balanced Ironwood in line with VG changes.

## [1.0.1.0] - 2018-10-17
### New
- Updated version to 1.0 release of Rimworld.
- Updated readme to contain helpful information on bare starting scenarios.
- Added separate license file.
- Fluffy's Mod Manager support.

### Removed
- Rimworld alpha/beta version in the name.

## [0.19.1.0] - 2018-09-16
### Fixed
- Errors resulting from update to B19 of Rimworld and VGP.
- Assembly updated.

## [0.18.0.4] - 2018-07-11
### New
- Readded support for the other cultivated fruit trees since they were readded by Vegetable Garden.
- Russian language localisation by lex1975.
- ModSync RW support.

### Fixed
- Tree defintions overwriting the tree changes made by plant density mods and the VGP fruit tree defintions.

### Removed
- ThingDefs_Plants files and folder as it is no longer needed.

## [0.18.0.3] - 2017-12-31
### Fixed
- Fuel filter patching edited to coincide with the change in Expanded Woodworking.

### Removed
- Patch files for specifically VGP Vegetable Garden and VGP Garden Gourmet as they only edited the fuelFilter.

## [0.18.0.2] - 2017-12-15
### New
- ModSync Ninja support.

## [0.18.0.1] - 2017-12-04
### New (save needed for B18 if switching from A17)
- Assembly updated.
- With changes of Vegetable Garden to Vegetable Garden Project, changes are being made to how this mod is structured.
- VGP Vegetable Garden mod is required.
- VGP Xtra Trees and Flowers support is entirely through a patch, so it is not needed if you don't want to use it.
- Support for Wood fired generator and VGP's bamboo campfire.
- Moved Lighting, Power, Production, Temperature into patching system for better compatibility with other mods as well as
  Rimworld updates editing such as well.
- Individual lumber recipies! (looking for feedback on)
- Compost starter uses logs.
- Languages folder added. (Who wants to translate?)

### Fixed
- Balancing for stats (door open speed, beauty, mass, market value, etc.). Looking for feedback regarding these!
- Something I likely forgot, so updates across the defs.

### Removed
- Olive tree producing wood (as a result of this change in VGP).
- Original generator.

## [0.17.0.4] - 2017-08-09
### New
- Updates to C sharp code to iron out any issues that may be caused by old.
- Source is actually now available (Only on Github). Respect attached license!
- Including Changelog & Readme in Steam releases.

## [0.17.0.3] - 2017-07-31
### Removed
- Ironwood as a fuel.

## [0.17.0.2] - 2017-07-20
### New
- Brought the wild fruit trees Vegetable Garden intorduces into the code. This means there will no longer be two of the same 
  fruit tree where only one of them would drop wood. It is now one fruit tree that drops wood and fruit.
- Brought the rarity of trees in-line with how Vegetable Garden has it. (Let me know if you think this is too few.)
- Some code changes to reflect changes made in Vegetable Garden.

## [0.17.0.1] - 2017-07-20
### New
- Updated to work with A17.

## [0.16.0.5] - 2017-02-20
### New
- Minor code change in compliance with latest version of Expanded Woodworking.

## [0.16.0.4] - 2017-02-17
### New
- Substantial code cleanup.
- Fruit trees now drop wood as well as fruit.
- Expanded Woodworking for Vegetable Garden is now dependent on Expanded Woodworking.

### Fixed
- Objects built with ironwood are no longer described as being made of willow.

## [0.16.0.3] - 2017-02-13
### New
- Log walls.
- Mixed lumber can be crafted by hand at a crafting spot.
- Woodworking tables are now stuffed for stone, wood, and metal.
- Torch lamps are now stuffed for raw logs.
- Horseshoe pines are now stuffed for raw logs.
- Passive coolers are now stuffed for raw logs.
- Campfires are now stuffed for raw logs.
- Deadfall traps are now stuffed for raw logs.
- The following neolithic weapons are now crafted with raw logs: Shivs, clubs, spears, pilas, short bows, and great bows.

## [0.16.0.2] - 2017-02-11
### Fixed
- The description of lumber recipes are now clearer.
- The mixed lumber recipe now gives the proper amount of lumber.
