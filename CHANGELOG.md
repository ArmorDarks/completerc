# Changelog

## [1.0.0] — 2015-12-17
First stable release. There is _no changes_ in actual hakpacks. It's just maintenance update.

* Start using [semantic versioning](http://semver.org/)
* Repacked content
* Included simpler hills in release as optional hackpack

## Simpler hills replacement — optional hak
* Added simpler hills replacement pack as optional hak

## 0.985
* All previous haks merged into one `CompleteRC.hak`
* Added special crosser (`Terrain` > `Continuer Cobble`). That crosser must be placed at the end of the map, at the edges of cobble, raised cobble or water. After that crosser all titles that are beyond edges of the map will become cobble ones. See screenshot from v0.985 for demonstration.

## 0.984h
* `Alley` `mdl`s that were used with `Building Grass` terrain were bugged and crashed toolset. Fixed
* `Building Grass Alley` didn't have edge `mdl`. Fixed

## 0.984
* Added fort and fort wall tiles from Tom_Banjo's Forest Expansion + retextured + 3d grass added (`Terrain` > `Fort`, `Rural` > `Guard Post`, `Rural` > `Wall 2 Guard Shack`)
* Added in `wall 2` crosser tower from Tom_Banjo's Forest Expansion
* Added cliff and chasm stairs from original Bioware's forest + retextured (in hak used version from Tom_Banjo's Forest Expansion) (`Rural` > `Cliff stairs`, `Rural` > `Chasm...`)
* Added new raised terrain cliff (see screenshot). Use erase tool on raised terrain edge to find it
* `wall 2` crosser can be connected to cliff terrain. `mdl` imported from Tom_Banjo's Forest Expansion + retextured with rural's standard textures
* Fixed edge of raised terrain buildings

## 0.983h
* Color of the wall in `tw010_u06_05.mdl` was wrong. Fixed

## 0.983
* Added covered bridge. Thanks to Michael_DarkAngel for fixings and remodeling for DOA cliffs. Added two crossers instead of one to avoid bug with edge tiles. Can be found in `Terrain` > `Water Covered Bridge`
* Added stone bridge. `set`-file has been completely remade — now it's much easier to use. (`Terrain` > `Water Stone Bridge`)
* Added special tile `Road - end` that can be used with CCS gates to fit it properly (`Rural` > `Road - end`)
* Fixed `DOA Field` edges. That bug was in original DOA tileset. Strange that nobody fixed it before
* `tw010_a01_90.mdl` and `tw010_a01_99.mdl` have been deleted from set-file, since they were same as main cobble tile. If you will use this version with locations, that have been made prior to this change, you will see empty tiles in places, where had to be old cobble tiles. Don't panic — use <kbd>Ctrl</kbd>+<kbd>C</kbd> on any existing tile and then <kbd>Ctrl</kbd>+<kbd>V</kbd> on all empty tiles

## 0.982
* Added cobble edges as groups
* Now hak fully compatible with 1.69 patch
* Now hak can be used as replacement of DOA DOA City/Rural 2.1 + LOK XP1&2. Thanks to [virusman](https://github.com/virusman) for remake and now compatible with DOA `set`-file
* **NOT compatible with CompleteRC 0.98**

## 0.98
* Added ships
* Added ruins tileset
* Added `Roman Temple`
* Added `RuinCastle`
* Added DLA Trees tiles
* Added City Bridge crosser
* All models cleaned by [Clean Models 3.1](url=http://nwvault.ign.com/View.php?view=Other.Detail&id=1151)

## 0.9
* Renamed tileset to "Complete Rural/City" (`CompleteRC.hak`)
* Added terrain `Building grass` — city building tiles covered with grass + 3d grass
* Now crosser `Alley` can be used with terrain `Building grass`
* Added tiles from CCS `Features` with grass + 3d grass (wells, monuments and platforms). No covered with grass archways, roofs and bridge, because placeable `grass_extended` can be useed under them to achieve same effect.
* All CCS houses, covered with grass, now have 3d grass
* Some `mdl`s and `wok`s have been renamed to prevent possibility of errors occurring
* **NOT compatible with 0.8**

## 0.8
* Initial version