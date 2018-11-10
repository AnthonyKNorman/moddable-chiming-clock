# moddable-chiming-clock
ESP32 connected to a cheap TFT as per the moddable-zero wiring here https://github.com/Moddable-OpenSource/moddable/blob/public/documentation/displays/wiring-guide-generic-2.4-spi-esp32.md

Go through the Getting started process at https://github.com/Moddable-OpenSource/moddable/blob/public/documentation/Moddable%20SDK%20-%20Getting%20Started.md

Run some of the moddable examples to make sure all is working

This example takes moddable's clock example and adds the Digital/pins library to drive a small piezo buzzer that 'chimes' on the hour and half hour.

The code also demontrates the use of a single-shot timer for the duration of the buzz.

