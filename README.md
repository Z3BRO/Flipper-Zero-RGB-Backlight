![r2d9ahnjp-fnd-gif-iv2csr](https://user-images.githubusercontent.com/89728480/226134250-966746b9-74c1-461a-a6d4-82453af41d7c.gif)

<h1 align="center"> Flipper Zero RBG Backlight!!! </h1>

<h4 align="center"> <code>Big thanks to Quenon#1989, t.me/hitriy and axum#6461 for making this possible!</code></h4>

<h1 align="center">  Here are the links to everything you will need! </h3>


Capacitors - https://www.digikey.com/en/products/detail/kyocera-avx/06036C104JAT2A/1600414

Leds, Pack of 10
- https://www.digikey.com/en/products/detail/adafruit-industries-llc/4492/11569136
- https://www.adafruit.com/product/4492
- https://mouser.com/ProductDetail/Adafruit/4492?qs=CUBnOrq4ZJz3oeplDXDOWA%3D%3D		   

Thin gauge wire (I'm using 28 gauge because it is what I had) - https://www.amazon.com/Fermerry-Silicone-Stranded-Copper-Electrical/dp/B089CP9N98

When purchasing the PCB's make sure to have the thickness set to 0.6mm and the layer amount set as 2.

Showcase https://youtu.be/W1frMyVFv6Y


<h1 align="center"> Tutorials </h1>

## RGB Backlight Build Guides 

Video Guide Made by myself https://youtu.be/pft1CI5ikA4

Here is a Tutorial made by t.me/hitriy https://telegra.ph/Flipper-Zero-RGB-backlight-guide-12-26

Another Tutorial on how to remove the led backlight board (also made by t.me/hitriy) https://telegra.ph/Izmenenie-cveta-podsvetki-Flipper-Zero-11-14 you will need to translate it unless you speak Russian

## PCB Assembly

Here is a video I made on assembling the PCB https://youtu.be/N64fDjziTaE

<h1 align="center"> Firmware Stuff </h1>

All of the repos below have been modified with their respective patches (FW Made by Quenon#1989)

Unleashed - https://github.com/quen0n/unleashed-firmware-rgb

OFW - https://github.com/quen0n/flipperzero-firmware-rgb

# How to compile from the repos above 

Step 1: git clone --recursive FIRMWARELINKFROMABOVE


Step 2: ./fbt updater_package


Step 3: Navigate to dist\f7-D\ in the cloned repos folder ( Usually found at Documents\GitHub)


Step 4: Copy the f7-update-local folder to the Update folder on your Flipper


Step 5: On your Flipper Navigate to the Update folder


Step 6: Open the f7-update-local folder


Step 7: Update from the update.fuf file  ( It will have a picture of a box with an arrow next to it)


# How to update from the pre-compiled firmware

Step 1: git clone --recursive https://github.com/Z3BRO/Flipper-Zero-RBG-Backlight


Step 2: Navigate to the cloned repo ( usually its Documents\GitHub\Flipper-Zero-RBG-Backlight)


Step 3: Open the Update Files folder


Step 4: Copy the desired folder to the Update Folder on your Flipper


Step 5: On your Flipper Navigate to the Update folder


Step 6: Open the folder you just added to the SD card


Step 7: Update from the update.fuf file  ( It will have a picture of a box with an arrow next to it)





# Notes


Here is a video on how to use git patch files https://www.youtube.com/watch?v=ArbQNoNlFXk
