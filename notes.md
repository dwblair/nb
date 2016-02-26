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


https://hdfgroup.org/wp/2015/04/hdf5-for-the-web-hdf-server/
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

- solar water disinfection
http://www.cdc.gov/safewater/solardisinfection.html

- linux on toshiba chromebook
http://www.fascinatingcaptain.com/howto/install-ubuntu-on-the-toshiba-chromebook-2-in-5-steps/

- diy fiber optics
https://hackaday.io/project/1379-diy-fiber-optic-sensors
https://www.raspberrypi.org/forums/viewtopic.php?f=37&t=68660

- low cost fiber optic pH sensor
https://www.osapublishing.org/view_article.cfm?gotourl=https%3A%2F%2Fwww%2Eosapublishing%2Eorg%2FDirectPDFAccess%2F34675243-B4DA-50AC-C8A3F4A4A425B215_190647%2Foe-17-25-22296%2Epdf%3Fda%3D1%26id%3D190647%26seq%3D0%26mobile%3Dno&org=

- using phenol red absorption
http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3771845/

- nice old thesis
https://core.ac.uk/download/files/370/11539810.pdf

- principle of ph sensor
http://csrg.ch.pw.edu.pl/tutorials/fiber/

- ysi comparison of optimetric vs potentiometric
https://www.ysi.com/ysi-blog/water-blogged-blog/2014/10/ph-measurement-methods-advantages-and-disadvantages

- great paper on pros and cons of optical sensing -- great great overview
http://cdn.intechopen.com/pdfs-wm/26343.pdf

- impedance spectroscopy and water quality
http://www.j-sens-sens-syst.net/3/133/2014/jsss-3-133-2014.pdf

- electronic tongue
http://chemse.oxfordjournals.org/content/30/suppl_1/i258.full

- using a dye and microfluidics and spectrophotometry:
http://www.fondriest.com/news/ocean-acidification-prompts-low-cost-long-term-ph-sensor.htm

- ph and microfluidics:
http://noc.ac.uk/news/new-generation-micro-sensors-monitoring-ocean-acidification

- spectrophotometer -- pure engineering
http://www.pureengineering.com/store
https://hackaday.io/project/4141-c12666ma-micro-spectrometer
http://www.hamamatsu.com/us/en/C12666MA.html

- group buy for micro spectrophotometer
https://groupgets.com/manufacturers/hamamatsu-photonics/products/c12666ma-micro-spectrometer

https://hackaday.io/project/1395-open-source-science-tricorder
- arducorder mini that has footprint for C12666MA
- specifically, https://github.com/tricorderproject/arducordermini/blob/master/hardware/sensorboard_spectrometer_rev0.pdf
 near-ir fft: http://www.laserfocusworld.com/articles/2015/02/si-ware-mems-sensors-chosen-for-spectrometer-based-soil-analysis.html

- single board nmr based on usb radio
http://d1.ourdev.cn/bbs_upload782111/files_42/ourdev_657333WMUP1R.pdf
https://www.thevespiary.org/rhodium/Rhodium/Vespiary/talk/files/2726-A-Radio-Frequency-Source-Using-Direct-Digital-Synthesis-and-Field-Programmable-Gate-Array-for-Nuclear-Magnetic-Resonance.807f.pdf
http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3892883/pdf/sensors-13-16245.pdf

# 2016-2-22

four-probe conductivity circuit
https://github.com/p-v-o-s/conductivity-research/blob/master/four_probe.ipynb

two-probe conductivity circuit
https://github.com/p-v-o-s/conductivity-research/blob/master/two_probe.ipynb

in-browser 'live' plotting via jupyter (running locally):
https://github.com/p-v-o-s/conductivity-research/blob/master/plotter.ipynb

in-browser 'live' plotting via chrome plugin:
https://github.com/p-v-o-s/chrome-serial-tests

avr code:
https://github.com/OpenWaterProject/avr-upload

