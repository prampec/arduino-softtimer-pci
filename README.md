## Description ##

This library adds extra functionality to SoftTimer Arduino library, that utilizes PinChangeInterrupt capability of the AVR microcontrollers.

Added functionalities:
- Debouncer - For bouncing input pins, with the option of detecting released pins and measuring time being the pin pressed
- Rotary - Rotary encoder event handling.

## Notes ##

Some time ago these functionalities were also a part of the SoftTimer library itself. But as time passes, a set of popular MCUs appeared with the lack of the PinChangeInterrupt. And from that point on, using the SoftTimer appeared to be very confusing. So eventually all functions based on PinChangeIntrrupt was moved out to this extension library.
