# Mini Minecraft 2fort Map for Team Fortress 2

A small map for intimate matches and fast pasted action! Blue and Red forts are identical. There are two teleporters in each tunnel and the central stone structure is boobytrapped with TNT... Careful!

My first map. Original map design built in Minecraft and used as a reference in Hammer++ to build the final map.

[Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2998450868)
## Compilation

Baked Lighting:
>Sun Samples: 128
>
>Ambient Samples: 512
>
>Visible Samples 2048
>
>Light Radius, Brightness Scale: 1
>
>Ambient Occlusion Scale: 1
>
>Bounced Light, HDR Lights, Light bleed hack, Cubemap, Soften Cosine: TRUE/Checked

Running the map:
>$bsp_exe -game $gamedir $path\$file
>
>$light_exe -both -game $gamedir $path\$file
>
>$vis_exe -game $gamedir $path\file
>
>$bsp_exe -game -final* $gamedir $path\$file
>
>Copy File $path\$file.bsp $bspdir\$file.bsp
>
>(optional) $game_exe -dev -console -allowdebug -hijack -game $gamedir +map $file **

\* '-final' flag is optional. '-final' flag compilation takes longer.

\** this line is optional. this runs the game after compilation.

##Future Goals:

1. Add an underworld 'nether', accessible by the central stone structure. It should be a clone of the overworld, with a dystopian, hellian twist.
1. Add hidden rooms accessible by the two 3x3 areas next to the forts on each side of the map. These could be homages to other TF2 Minecraft themed maps or something original.
1. Decorate the forts with decorative blocks, such as picture frames and plants.

## Credits
- Map created and compiled with [Hammer++](https://ficool2.github.io/HammerPlusPlus-Website/index.html).
- Textures, Materials, Sounds by Mojang. Compiled with [VFTEdit](https://valvedev.info/tools/vtfedit/).
- Skybox [MCLite](https://gamebanana.com/mods/7260) by HaZZaRDouZ.
