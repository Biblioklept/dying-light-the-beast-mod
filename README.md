# Dying Light The Beast Mod

### Mods Included
Version that is easier to patch but not the main version. Very vanilla friendly.

- [Skip Intro Videos](https://www.nexusmods.com/dyinglightthebeast/mods/1)
> Removes intro videos.
- [Disable Telemetry](https://www.nexusmods.com/dyinglight2/mods/20)
> Removes telemetry.
- [DLTB Retouched](https://www.nexusmods.com/dyinglightthebeast/mods/102)
> Introduces a bunch of quality of life tweaks.
- 2x XP.
	- Modifies scripts/player/player_variables.scr  
	Param("OpenWorldXPModifier", "2.0");  
	Param("OpenWorldNightXPModifier", "4.0");  
	Param("VehicleKillXPMultiplier", "0.10");
- More FOV
	- Modifies scripts/player/player_variables.scr  
	Param("CameraDefaultFOV", "73.0");
- Map Revealed
	- Modifies scripts/player/player_variables.scr  
	Param("FogOfWarViewRadius", "999999.0");
- Infinite Repairs
	- Modifies scripts/inventory/inventory_special.scr  
	MaxRepairCountByRarity(Color_White,	-1);  
	MaxRepairCountByRarity(Color_Green,	-1);  
	MaxRepairCountByRarity(Color_Blue,	-1);  
	MaxRepairCountByRarity(Color_Violet,	-1);  
	MaxRepairCountByRarity(Color_Orange,	-1);  
	MaxRepairCountByRarity(Color_Platinum,	-1);  
	MaxRepairCountByRarity(Color_Exotic,	-1);

### Other Recommended Mods
- [Play Online With Mods](https://www.nexusmods.com/dyinglightthebeast/mods/17)
> Disables multiplayer CRC check so it lets you play online with custom files/mods.
- [Increase Save Slots](https://www.nexusmods.com/dyinglightthebeast/mods/19)
> Increases save slots to 10, so you can have more than 4 saves.
- [Load Custom RPacks](https://www.nexusmods.com/dyinglightthebeast/mods/99)
> Makes you able to load custom named RPacks, with the ability to override vanilla .rpack content with yours, not needing to inject/repack rpacks every new update.