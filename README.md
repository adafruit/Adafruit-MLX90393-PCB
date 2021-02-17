## Adafruit Wide-Range Triple-axis Magnetometer - MLX90393 PCB

<a href="http://www.adafruit.com/products/4022"><img src="assets/4022-QT.jpg?raw=true" width="500px"><br/>
<a href="http://www.adafruit.com/products/4022"><img src="assets/4022.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Wide-Range Triple-axis Magnetometer - MLX90393. Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4022

### Description

Measure the invisible magnetic fields that surround us, with this wide-range magnetometer. The MLX90393 is a wide range magnetic field sensor, that can measure 16-bits in ranges from ±5mT up to ±50mT in all 3 axes.

Compared to most magnetometers, this gives a huge range, which makes it excellent for detecting magnets and magnetic orientation, rather than the Earth's magnetic field. (Magnets have a much stronger field that overwhelms most magnetometers that would normally be used for orientation with respect to the North Pole)

To make it easy to use, we've placed this tiny little sensor onto a breakout board, with a 3.3V power supply and level shifter. This makes it easy to use with any 3 or 5V microcontroller. Our Arduino and CircuitPython code will get you started in a jiffy, with I2C communication to the sensor. You will be readin' out those Gauss's in minutes! With the address select pins you can have up to 4 sensors on one I2C bus.

Comes as a fully assembled and tested breakout board with a small piece of header for use with a breadboard. As if that weren't enough, we've now also added SparkFun qwiic compatible STEMMA QT connectors for the I2C bus so you don't even need to solder the I2C and power lines. Just wire up to your favorite micro using a STEMMA QT adapter cable. The Stemma QT connectors also mean the MLX90393 can be used with our various associated accessories. QT Cable is not included, but we have a variety in the shop.

**Specifications**
The MLX90393 has the following key technical specifications:

 * 16-bit output on all three (XYZ) magnetic field sensors
 * An unusually large dynamic range of **5-50** mT (1 mT or millitesla = 10 G or Gauss).
 * By comparison, the LSM303DLHC saturates at +/-8.1 G (0.81 mT) at maximum range setting.
 * Up to ~500 Hz sample rate (Based on OSR=0, DIG_FILT=2, HALLCONF=0xC for **1.84ms** conversion time. See 15.1.5 HALLCONF [3:0] in the datasheet for details.)
 * User-adjustable I2C address to allow multiple sensors in your project (two I2C ADDR pins for four possible I2C addresses).

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
