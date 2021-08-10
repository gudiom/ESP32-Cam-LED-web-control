# ESP32-Cam-LED-web-control

Taken from the official Espressif ESP32 camera examples:
https://github.com/espressif/arduino-esp32/tree/master/libraries/ESP32/examples/Camera/CameraWebServer

I have copied and changed the status_handler.
When calling the pages:

http://ipcam/ledon

Or

http://ipcam/ledoff

Then the GPIO4 will set to HIGH or LOW and a simple JSON output with LED:true or LED:false is generated. 
It's not pretty but it works. 

Have fun with it. 


## Setup

Wiring and settings as usual:

I flash with 5V, don't forget to connect IO0 to GND during flashing and de-wire it during testing.

![fritzing of the wiring](https://github.com/gudiom/ESP32-Cam-LED-web-control/blob/main/images/esp32cam_wiring.png?raw=true)

### Arduino Settings

![screenshot of arduino settings](https://github.com/gudiom/ESP32-Cam-LED-web-control/blob/main/images/arduinospecs.png?raw=true![image](https://user-images.githubusercontent.com/61744949/128921341-a93f76ca-0dd9-4a54-9ddd-ef01decdf3cf.png)
)

