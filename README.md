Baofeng UV5R TRRS Adapter
=========================
http://github.com/johnboiles/BaofengUV5R-TRRS

Tiny board that allows you to connect the Baofeng UV5R radio to a smartphone or other device that uses a TRRS connector for audio. Useful for connecting the radio to a software TNC app such as [APRSDroid](http://aprsdroid.org/) or [PocketPacket](https://itunes.apple.com/us/app/pocketpacket/id336500866?mt=8). Solder on the components, solder on the cables, then provide some stress relief (I use solid-core wire and heat shrink tubing), and you can use your UV5R with your smartphone for APRS on the cheap.

![Baofeng UV5R TRRS Adapter](http://johnboiles.s3.amazonaws.com/Screenshots/BaofengUV5R-TRRS-r3-Front.png)
![Baofeng UV5R TRRS Adapter](http://johnboiles.s3.amazonaws.com/Screenshots/BaofengUV5R-TRRS-r3-Back.png)

Pictures
--------

![The PCB and a US quarter](https://johnboiles.s3.amazonaws.com/Screenshots/BaofengUV5R-TRRS/r3-PCB-Quarter.jpg)
![The front of an assembled cable](https://johnboiles.s3.amazonaws.com/Screenshots/BaofengUV5R-TRRS/r3-Cable-Front.jpg)
![The back of the PCB with the cable ends](https://johnboiles.s3.amazonaws.com/Screenshots/BaofengUV5R-TRRS/r3-Full-Cable.jpg)

Notes
-----
A small capacitor and 3 resistors to trick the iPhone into thinking a microphone was connected. This part of the schematic was inspired by [this article](http://www.creativedistraction.com/demos/sensor-data-to-iphone-through-the-headphone-jack-using-arduino/) on connecting Arduino to an iPhone.

A small capacitor on the speaker out of the radio removes any DC bias. (I'm not sure why this was necessary, but in my testing it made receipt of packets much more reliable.)

On my UV5R+, volume is maxed, vox is set to 2 and, squelch is set to 1. On my iPhone volume is also maxed.

Schematic
---------
![Schematic](http://johnboiles.s3.amazonaws.com/Screenshots/BaofengUV5R-TRRS-r2-Schematic.png)

Bill of Materials
-----------------
1x [Kenwood Type Speaker Mic Cable](https://www.argentdata.com/catalog/product_info.php?products_id=70) (Alternately, you can use a 3.5mm and a 2.5mm cable)

1x [3.5mm TRRS Cable](http://amzn.com/B00FJEGXLW)

1x 10k Resistor 0603

2x 2.2k Resistor 0603

2x .01uF Capacitor 0603

1x 3" of 1/4" diameter heat shrink tubing (optional)

How to Order
------------
You can order the board directly through [OSHPark](http://oshpark.com/shared_projects/qy523INb) ($1.70 for 3 boards with free shipping). Digikey or Mouser are good places to buy the resitors and capacitors.
