# Overview

Sets the maximum building slots per planet to 15.  Intended for use with [Basic Planetview: More Districts](https://steamcommunity.com/sharedfiles/filedetails/?id=2654043078).

Why does it only add 3 more buildings?  This is due to how the game's UI files are laid out.  The building box is set up in such a way that it is not possible to add scrollbars to it, so 15 is the highest amount of slots that can be added without overflowing the bottom of the intended display area.

Requested by [Ph00nix](https://steamcommunity.com/profiles/76561198804285928) - sorry it's only +3.

# Changes

One file that alters the define value `MAX_PLANET_BUILDING_SLOTS` from 12 to 15.  The graphical accommodation for this is handled in the parent mod.

## Compatibility

Built for Stellaris version 3.7 "Canis Minor."  This add-on is **not** achievement compatible because the maximum number of building slots is controlled by a game configuration setting.

Not compatible with other mods that also adjust the number of building slots.

### Required Dependency Mods

[Basic Planetview: More Districts](https://steamcommunity.com/sharedfiles/filedetails/?id=2654043078) makes the basic graphical changes to allow displaying 15 building slots.  If you do not use it, your planets will still have 15 building slots but only 12 of them will fit in the default UI.

### Recommended Companion Mods

[More Standard Districts](https://steamcommunity.com/sharedfiles/filedetails/?id=2650611194) adds 5 district types based on basic buildings: Research, Commercial, Leisure, Military, and Administrative.  Commercial Districts are not available for gestalt empires and Leisure Districts are only available for regular empires and Rogue Servitors.

### Not Included in "Subtle Polish"

This mod is intentionally not included in my modpack [Subtle Polish: A Collection of Fixes and Enhancements](https://steamcommunity.com/sharedfiles/filedetails/?id=2522974089) because it is an optional, basic UI change targeted at specific screen resolutions.

## Changelog

* 1.0.0 Initial version
* 2.0.0 Mark as compatible for Stellaris 3.3 version "Libra" - no script changes, but the parent mod is not backwards compatible
* 3.0.0 Mark as compatible for Stellaris 3.4 version "Cepheus" - no script changes, but the parent mod is not backwards compatible
* 4.0.0 Mark as compatible for Stellaris version 3.6 "Orion" - no script changes, but the parent mod is not backwards compatible
* 5.0.0 Mark as compatible for Stellaris version 3.7 "Canis Minor" - no script changes, but the parent mod is not backwards compatible

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/basic-more-districts-planetview-15-building-slots)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.