# DanceDanceRevolution White Cabinets
Known as "white cabinets", this model of arcade cabinet was introduced by Konami in 2013. The monitor runs at 1280x720 at 60fps. This is the most common type of cabinet running e-amusement in the United States, primarily found at Round1, Dave & Busters.

Inside the cabinet, you will find a BemaniPC, likely an [ADE-704A/HM64](https://jeffreyatw.com/blog/2019/03/types-of-ddr-cabinets-and-pcbs/#bemani-pc-ade704ahm65) or similar model.

Because most models of this cabinet do not enable the extra DVI ports on the motherboard for video mirroring, the recommended method to get an extra video feed for capture is to use a powered DVI splitter with EDID mirroring.

Additionally, you will need either a stereo 3.5mm splitter, or RCA splitters, depending on how you wish to capture audio.

## Items Needed
* Powered DVI splitter [link](https://www.amazon.com/gp/product/B084LK5S5Q)
* 2xRCA or 1x stereo 3.5mm splitter
* RCA cables or 3.5mm cable, at least 10' in length (depending on what type of splitter you use)
* 2 DVI cables (One DVI cable should be 3-6' in length, the other should be at least 10' in length)
* A capture card capable of capturing DVI signals, and any necessary adapters. One known good card is the [StarTech USB3HDCAP](https://www.amazon.com/StarTech-com-USB3HDCAP-Video-Capture-Device/dp/B00PC5HUA6).

## Install Process
### Video
1. Turn off power to the machine. The safest way to do so is to turn off the power switch located inside the coin door. This will ensure that the machine remains grounded while working, reducing the risk of ESD damage to the machine.
2. Open the lower panel on the rear of the machine. This panel is typically secured with a single tubular lock located at the top center of the panel, or screws located in the top corners.
3. Disconnect the DVI cable from the port labled DVI-2 on the motherboard of the BemaniPC, and connect it to Output 1 on the DVI splitter.
4. Connect the shorter DVI cable to the port labeled DVI-2 on the BemaniPC, and the Input port of the DVI splitter.
5. Connect the long DVI cable to Output 2 on the DVI splitter.
6. Connect the power adapter barrel conector to the DVI splitter, and route the adapter to a power source.
7. Proceed to the appropriate Audio section depending on what type of cable and splitters you have.

### Audio - 3.5mm
1. With the machine still shut down, unplug the 3.5mm audio cable from the motherboard of the computer, from the port labeled "Green" and plug it into one of the outputs of the 3.5mm splitter.
2. Connect the 3.5mm audio splitter to the port labeled "Green"
3. Connect the new 3.5mm audio cable to the second port of the audio splitter

### Audio - RCA
1. On the P2 side of the machine, you will see two audio amplifiers. Disconnect the RCA cables from the audio amplifier closer to you.
2. Install the in-line RCA splitters onto the audio amplifier board, being careful not to damage the board-mounted RCA jacks.
3. Connect the existing RCA cables from the machine to one of the jacks on the splitter
4. Connect the new RCA cables to the other jacks on the splitter

### Finishing Up
1. Carefully route cables inside the machine, attempting to avoid running parallel to any wires that are brown, green or blue, as these are AC voltage lines, and may cause interference to audio or video signals.
2. Place the video splitter in a safe location. If this will be permanently installed, it may be wise to mount the splitter with two-sided-tape to an open panel, leaving the ports accessible for service. Take care not to pinch or excessively bend any cables.
3. Route the audio and video cables out the service slot on the bottom left corner of the rear of the machine, where the power and network cables come out.

## Streaming
### Booting
When booting the cabinet for the first time after installing the splitter, you will want to ensure that the audio and video signals are working as expected. You may do this either by allowing the cabinet to boot to the game software and playing a test credit, or by using the audio and video test functions in the service menu.

Some models of cabinet may misbehave and shrink the output of the video if a capture card is connected to the second output of the splitter when the cabinet boots. If this occurs, disconnect anything from Output 2 (it is ok to leave the cable connected), and reboot the cabinet.

### Capture Card
Once you have verified that the audio and video are working properly, you should test your capture card. Boot the machine, wait for the game to load, and then connect your streaming equipment.

### Disconnecting
After your streaming event has finished, you will want to clean up the area of the cabinet. If you have permission from the cabinet owner, you may wish to leave the streaming equipment installed. If not, remove the equipment and restore the hardware to its original configuration.