Real Time Clock (RTC) and lower power code streamlined: 
https://gist.github.com/dwblair/cee071d7b5af1c8f0cda

Nice convos with Craig Versek and others re: dielectric spectroscopy 

-- publiclab receipts  https://publiclab.org/receipts 

This week:

- Write up conductivity and firmware progress as research notes (find nice way to import Jupyter notebook as markdown) 
- Coqui class at Emerson with Catherine -- more documentation
- Four probe conductivity prototyping 
 
spectrometer device pcb https://github.com/tricorderproject/arducordermini/blob/master/hardware/sensorboard_spectrometer_rev0.pdf


spectrometer device pcb https://github.com/tricorderproject/arducordermini/blob/master/hardware/sensorboard_spectrometer_rev0.pdf

----

- Trigger BBB Webcam, USB
- Power on BBB -- remote switch with features 
- through-hole stuff 


- undecover raptor eye
http://www.pixcontroller.com/UndercoverEye/UndercoverEye-Cellular.htm

game camera review:
http://game-camera-review.toptenreviews.com/

naturebytes camera:
https://www.raspberrypi.org/blog/naturebytes-camera-traps/

- pi in the sky lora gateway
https://github.com/piinthesky

lora radio on hackaday:
http://hackaday.com/2014/11/16/the-future-of-the-internet-of-things/

fiber optic cable source for adafruit
http://www.wiedamark.com/fiberopticlighting.aspx

voltage to frequency converter
http://www.mouser.com/ds/2/609/AD7740-278983.pdf
http://www.mouser.com/ProductDetail/Analog-Devices/AD7740KRMZ-REEL7/?qs=sGAEpiMZZMuYYilu8wI%252bZxvtRgn7Gyq8jqE9xoTIaLI%3d

designs for high performance voltage to frequency converters
http://cds.linear.com/docs/en/application-note/an14f.pdf
-- see figure 14 !!! sine wave output 

sine wave generation techniques
http://www.ti.com/lit/an/snoa665c/snoa665c.pdf

sine approximation: allows for easy tuning -- see section 10 / figure 14

--- figure 15 -- voltage tunable sine wave oscillator!!!
http://www.ti.com/lit/an/snoa665c/snoa665c.pdf
-- can use this op-amp: http://www.digikey.com/product-detail/en/AD711JNZ/AD711JNZ-ND/671001

arduino sine wave generation: 
-- http://interface.khm.de/index.php/lab/interfaces-advanced/arduino-dds-sinewave-generator/

the synth library!
https://github.com/dzlonline/the_synth

function generator with attiny
http://hackaday.com/2012/02/08/attiny25-based-function-generator-causes-a-wave/

http://blog.allgaiershops.com/2012/02/08/attiny25-based-function-generator/

http://www.technoblogy.com/show?QVN

sine wave on the digispark!
http://duino4projects.com/digispark-rgb-led-fader/

attiny85 sine wave 
http://cho-yaba.punyu.jp/?p=1663

variable sine wave code
http://interface.khm.de/index.php/lab/interfaces-advanced/arduino-dds-sinewave-generator/

thread on using digispark as sine wave generator
http://forum.arduino.cc/index.php?topic=263703.0

code for the attiny85:
http://www.mikrocontroller.net/attachment/163429/Tiny_50Hz.c

more code for attiny:
http://www.alexallmont.com/blog/?p=178
http://shin-ajaran.blogspot.com/2014/04/wearable-electronics-arduino-x-attiny85.html
http://www.electronics-lab.com/project/tiny-dds-open-source-dds-generator/

DDS -- write to chip w/ arduino -- for cool breakout board -- 
http://www.analog.com/media/en/technical-documentation/data-sheets/AD9837.PDF

really simple sine wave w/ an op-amp:
http://www.ti.com/lit/wp/snoa839/snoa839.pdf

