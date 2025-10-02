# esphome_velux_blind

The idea, and implementation is mostly taken from:
https://chiragdesai.uk/automating-velux-blinds-with-home-assistant/

https://community.home-assistant.io/t/hacking-velux-blinds-and-automating-them-with-esphome/665005

AtomEcho:
available pins are:
G21, G25 - on the right - first and second pin from the top
G26, G32 - at the bottom - third and fourth pin from the left
Please note: non of the above pins can drive 5 V; they are (as are all ESP32 GPIO pins) 3.3 V only.
3.3V output is the left top pin

To use the same pins for input and output the following discussion is helped me out:
https://community.home-assistant.io/t/open-drain-output-and-binary-sensor-at-the-same-pin/835056/6
