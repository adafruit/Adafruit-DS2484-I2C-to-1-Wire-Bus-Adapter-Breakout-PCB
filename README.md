## Adafruit DS2484 I2C to 1-Wire Bus Adapter Breakout - STEMMA QT / Qwiic JST SH 1mm PCB

<a href="http://www.adafruit.com/products/5976"><img src="assets/5976.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit DS2484 I2C to 1-Wire Bus Adapter Breakout - STEMMA QT / Qwiic JST SH 1mm. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5976

### Description

By customer request, this is a DS2484 Stemma QT board that uses a I2C-to-1W controller chip, with ESD protection and support for split supplies. You can easily connect it to an existing I2C bus and then use the screw terminals to attach multiple DS18B20's, or pair it with our 1-Wire chaining breakouts for fancier experimentation.

You're probably familiar with the 'top three' electronics protocols: I2C, SPI and UART. Perhaps you're aware of a fourth one, called "1-Wire" which was invented by Dallas Semiconductor (which became Maxim, which became Analog Devices). As you may expect, this protocol uses a single data wire plus a ground wire (and an optional power wire) to connect to any number of sensors or memory chips that all share the same bus.

In theory, there's a lot of different 1-Wire devices out there, but in reality almost everyone uses 1-Wire for DS18b20 temperature sensors. the long wire lengths and ease of 'chaining' by sharing a single bus wire makes it perfectly fine for this purpose. You can bit-bang 1-Wire on most microcontrollers, and some SBCs like Raspberry Pi have kernel module support. But are lots of chips or firmware stacks without 1-Wire capability, or maybe you want to use 1-Wire devices on your desktop computer or other SBC with I2C.

To get you going fast, we spun up a custom-made PCB in the STEMMA QT form factor, making it easy to interface with. The STEMMA QT connectors on either side are compatible with the SparkFun Qwiic I2C connectors. This allows you to make solderless connections between your development board and the DS2484 or to chain it with a wide range of other sensors and accessories using a compatible cable.

You can power the board directly from the STEMMA QT cable, whether it is 3V or 5V. If you want a different voltage on the 1-Wire power pin, cut the onboard trace and you can inject the voltage at the terminal block.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
