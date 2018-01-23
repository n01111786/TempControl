# TempControl

# Build Instructions:

The project I decided to work on this semester was the DHT sensor module.  It is a simple device which has to capability to measure the Temperature/Humidity of a given area.

# Materials/Components Needed:
*Raspberry pi 3 - $99.99
*DHT Sensor (11 22 or AM2302) - $14.99
*Connection wires/Breadboard - Parts kit
*4k Ohm Resistor - 200 for $10.99

# Assembly:

1. You will need to make a connection to ground from the sensor to either the pi or a breadborad.
2. Connect the signal pin and vcc to a 4k Ohm resistor
3. Once again connect the signal and vcc directly to the corresponding pins on the pi.

# Power up

If booting for the first time after purchasing the Raspberry pi 3 starter kit from amazon, insert the SD card to the SD reader on the pi.
I would recomend installing Raspbian as it is already on the SD and provides friendly user interface, The python code is avalible in my blog, you simply download the package from adafruit, save it as sudo yourfilename.py and compile in the terminal using the command " python yourfilename.py. it will compile if there are no errors.

# Product testing

If compiles succesful,you simply run this command in the terminal window: sudo /home/pi/Adafruit_Python_DHT/examples/AdafruitDHT.py 2302 4. The directory might be differant depending on where you save your files, also the 2302 can be changed to 11 or 22 depending on your sensor as well as the 4 in the code, that is the signal pin i used however there are multiple on the pi avalible.

# Reproducable

In my opinion, All of the necessary documents/code required to build this sensor are avalible in my repository. If you follow my instructions and watch my video you will have no problem with this project. 