voltage controlled oscillator --> smart phone circuit
http://www.instructables.com/id/How-to-Make-a-Voltage-Controlled-Oscillator/?ALLSTEPS

very simple voltage controlled oscillator IC
http://www.mouser.com/ds/2/405/sn74ls624-405812.pdf

555 alarm based on voltage -- use with conductivity circuit?
http://www.electroschematics.com/6255/temperature-alarm-2/

over-temperature alarm:
http://electronicdesign.com/analog/over-temperature-alarm-circuit-uses-common-inexpensive-components

# 2016-2-23

The corporate timescale for clean energy:
http://www.nytimes.com/2016/02/23/opinion/bill-gatess-clean-energy-moon-shot.html

PIT physics of information theory notes:  
http://fab.cba.mit.edu/classes/862.16/

notes on binomial distribution:
https://www3.nd.edu/~rwilliam/stats1/x13.pdf

nice proofs:
http://www.math.uah.edu/stat/bernoulli/Binomial.html

further proof material:
https://proofwiki.org/wiki/Expectation_of_Binomial_Distribution

common conductivity measurement mistakes: 
https://www.thermofisher.co.nz/Uploads/file/Environmental-Industrial/Environmental-Monitoring-Safety/Water-Monitoring-Treatment/Tech-Tip-Top-Ten-Conductivity-Mistakes-NZ.pdf

theory of four probe conductivity measurements:
http://www.landviser.net/webfm_send/10

# 2016-2-24

Fantastic blog re: hacks with avrs:
http://scanlime.org/2008/09/using-an-avr-as-an-rfid-tag/

TODO: check out lifepo battery tech

rationale for using 1200 baud standard for FSK: https://www.reddit.com/r/electronics/comments/2acu2b/decoding_fsk_signal/

rationale for audio: http://labs.rakettitiede.com/12kbps-simple-audio-data-transfer-for-avr/

basic scheme to implement FSK -- great explanation / hack: http://labs.rakettitiede.com/12kbps-simple-audio-data-transfer-for-avr/

fab lab fsk: http://fab.cba.mit.edu/classes/863.12/people/Adam.Marblestone/AHM_week11.html

arduino manchester encoding: https://mchr3k.github.io/arduino-libs-manchester/

review of implementations in javascript: https://github.com/cobookman/HTML5.MicIO/issues/2

brilliant -- finland hacker, pea whistle: http://www.windytan.com/2015/10/pea-whistle-steganography.html

sound of a dialup, pictured: http://www.windytan.com/2012/11/the-sound-of-dialup-pictured.html

pitch detect in web audio: https://github.com/cwilso/PitchDetect **** 

using morse code over audio: http://www.whatisthis.top/questions/150301/data-to-audio-and-back-modulation-demodulation-with-source-code ****

ORDERING:  
- need materials for jon's project
- need materials for turbidity

turbidity -- ~ 850 nm leds on mouser
http://www.mouser.com/Optoelectronics/Infrared-Data-Communications/Infrared-Emitters/_/N-6qrgl?P=1z0wtyrZ1z0wtyt

better boost chip? http://jeelabs.org/wp-content/uploads/2012/06/04/boost-revisited/index.html

TODO -- find the lifepo info / breakout board


hdf5 access online:
https://hdfgroup.org/wp/2015/04/hdf5-for-the-web-hdf-server/

lecture online: https://www.youtube.com/watch?v=FOMI0ORGH44&ebc=ANyPxKr5uUXe42rnrDdyfotqYY4RhDqvjOBYiSugtaY-u2iYp177tn--9pSTAsqeMq3rcGrToCtHLVEHR3JgfJ1qxBomhgS7mw

replacing relatve paths
http://stackoverflow.com/questions/4694993/replace-url-relative-path-with-full-domain-in-css-files

pycharm and jupyter:
http://blog.jetbrains.com/pycharm/2015/07/quantitative-research-in-python-using-notebooks/

