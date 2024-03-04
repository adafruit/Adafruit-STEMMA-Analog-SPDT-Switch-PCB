## Adafruit STEMMA Analog SPDT Switch - MAX4544 12V - JST PH 2mm PCB

<a href="http://www.adafruit.com/products/5892"><img src="assets/5892-01.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit STEMMA Analog SPDT Switch - MAX4544 12V - JST PH 2mm. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5892

### Description

Analog switches are a solid state alternative to relays, when you want a smaller, lower-power technology that won't wear out mechanically. As the name implies, you can use an analog switch chip to select between two analog signals, much like a mechanical switch. These chips tend to be tiny surface mount parts, so the Adafruit STEMMA Analog SPDT Switch lets anyone use the MAX4544 SPDT analog switch for signals up to 12V, without fiddly soldering.

When the selection signal is low, the Common pin is connected to the Normally Closed (NC) pin and disconnected from the Normally Open (NO) pin. When the selection signal is high, the Common pin is connected to NO and disconnected from NC. 

Unlike a relay or mechanical switch, analog switches don't wear out, and the switch time is near instant, about 30nS. The MAX4544 chip also guarantees break-before-make so the NC and NO pins will never accidentally cross-connect. 

However, there's a few things to watch out for:

* The V+ power pin (also the red wire if using a STEMMA cable) must as high as the highest analog voltages you want to switch. That means if the analog signals are no more than 6VDC, the V+ pin must be higher than 6V. You cannot power this pin with 3.3V and switch 12V signals.
* The MAX4544 cannot switch signals below ground. No negative voltages can be applied to the COM/NO/NC pins!
* Analog switches are for signals, not power! Since this is not a mechanical switch, the signals pass through circuitry that is not designed to source or sink current. This is great for analog signal voltages, and is not good for providing more than a few mA of current.

This board has a simple plug-and-play JST PH (2mm pitch) input connector for solderless use. Provide V+ power (from 3V up to 12V) and signal of at least 2.5VDC logic level. On the output is a terminal block with the common, Normally Open and Normally Closed signals. You can also get to all the signal and power pins on a 0.1" breakout header if desired.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
