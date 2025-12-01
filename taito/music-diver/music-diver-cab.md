# Music Diver Cabinets
Music Diver was introduced by Taito in 2022. The monitor runs at 1920x1080 at 60fps. This is currently the only cabinet availaible for the game.

Inside the cabinet, you will find the [Taito X4](https://en.wikipedia.org/wiki/Taito_Type_X#Taito_Type_X4) pc.

The cabinet gets it's video output from the DVI port on the Taito PC. None of the other ports should output a mirrored video. With this in mind the recommended approach to capturing video is to use a DVI splitter with EDID mirroring and to capture from the second Output.

This setup will require 1 power outlet and 3 USB ports. None of the USB ports on the Taito PC should be used. There may be ways to reduce or change these requirements depending on your exact setup. While this setup should be able to run on any system, we tested and validated this setup with Windows. For those with other operating systems your mileage may vary.

## Items Needed
* Powered DVI splitter [link](https://www.amazon.com/dp/B08HS7TYYB)
* 2 DVI cables (One DVI cable should be 3-6' in length, the other should be at least 10' in length) examples: [3 foot](https://www.amazon.com/dp/B09QG7VQ51), [10 foot](https://www.amazon.com/dp/B09QGP67Q2)
* A capture card capable of capturing DVI signals, and any necessary adapters. One known good card is the [StarTech USB3HDCAP](https://www.amazon.com/StarTech-com-USB3HDCAP-Video-Capture-Device/dp/B00PC5HUA6).
* An Optical Audio to USB Input [link](https://amazon.com/dp/B0BQQLFQ59)
* An Optical Audio Splitter [link](https://amazon.com/dp/B0DT6LPZGY)
* 2 Optical Audio cables (One Optical Audio cable should be 3-6' in length, the other should be at least 10' in length) examples: [3 foot](https://amazon.com/dp/B00L3KO5WK), [10 foot](https://amazon.com/dp/B00L3KO3YU)

## Install Process
### Video
1. Turn off power to the machine. The safest way to do so is to turn off the power switch located inside the coin door. This will ensure that the machine remains grounded while working, reducing the risk of ESD damage to the machine.
2. Open the left panel on the front of the machine. This panel is secured with a single tubular lock located at the top center of the panel.
3. Disconnect the DVI cable from the graphics card of the Taito PC, and connect it to Output 1 on the DVI splitter.
4. Connect the shorter DVI cable to the DVI port on the graphics card of the Taito PC, and the Input port of the DVI splitter.
5. Connect the long DVI cable to Output 2 on the DVI splitter.
6. Connect the power adapter barrel conector to the DVI splitter, and route the adapter to a power source.
7. Proceed to the appropriate Audio section depending on what type of cable and splitters you have.

### Audio - Optical Audio
1. With the machine still shut down, unplug the Optical Audio cable from the motherboard of the Taito PC, and plug it into one of the outputs of the Optical Audio Splitter.
2. Connect the input of the Optical Audio Splitter to the motherboard of the Taito PC using one of the shorter Optical Audio Cable.
3. Connect the remaining output from the Optical Audio Splitter to the Optical Audio to USB Input using the longer Optical Audio Cable.
4. Connect the Optical Audio to USB Input to the Streaming PC.

### Finishing Up
1. Carefully route cables inside the machine, attempting to avoid running parallel to any wires that are brown, green or blue, as these are AC voltage lines, and may cause interference to audio or video signals. Most AC voltage lines will be located in the rear of the cabinet so as long as you do not route anything through the cabinet you should be good.
2. Place the video splitter in a safe location. If this will be permanently installed, it may be wise to mount the splitter with two-sided-tape to an open panel, leaving the ports accessible for service. Take care not to pinch or excessively bend any cables.
3. Route the audio and video cables out the open slot on the front of the cab.

## Streaming
### Booting
When booting the cabinet for the first time after installing the splitter, you will want to ensure that the audio and video signals are working as expected. You may do this either by allowing the cabinet to boot to the game software and playing a test credit, or by using the audio and video test functions in the service menu.

If the machine was not powered down before installing the splitter, the game may appear rotated on the monitor by 90 degrees. To fix this, you will need to power cycle the cabinet.

### Capture Card
Once you have verified that the audio and video are working properly, you should test your capture card. Boot the machine, wait for the game to load, and then connect your streaming equipment.

### Disconnecting
After your streaming event has finished, you will want to clean up the area of the cabinet. If you have permission from the cabinet owner, you may wish to leave the streaming equipment installed. If not, remove the equipment and restore the hardware to its original configuration.    