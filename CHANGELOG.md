# Changelog

## Simpler hills replacement — optional hak
* Added simpler hills replacement pack as optional hak

## 0.985
* All previous haks merged into one `CompleteRC.hak`
* Added special crosser (`Terrain` - `Continuer Cobble`). That crosser must be placed at the end of map at edges of cobble, raised cobble, water. After that crosser all titles that are below edges of the map will become into cobble one. See screenshot from v0.985 if you don't know how to use it properly.

## 0.984h
* `Alley` MDLs that was used with `Building Grass` terrain was bugged and crashed toolset. Fixed
* `Building Grass Alley` didn't have edge `mdl`. Fixed

## 0.984
* Fort and some fort wall tiles from Tom_Banjo's Forest Expansion was added + retextured + 3d grass added (`Terrain` - `Fort`) (`Rural` - `Guard Post`) (`Rural` - `Wall 2 Guard Shack`) (in wall 2 crosser tower was added)
* Cliff and chasm stairs from original Bioware's forest was added + retextured (in hak was used version from Tom_Banjo's Forest Expansion) (`Rural` - `Cliff stairs`) (`Rural` - `Chasm...`)
* New raised terrain cliff was added (see screenshot). Just use erase tool on raised terrain edge to find it
* Now wall 2 crosser can be connected to cliff terrain. Mdl imported from Tom_Banjo's Forest Expansion + retextured with rural's standard textures
* raised terrain - buildings edge was fixed

## 0.983h
* Color of the wall in `tw010_u06_05.mdl` was wrong. Fixed

## 0.983
* Added `Covered bridge`. All thanks to Michael_DarkAngel for fixings and remodeling for DOA cliffs. I have added two crossers instead one to avoid bug with edge tiles. Can be found in `Terrain` - `Water Covered Bridge`
* Added `Stone bridge` (set-file completely remade - now it is much easier to use it) (`Terrain` - `Water Stone Bridge`)
* Special tile `Road - end` that can be used with CCS gates to fit it properly (`Rural` - `Road - end`)
* `DOA Field` edges was fixed (that bug was in original DOA tileset. Strange that nobody fixed it before)
* `tw010_a01_90.mdl` and `tw010_a01_99.mdl` was deleted from set-file, 'cause it was same as main cobble tile. If you will use it add-on with locations, that was made before this change - you will see empty tiles in places, where have to be old cobble. Don't panic - use ctrl+c on any existing tile and then ctrl+v on all empty tiles

## 0.982
* Added cobble edges as groups
* Now hak compatible with 1.69 patch
* Set file have been remade by @virusman. Some things was corrected and now it fully compatible with DOA DOA City/Rural 2.1 + LOK XP1&2 (see compatibility notes for more info)
* **NOT compatible with 0.98**. Sorry for that, but it is better to fix it now than deal with bugs in future

## 0.98
* Added ships
* Imported ruins tileset
* Added Roman Temple
* Added RuinCastle
* Added DLA Trees tiles
* Included City Bridge crosser
* All models cleaned by [Clean Models 3.1](url=http://nwvault.ign.com/View.php?view=Other.Detail&id=1151)

## 0.9
* Tileset has been renamed to "Complete Rural/City" (completerc.hak)
* Added terrain `Building grass` — city building tiles covered with grass + 3d grass
* Now crosser `Alley` can be used with terrain `Building grass`
* Added tiles from CCS `Features` with grass + 3d grass (wells, monuments and platforms). I didn't added covered with grass archways, roofs and bridge, 'couse they don't have overrideable by placeable `grass_extended` walkmesh, so those placeable can be used to make it covered with grass. This measure will save a bit space in hak 
* All CCS houses, covered with grass, now have 3d grass
* Some `mdl`s and `wok`s have been renamed to prevent possibility of errors occurring
* **NOT compatible with 0.8**

## 0.8
* Initial version