https://cloud.sagemath.com

pycharm
http://nicoddemus.github.io/articles/pycharm/

avr and dtmf:
http://www.atmel.com/images/doc1982.pdf
http://boris0.blogspot.com/2013/09/rotary-dial-for-digital-age.html

SOLVED: https://github.com/johnmccombs/arduino-libraries/blob/master/Tone/examples/DTMFTest/DTMFTest.pde

goertzel algorithm: https://github.com/Ravenstine/goertzeljs

# 2016-2-25
￼
## turbidity 

cornell reference re: turbidity
http://people.ece.cornell.edu/land/courses/ece4760/FinalProjects/s2005/jsa25_jyh25/TurbidityMeter.htm

wash4all: http://wash4all.org/wp/blog/

nice part: https://www.sparkfun.com/datasheets/Sensors/TSL230R-LF-e3.pdf

another nice part: https://www.adafruit.com/datasheets/TSL256x.pdf

http://www.chi.camp/projects/dory/

https://learn.adafruit.com/ir-sensor

meausring turbidity:
http://www.fondriest.com/environmental-measurements/equipment/measuring-water-quality/turbidity-sensors-meters-and-methods/

http://ir.hfcas.ac.cn/bitstream/334002/11934/1/Research%20on%20PWM%20applied%20in%20water%20turbidity%20measurement.pdf

http://www.analog.com/media/en/technical-documentation/technical-articles/Optimizing-Precision-Photodiode-Sensor-Circuit-Design-MS-2624.pdf

interesting: phototransistors that emit and detect: http://sensing.honeywell.com/honeywell-sensing-infrared-sensors-line-guide-006494-6-en.pdf

how to build a lock-in amplifier:
http://www.analog.com/library/analogdialogue/archives/48-11/lock_in_amplifier.html <--- key reference!! 

lock-in amplifier: http://www.phys.utk.edu/labs/modphys/lock-in%20amplifier%20experiment.pdf

http://www.instructables.com/id/Lock-in-Amplifier/

http://electronics.physics.helsinki.fi/wp-content/uploads/2011/02/lockin_rob_web.pdf  <--- great explanation

so, one idea: pulse LED with a sine wave of 1 kHz, and use band pass around 1 kHz on the detector ...

input can be true sine wave, or square wave + filters 

same principle used here: http://www.comm-tec.com/library/Technical_Papers/SinglePointDoppler/Turbidity%20Sensor%20Design%20and%20performance.pdf

nice conceptual diagram: http://www.mdpi.com/1424-8220/14/3/3871/htm

removing dc offset:
https://openenergymonitor.org/emon/buildingblocks/digital-filters-for-offset-removal

circuit for removing dc offset: http://forum.allaboutcircuits.com/threads/removing-dc-offset-from-a-signal.65288/

good explanation of lock-in amplifier: https://www.uni-ulm.de/fkp/lehre/Physics%20Lab%20Anleitungen/Lockin%20Amplifier.pdf

try some version of filtering / lock-in amplifier to remove DC offset in signal 

## microphone / noise

For those thinking about using smartphone apps, we (NIOSH) did a study on noise apps and not all apps are equal in terms of accuracy and reliability.  See http://blogs.cdc.gov/niosh-science-blog/2014/04/09/sound-apps/.  We published the study in the Journal of Acoustical Society of America http://scitation.aip.org/content/asa/journal/jasa/135/4/10.1121/1.4865269.

calibrated external mic: http://www.parts-express.com/dayton-audio-imm-6-calibrated-measurement-microphone-for-tablets-iphone-ipad-and-android--390-810

nice calibrated microphone for iphone: http://www.amazon.com/MicW-Calibrated-Measurement-External-Microphone/dp/B00510Y3KC

great blog post + comments on the microphone project: http://blogs.cdc.gov/niosh-science-blog/2014/04/09/sound-apps/

