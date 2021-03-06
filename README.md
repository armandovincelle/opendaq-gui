opendaq-gui
===========

Some demo GUI interfaces for openDAQ, implemented in Python.

These demos require Python 2.7.6

**OpenDAQ** is an open source data acquisition instrument, which provides user
several physical interaction capabilities such as analog inputs and outputs,
digital inputs and outputs, timers and counters.

Through a USB connection, openDAQ brings all the information that it captures
to a host computer, where you can decide how to process, display and store it.
Several demos and examples are provided in website's support page.
(http://www.open-daq.com/paginas/support)

Please, go to http://www.open-daq.com for additional info.
For support, e-mail to support@open-daq.com

DAQControl.py
-------------
[DAQControl](http://www.open-daq.com/paginas/daqcontrol) is a test software application intended for demonstrating the command-response operation of openDAQ.

EasyDAQ.py
-------------
[EasyDAQ](http://www.open-daq.com/paginas/easydaq) is a test software application intended for demonstrating the Stream Mode operation of openDAQ.

calibration.py
--------------
[calibration.py](http://www.open-daq.com/posts/understanding-calibration-py-demo-i) is a demo intended to illustrate the process of device calibrating and checking.

Installation
============

Just download the files and run: 

`$ python setup.py install`

In any case, if for any reason the setup fails, EasyDAQ and DAQControl demos will require the following packages:

- opendaq (can be found in our root repository)

- setuptools

- wxPython

- numpy

- matplotlib 

- dateutil

- pyparsing

In Windows, you will need to include the route "C:\Python27\Scripts" into the system "Path" variable, if it does not already exist (System->Advanced Settings).

