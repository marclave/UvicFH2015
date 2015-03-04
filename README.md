UvicFH2015
========
UVic Formula Hybrid Repository for 2015

###Requirements
1. Python is installed (Version 3.3.4 but any above is fine)
2. [Arduino UNO](http://www.seeedstudio.com/wiki/Arduino_UNO) with a [CAN-BUS Shield](http://www.seeedstudio.com/wiki/CAN-BUS_Shield)
3. You need to install GPIO Interrupts on the raspberry pi

For Python 3:
```
sudo apt-get -y install python3-rpi.gpio
```
###Tkinter Notes
1. Tips on [Performance](http://effbot.org/zone/tkinter-performance.htm)

###Python Notes
1. If needed c functionality, here is a library [ctypes](https://docs.python.org/2/library/ctypes.html)
2. GPIO interrupts [GPIOinterrupts](http://raspi.tv/2013/how-to-use-interrupts-with-python-on-the-raspberry-pi-and-rpi-gpio)
3. POLLING ~~Or we should be using [listeners](http://python-can.readthedocs.org/en/latest/listeners.html)~~
4. Python guideline for [raise](http://stackoverflow.com/questions/2052390/manually-raising-throwing-an-exception-in-python)
