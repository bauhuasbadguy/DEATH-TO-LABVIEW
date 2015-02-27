# DEATH-TO-LABVIEW
I've got the daq card and GPIB running in python, here's how



Functions
---------

**sendvalue(channelno, value, *samplerate*)**:- Makes an output channel (channelno) on the DAQ card output a set value(value). You can also change the sample rate by feeding it a third value but this is optional

**result = readDAQ(channel, n)**:- Take n readings from DAQ input channel, 'channel', (put a number in here). The readings are returned in a 1D numpy array





Future plans
------------

1)Examples: I intend to upload a python file with all these functions being used as well as example uses of the pyvisa libary but I'm a little busy today so it'll have to wait till Monday.

2)Output function:- I also intend to create a way of sending functions to the DAQ card, this might just be an odd way of using the existing function but I need to experement a little to get responce times

