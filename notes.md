External power for canon powershot:

- http://arch.ced.berkeley.edu/kap/discuss/index.php?p=/discussion/4862/external-power-for-canon-powershot-cameras
- http://www.replacedirect.nl/product/p0142986/dc-koppelstuk.html

webcam and linux:

- http://derekmolloy.ie/beaglebone/beaglebone-video-capture-and-image-processing-on-embedded-linux-using-opencv/

3d printing a battery holder for a powershot:

- http://www.3ders.org/articles/20120513-3d-print-a-battery-adapter-for-canon-powershot-sx200.html
- original post: http://tinkerlog.com/2012/05/13/battery-adapter-for-canon-powershot-sx200/
- additional photo: http://diy3dprinting.blogspot.com/2014/04/diy-3d-printed-external-power-supply.html
- battery emulator: http://hackaday.com/2015/01/21/3d-printed-camera-battery-emulator/

gps datalogger:

- http://www.toptechboy.com/arduino/lesson-23-arduino-gps-with-data-logger/

aa battery adapter:

- http://www.thingiverse.com/thing:312059

LiFePO4 battery chemistry:

http://lifepo4wered.com/


- https://hackaday.com/2015/09/06/better-batteries-for-electronic-gadgets/
- https://github.com/xorbit/LiFePO4wered-USB-OSHW

Voltage regulation wastes power. If you use an LDO, you waste power when you draw current. If you use a switching power supply, you waste power when your device is sleeping. Low power electronics tend to operate under both conditions: they sleep most of the time, then briefly wake up and do something that consumes power. 

Some systems can get away with using a lithium coin cell. The voltage range of such a cell allows it to power 3V systems without regulator. The downside is that they have high internal resistance and are often incapable of providing the current necessary to power transmitters or actuators. Wouldn't it be great if there was a battery technology that had a 2-3.6V voltage range, low self-discharge, low internal resistance so it could deliver high current, was rechargeable and had a large number of recharge cycles? 

There is! It's called LiFePO4 (lithium iron phosphate). Now you can easily use it in your projects with LiFePO4wered/USB!
DETAILS
LiFePO4 is a battery technology that finds wide application in power tools and electric vehicles. It is an inherently stable chemistry (which makes it safe), is environmentally friendly (no heavy metals), has very high power density and many more recharge cycles than other Lithiums.

It also has a perfect voltage range for use with electronics: 2 - 3.6V. This means most modern chips can be powered without the use of a voltage regulator, which tends to be a big power waster in low power systems.

So here is an easy to use module to get started with LiFePO4 in your own designs. It's basically a battery with an integrated USB charger. All connections are on a 0.1" grid for easy integration. Take power straight off the battery holder terminals, or if that doesn't fit in your design, cut off the battery terminals and connect to the 0.1" header footprint.

So stop using old lithium cells that require a voltage regulator and last only a couple hundred cycles, and upgrade to the next level with LiFePO4!

https://github.com/xorbit/LiFePO4wered-USB-OSHW


LiFePO4 battery chemistry:

http://lifepo4wered.com/

LiFePO4 battery chemistry:

solar charger for lifepo4 batteries:

- http://www.mictronics.de/projects/lt8490-mppt-solar-charger/

- https://www.sparkfun.com/products/12885

- designing a solar cell battery charger: 
http://cds.linear.com/docs/en/lt-journal/LTMag-V19N4-04-LT3652-JimDrew.pdf

- sexagesimal binary clock
https://en.wikipedia.org/wiki/Binary_clock

- 6 position dip switch
http://www.mouser.com/ProductDetail/Grayhill/78B07ST/?qs=ls7QRyWmRk66SBR2nlg76g%3D%3D&gclid=CjwKEAiA3aW2BRCD_cOo5oCFuUMSJADiIMILJSKnd6qr90DzabnXjfnhiTPKYfSvobBwbj_5TinWcxoCx4rw_wcB

- 12 position dip switch
http://www.mouser.com/ProductDetail/Grayhill/76RSB12ST/?qs=sGAEpiMZZMv%2f%252b2JhlA6ysJGznUGmjyNwBvtEAniwyUA%3d
http://www.mouser.com/ProductDetail/CK-Components/SDA12H1BD/?qs=sGAEpiMZZMv%2f%252b2JhlA6ysEDRsbwL3hJkHYs1F%252b%2ffh9I%3d

- piece on medium on blockchain, to counter:
https://medium.com/@piscosour/from-bitcoin-skeptic-to-blockchain-enthusiast-5ad99e39d249#.u3qfenawj