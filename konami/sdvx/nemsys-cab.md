# Sound Voltex Nemsys Cabinets (SDVX 5 and newer)
Known as "Nemsys cabinets", this model of arcade cabinet was introduced by Konami in 2011 with the original Sound Voltex game, Sound Voltex Booth. The monitor runs at 1920x1080 at 60fps, rotated 90 degrees clockwise. This is the most common type of cabinet running e-amusement in the United States, primarily found at Round1, however, they are being replaced by the newer Valkyrie model.

In 2018, Konami released Sound Voltex Vivid Wave, which required a full BemaniPC upgrade. All Nemsys cabinets running Vivid Wave or newer should match the hardware described in this document.

Inside the cabinet, you will find a BemaniPC. This BemaniPC uses a DVI output on the PCIe graphics card to output video to the monitor. To the author's knowledge, the DisplayPort and HDMI ports on the grahpics card are not typically set up to output video. As a result of this, the recommended method to get an extra video feed for capture is to use a powered DVI splitter with EDID mirroring.

Additionally, you will need a stereo 3.5mm splitter to capture audio

## Items Needed
* Powered DVI splitter [link](https://www.amazon.com/dp/B08HS7TYYB)
* 1x stereo 3.5mm splitter
* 3.5mm cable, at least 10' in length
* 2 DVI cables (One DVI cable should be 3-6' in length, the other should be at least 10' in length)
* A capture card capable of capturing DVI signals (1280x720 60fps), and any necessary adapters. One known good card is the [StarTech USB3HDCAP](https://www.amazon.com/StarTech-com-USB3HDCAP-Video-Capture-Device/dp/B00PC5HUA6).

## Install Process
### Video
1. Turn off power to the machine. The safest way to do so is to turn off the power switch located inside the coin door. This will ensure that the machine remains grounded while working, reducing the risk of ESD damage to the machine.
2. Open the front left panel on the front of the machine. This panel is typically secured with a single tubular lock located at the top center of the panel.
3. Disconnect the DVI cable from the DVI port of the graphics card of the BemaniPC, and connect it to Output 1 on the DVI splitter.
4. Connect the shorter DVI cable to the DVI port on the graphics card, and the Input port of the DVI splitter.
5. Connect the long DVI cable to Output 2 on the DVI splitter.
6. Connect the power adapter barrel conector to the DVI splitter, and route the adapter to a power source.

### Audio
1. With the machine still shut down, unplug the 3.5mm audio cable from the motherboard of the computer, from the port labeled "Green" and plug it into one of the outputs of the 3.5mm splitter.
2. Connect the 3.5mm audio splitter to the port labeled "Green"
3. Connect the new 3.5mm audio cable to the second port of the audio splitter

### Finishing Up
1. Carefully route cables inside the machine, attempting to avoid running parallel to any wires that are brown, green or blue, as these are AC voltage lines, and may cause interference to audio or video signals. Feed audio and video cables towards the back of the machine.
2. Place the video splitter in a safe location. If this will be permanently installed, it may be wise to mount the splitter with two-sided-tape to an open panel, leaving the ports accessible for service. Take care not to pinch or excessively bend any cables.
3. Open the lower panel on the rear of the machine, and route the audio and video cables out the service slot on the bottom of the rear of the machine, where the power and network cables come out.

## Streaming
### Booting
When booting the cabinet for the first time after installing the splitter, you will want to ensure that the audio and video signals are working as expected. You may do this either by allowing the cabinet to boot to the game software and playing a test credit, or by using the audio and video test functions in the service menu.

Some models of cabinet may misbehave and shrink the output of the video if a capture card is connected to the second output of the splitter when the cabinet boots. If this occurs, disconnect anything from Output 2 (it is ok to leave the cable connected), and reboot the cabinet.

### Capture Card
Once you have verified that the audio and video are working properly, you should test your capture card. Boot the machine, wait for the game to load, and then connect your streaming equipment.

### Disconnecting
After your streaming event has finished, you will need to clean up the area of the cabinet. If you have permission from the cabinet owner, you may wish to leave the streaming equipment installed. If not, remove the equipment and restore the hardware to its original configuration.