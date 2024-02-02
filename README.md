# neotrellis-grid-paletted-plus-for-M0/SAMD21-RP2040-and-Teensy

A modified version of the "paletted" DIY Neotrellis Grid controller originally from https://github.com/oldmanfury ... which is modified code originally from https://github.com/okyeron. 

Ive added the ability to define default color and brightness settings along with the option to skip the automatic launching of color selector at startup (disabled by default) so so its always immediately ready to go using the default color and brightness values as soon as it is plugged in.   Launch the color selector anytime by pressing (and releasing) the 3 left-most buttons (14,15,16) in the bottom row. 
There is also an option to display the color and brightness values to serial monitor when the selection is made (helpful for customizing the default values.) I also added a 4th page of color choices (subtle variations of white) along with a few additional variables that should make it easier to add even more color pages without having to change stuff elsewhere in the code.  Configure this in the "User Variables" section near the top after the libraries.

Versions for RP2040, M0/SAMD21, and Teensy.  (M0/SAMD21 version currently not yet tested!! Please let me know if it works!)

You will have to complie the sketch in Arduino for your specific board. Dont forget to select "TinyUSB" as the USB stack and have the required libraries and board definitions installed.

Original code and installation instructions here: https://github.com/okyeron/neotrellis-monome/tree/master/neotrellis_monome_teensy  and here:https://github.com/oldmanfury/neotrellis-grid-paletted


