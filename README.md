# Magnificent Desolation

A modular Kerbal Space Program planet mod in a desolate but beautiful multiple-star system.

## Dependencies: 
* Kopernicus: https://github.com/Kopernicus/Kopernicus/releases
    * HarmonyKSP: https://github.com/KSPModdingLibs/HarmonyKSP/releases
	* ModuleManager: https://ksp.sarbian.com/jenkins/job/ModuleManager/163/artifact/ModuleManager.4.2.3.dll
	* ModularFlightIntegrator: https://ksp.sarbian.com/jenkins/job/ModularFlightIntegrator/40/artifact/ModularFlightIntegrator-1.2.10.0.zip
	* KSPTextureLoader: https://github.com/Phantomical/KSPTextureLoader/releases
* Kopernicus Expansions: https://github.com/VabienArt/KopernicusExpansion-Continueder/releases
* Scatterer: https://github.com/LGhassen/Scatterer/releases
    * You do *not* need to install StockScattererConfigs.
* MultiStarRings: https://github.com/jabaworks/MultiStarRings/releases

## Included Mods:
* ScientificRevolution: https://github.com/StollD/SciRev
* VertexMitchellNetravaliHeightmap: https://github.com/jamespglaze/VertexColorMapEmissive
* VertexColorMapEmissive: https://github.com/jamespglaze/VertexColorMapEmissive

## Recommended Mods:
* E.V.E. True Volumetric Clouds V5: https://www.patreon.com/blackrack/posts/true-volumetric-139879553
    * Only the paid version, version 5, is currently supported.
	* you must install StockVolumetricClouds, which is included.
	* You do *not* need to install StockScattererConfigs.
* Distant Object Enhancement: https://github.com/net-lisias-ksp/DistantObject/releases
* KSP Community Fixes: https://github.com/KSPModdingLibs/KSPCommunityFixes/releases
    * Go to the in-game settings menu and disable the stock maneuver planner tool, which can cause various issues.
* Transfer Window Planner: https://forum.kerbalspaceprogram.com/topic/84005-112x-transfer-window-planner-v1800-april-11/
    * Although we have seen some bugs in this system, where the planner computes transfer delta-v in the trillions of meters per second in some situations, so keep an eye out for that.

Magnificent Desolation is a modular planet pack taking place in a system orbiting around an intermediate-mass black hole. Other stars are only a few dozen to hundred astronomical units distant--much closer than interstellar distances, but a fair bit further than typical interplanetary distances, and with higher delta-v requirements to boot.

Current modules are:
* MagDes_Core (Auox the black hole, and all of the stars (but without planets.)
* MagDes_Haun (The main home system, beginner-friendly orange dwarf system.)
* MagDes_Ada (A red dwarf star with a compact system of planets.)

MagDes is intended as a System Replacer that removes the Kerbol System, but in future there may be an interstellar destination patch that makes it an additional system visitable from Kerbin by interstellar travel.

## System Layout

Auox central cluster:
* Helva (Lone M-dwarf)
* Kareen (Lone K-dwarf)
* Drados (Lone T-dwarf)
* Ubun (Lone Solar analog G-dwarf)

Rengal System:
* Remi (Binary M-dwarf)
* Revo (Binary M-dwarf)

Ada System:
* Ada (Ultracool M-dwarf)
* Ve'Eel (Small, largely molten planet)
* Ve'Lic (Small, partially molten planet)
* Ve'Gor (Small planet)
* The Synestia (Aftermath of recent giant impact)

Haun System: 
* Haun (K-dwarf) 
* Irecula (small planet)
* Revel (Martian Venusian hybrid)
* ?
* ?
* Limnus (Scarred, ringed homeworld)
    * Phenom, Otempta, and Trendle, the exceptionally small single-biome moonlets.
	* Pheber (large asteroid)
	* Phenix (Recycled moon)
	
## Developer Commentary

A new science experiment part has been added, the Developer Commentary Record. Based on the Voyager golden record, it is a nice decorative part for any craft, but its science definitions are fourth-wall-breaking commentary by the developers. The experiment produces no science points. The part *will* work on its own, but we recommend you install Resurfaced (https://forum.kerbalspaceprogram.com/topic/225920-resurfaced-backwards-compatible-pbr-stockalike-shaders-for-ksp-v12ksp-1125/) for better PBR rendering of the gold material.

## Known Issues:
* On Demand Textures are sometimes slightly fussy, if you have planets where normals are broken and/or missing textures, try reloading the game, this usually fixes the issue.
* Science Balance may be slightly off for Limnus and its neighboring planets, and hasn't been considered for other planets, I wouldn't recommend MagDes Prealpha ready for a science/career experience
* As with all mods that reparent the homeworld, the KSC scene is completely messed up when you first load a save, and there may be some other visual bugs in the tracking station, or in the map when viewing Limnus while orbiting another object.
* The multi-star rings have some weird semicircular shadows in localspace.