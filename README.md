# Thermocouple

Fast and accurate temperature monitoring for robot motors.

## Usage

1. Download and install the Adafruit MAX31855 library for Arduino IDE. This can be done by either of the following methods:
    1. Method 1
        1. Open Arduino IDE
        2. From the toolbar, open Sketch -> Include Library -> Manage Libraries
        3. Search for "Adafruit MAX31855"
        4. Select the first result and press "Install"
    2. Method 2
        1. Download Adafruit_MAX31855_library-1.0.3.zip from this repository
        2. Unzip, then copy to Arduino libraries folder (usually `Documents\Arduino\libraries\` on Windows, or `~/Documents/Arduino/libraries/` on Linux) 
2. Upload `serailthermocouple.ino` to Arduino via Arduino IDE.
3. Open Serial Monitor to read data.
