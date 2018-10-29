# Xcode `.usdz` file converter 
Make sure Xcode 10 is installed and change the command line tool to the latest version at 
 `Xcode > Preferences > Locations > Command Line Tools`

## Static Model
>Visualize

* xcrun usdz_converter
* ~/Desktop/quickLook/PokemonStatic.obj 
* ~/Desktop/quickLook/usdz/PokemonStatic.usdz 
* -color_map ~/Desktop/quickLook/textures/color.jpg 
* -normal_map ~/Desktop/quickLook/textures/normal.jpg 
* -roughness_map ~/Desktop/quickLook/textures/roughness.jpg 
* -ao_map ~/Desktop/quickLook/textures/ao.jpg

>example command line (copy and paste it in your terminal)

`xcrun usdz_converter ~/Desktop/quickLook/PokemonStatic.obj ~/Desktop/quickLook/usdz/PokemonStatic.usdz -color_map ~/Desktop/quickLook/textures/color.jpg -normal_map ~/Desktop/quickLook/textures/normal.jpg -roughness_map ~/Desktop/quickLook/textures/roughness.jpg -ao_map ~/Desktop/quickLook/textures/ao.jpg`


## Animated Model (Alembic file)

>Visualize

* xcrun usdz_converter 
* ~/Desktop/quickLook/Pokemon.abc 
* ~/Desktop/quickLook/usdz/PokemonAnimated.usdz 
* -x lvysaur -color_map ~/Desktop/quickLook/textures/color.jpg 
* -normal_map ~/Desktop/quickLook/textures/normal.jpg 
* -roughness_map ~/Desktop/quickLook/textures/roughness.jpg 
* -ao_map ~/Desktop/quickLook/textures/ao.jpg 
* -g snow 
* -emissive_map ~/Desktop/quickLook/textures/white.jpg 
* -roughness_map ~/Desktop/quickLook/textures/roughness_white.jpg 


>example command line (copy and paste it in your terminal)

`xcrun usdz_converter ~/Desktop/quickLook/PokemonAnimated.abc ~/Desktop/quickLook/usdz/PokemonAnimated.usdz -x lvysaur -color_map ~/Desktop/quickLook/textures/color.jpg -normal_map ~/Desktop/quickLook/textures/normal.jpg -roughness_map ~/Desktop/quickLook/textures/roughness.jpg -ao_map ~/Desktop/quickLook/textures/ao.jpg -g snow -emissive_map ~/Desktop/quickLook/textures/white.jpg -roughness_map ~/Desktop/quickLook/textures/roughness_white.jpg`


