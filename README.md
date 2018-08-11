If your double click the RES button ,  
The dongle can't go into the update bootloader mode.   
Use this way to bulid.


## Build 
Go through [trinket m0: arduino-ide-setup](https://learn.adafruit.com/adafruit-trinket-m0-circuitpython-arduino/arduino-ide-setup) and [trinket m0: arduino-ide-setup2](https://learn.adafruit.com/adafruit-trinket-m0-circuitpython-arduino/using-with-arduino-ide)

Summary:
* Download and install arduino IDE http://www.arduino.cc/en/Main/Software
* In Arduino: go to "Prefences" and add to "Additional Board Manager URLs" followin URL:
*  `https://adafruit.github.io/arduino-board-index/package_adafruit_index.json`
* go to "Tools > Board > Board Manager" and select Type: All and
* Install "Arduino SAMD Boards" by Arduino 
* Install "Adafruit SAMD Boards" by Adafruit 
* Select the Trinket M0 with "Tools > Board > Adafruit Trinket M0"

Go to Sketch > Include Library > Manage Libraries
Install USBHOst by Arduino

Download this Repository, open main/main.ino with Arduino IDE.
Then Verify/Compile (Ctrl + R)
make sure there is not errors appear

warning! Connect the dongle to your computer and do not Click the Reset Button.
do not Click the Reset Button.
do not Click the Reset Button.
 
(On win7 install this [driver](https://github.com/adafruit/Adafruit_Windows_Drivers/releases/download/2.2.0/adafruit_drivers_2.2.0.0.exe))

Got to Tools > Port and select the trinket M0

Upload (Ctrl + U).

DONE!

## Hardware Fix 
 if plug the dongle into PC and nothing happened, try to remove this Resistance. 
 then plug the dongle in PC, double chick the RES button.
 maybe it will run.
 after fix it. shorted this Resistance is ok.
