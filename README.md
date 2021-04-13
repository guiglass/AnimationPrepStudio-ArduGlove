# AnimationPrepStudio-ArduGlove
DIY Arduino/SteamVR motion capture gloves for AnimationPrepStudio. 


![Ardugloves](https://raw.githubusercontent.com/guiglass/AnimationPrepStudio-ArduGlove/master/IMG/IMG_0291.jpg)

Files for assembling and programming a (super low latency) "DIY" motion capture glove using an Arduino and 5x SEN-08606 Flex Sensor 4.5" for each finger and a Vive tracker that is strapped to the 3D printed hand strap.

nRF24 wireless receiver: https://www.sparkfun.com/products/705
10k ohm flex sensors: https://www.spectrasymbol.com/wp-content/uploads/2019/07/flexsensordatasheetv2019revA.pdf
Boneduino with nRF24 raido: http://duinopeak.com/index.php?route=product/product&manufacturer_id=9&product_id=30

![Ardugloves](https://raw.githubusercontent.com/guiglass/AnimationPrepStudio-ArduGlove/master/IMG/ardu_glove1.jpg)




The files in this git include:
Laser cutter files for cutting the flex sensor sleeves (if needed).

The 3D printer files are include to make the hand strap that hold the Vive trackers.

The Arduino files are used to program the Arduino/Boneduino to communicate with AnimationPrepStudio via a serial com port.

Two Arduino examples are shown, one is a hard wired simple serial example, the other is the nRF24L01 wireless example.


With 3D printable tracker holder:

[![ArduGlove](https://raw.githubusercontent.com/guiglass/AnimationPrepStudio-ArduGlove/master/IMG/68747470733a2f2f692e696d6775722e636f6d2f76774d755734332e706e67.png)](https://raw.githubusercontent.com/guiglass/AnimationPrepStudio-ArduGlove/master/IMG/68747470733a2f2f692e696d6775722e636f6d2f76774d755734332e706e67.png)

[![3D printed tracker holder parts](https://raw.githubusercontent.com/guiglass/AnimationPrepStudio-ArduGlove/master/IMG/IMG_E0554.JPG)](https://raw.githubusercontent.com/guiglass/AnimationPrepStudio-ArduGlove/master/IMG/IMG_E0554.JPG) 

[![3D printed tracker holder parts](https://github.com/guiglass/AnimationPrepStudio-ArduGlove/blob/master/IMG/Iv2EuKu.png)](https://github.com/guiglass/AnimationPrepStudio-ArduGlove/blob/master/IMG/Iv2EuKu.png) 

Optionally you may use cotton gloves and simply glue the sensor pouches to directly to the glove (this designe is very simple yet very effective):
[![sensor sleeves](https://raw.githubusercontent.com/guiglass/AnimationPrepStudio-ArduGlove/master/IMG/udh153.png)](https://raw.githubusercontent.com/guiglass/AnimationPrepStudio-ArduGlove/master/IMG/udh153.png)
