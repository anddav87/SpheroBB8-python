# SpheroBB8-python

[Youtube Video](https://youtu.be/1Rkq6M9SdCc)


Detailed Instructions: http://dustinevans.net/bb8

Required Packages:
python-pip
libglib2.0-dev
bluepy (sudo pip install bluepy)
bluetooth
blueman

**
Now even better with a python API library!

Use the app to find the MAC Address of the BB8
input it at "`deviceAddress =`" (line 244) in the Sphero class in BB8_driver.py

**

***Included Scripts:***

**
**BB8Test.py**
A simple program that connects to BB8 and flashes the internal RGB LED red to green to blue. You can take it a step further and add `bb8.roll` commands to make him move using the API. 

**BB8joyDrive.py**
*requires PyGame library* 

Allow you to drive BB8 with a joystick/gamepad.
Shows on screen feedback of analog stick as well as speed and heading
Currently setup for a Xbox 360 controller.

 - Left analog stick controls BB8's movement, much the like app!   
 - Holding the Left trigger stops BB8.
 - Tapping the Left bumper changes BB8's heading - used to calibration.   
 -  Holding the Right bumper turns on BB8's blue 'tail light' to aid in calibration.


**TODO:**
 - getting sensor info, command responses, etc. back from BB8
 - 
 
**BASH:**
sudo ipython

**IPYTHON:**
%load_ext autoreload
%autoreload 2
import BB8_simple
c = BB8_simple.bb8COntroller()
c.turnleft()

