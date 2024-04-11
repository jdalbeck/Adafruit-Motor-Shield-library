This fork of the Adafruit Motor Shield v1 library adds support for the Wemos D1 R32 (ESP32) board.

While the v1 of the Adafruit Motor Shield is somewhat antiquated and inefficient, it is still the cheapest motor shield available.  In combination with the Wemos D1 R32 board, it makes a great, economical platform for 3D printed robots that are designed around the Arduino Uno/Shield form factor (e.g. SMARS).

The added code for the Wemos D1 R32 currently uses the LEDC module, which is the easiest way to generate PWM signals on an ESP32.  I have not tested this with stepper motors.  It is possible that the MCPWM module would provide some benefits, or possibly using the ESP32_FastPWM library.  We have not encountered any issues with the LEDC method yet.

To install, click the "Code" dropdown button above, then click "Download ZIP".  Extract the folder "Adafruit-Motor-Shield-library" to your Arduino IDE "libraries" folder.  If you already have installed the Adafruit Motor Shield v1 library, you may need to remove it first via the Library Manager.
--------------

This is the August 12, 2009 Adafruit Motor shield firmware with basic Microstepping support. Works with all Arduinos and the Mega
Updated in September 2012 for use on PIC32 architecture (chipKIT/MPIDE)

For more information on the shield, please visit https://learn.adafruit.com/adafruit-motor-shield

To install, click DOWNLOAD SOURCE in the top right corner, and see our tutorial at http://www.ladyada.net/library/arduino/libraries.html on Arduino Library installation
