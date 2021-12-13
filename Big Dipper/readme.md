# Weedo X40 transition into RepRap Firmware printer using Fysetc Big Dipper

You need:
* Weedo X40(v2)
* [Fysetc Big Dipper](https://github.com/FYSETC/FYSETC-BIG_DIPPER)
* Wires
* [JST SM](https://amzn.to/3GhMfW4) & [JST XH](https://amzn.to/3omI1pY)
* Good Crimping Tool [ENGINEER PA-09](https://amzn.to/3os2x8O)
* Printed Holder (best in ABS (plus) and 5 outer perimeters)


## Wire Diagram
This is how I wired the IDEX printer with his two extruders, dual axis and all endstops.
![Pinning 1](pictures/Folie1.PNG)
![Pinning 2](pictures/Folie2.PNG)

If it is not clear to see, I also did some pictures.
For the Y and both Z Motors, I used the exising cables. For both E and X I bought new cables with 1m length.

<img src="pictures/Steppers.jpg" width="300">


For the Fans on the Hotend you need to set the Jumpers to 24V. See the pinning on the picture.

<img src="pictures/fans.jpg" width="300">

Also for the Endstops and the proximity sensor the Pinning is very impotant. There is no polarity but you have to take the right PINs in the JST-XH connectors.

<img src="pictures/endstops1.jpg" width="300">
<img src="pictures/endstop2.jpg" width="300">

## PINout

## Pinning
Tasks
1. update the Wireing, where the ribbon cables are. 
2. Install the Big Dipper using the holder into the original place.
3. cableing
4. (open) Firmware
