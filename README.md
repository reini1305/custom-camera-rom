# 2bit PXLR Studio
![2bit PXLR Studio Logo](assets/2bitpxlr.png "2bit PXLR Studio")

**2bit PXLR Studio** is a custom ROM ("firmware") for the Game Boy Camera targeted on accessing the full potential of the original Game Boy Camera's sensor, as well as giving photographers more control.   
It is meant to be used with [HDR's flashable Game Boy Camera PCB](https://github.com/HDR/Gameboy-Camera-Flashcart).   
You can tag your images with [#2bitpxlr](https://www.instagram.com/explore/tags/2bitpxlr/).   

## Current features:
+ Most settings of the camera's sensor are already configurable:
  + Sensor gain
  + Exposure time
  + Dithering matrices
  + All edge enhancement settings
  + Output node bias voltage
  + Zero point calibration
  + Output reference voltage offset
+ Raw image data can be saved to the same positions where the original ROM stores it's data.
+ Sensor settings are being saved across restarts. To reset hold `start`+`select` on boot

## Missing features:
If you're missing a feature, [check the issues](https://github.com/HerrZatacke/custom-camera-rom/issues) if it has already been discussed.   

# Contributing
* Logo/Splashcreen created by [@rembrandx](https://www.instagram.com/rembrandx/)

_This project is very much a work in progress._  
Join the [Game Boy Gamera Club Discord](https://discord.gg/C7WFJHG) for discussions in detail. And feel free to check and add to [this project's issues](https://github.com/HerrZatacke/custom-camera-rom/issues)  

# Feedback
**Remember: I can only improve things I know about!!**  
If you have actually used this ROM any type of feedback is very much appreciated. This includes but is not restricted to things like:
+ "I'd like to have feature XX"
+ "I've used the following combination of parameters which work really well/bad"
+ "When I set param XX, I'd also like param YY to change"

# Building
This project has been created with [GBDK 2020](https://github.com/gbdk-2020/gbdk-2020).  
This project requires an environment variable `GBDK_FOLDER="..."` pointing to the `bin` folder of GBDK  
E.g. on wsl for windows add `export GBDK_FOLDER="/mnt/c/path_to_gbdk/bin"` to your `.bashrc`

# Research and related projects
- [Documentation regarding the sensor by AntonioND](https://github.com/AntonioND/gbcam-rev-engineer) [PDF](https://github.com/AntonioND/gbcam-rev-engineer/blob/master/doc/gb_camera_doc_v1_1_1.pdf)
- [References regarding the Game Boy Camera's sensor](https://github.com/Raphael-Boichot/Play-with-the-Game-Boy-Camera-Mitsubishi-M64282FP-sensor)
- Mitsubishi [Sensor Datasheet](https://pdf1.alldatasheet.com/datasheet-pdf/view/146598/MITSUBISHI/M64282FP.html)
- I also received a lot of help and ideas from the [Game Boy Gamera Club Discord](https://discord.gg/C7WFJHG)

# License
This project is released under the [MIT License](LICENSE)
