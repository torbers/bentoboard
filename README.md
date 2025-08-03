# bentoboard

as many ready-to-use electronics as i could fit on a 4"x4" PCB.

### essential hardware

the stuff you need to get making.
- controllers. interfaces. wireless.
- sensors. adcs. io expanders.
- motor drivers. blinky lights. speaker amps.

### common components

no weird proprietary connectors or manufacturing methods.
- I2C via stemma qt/qwiic/jst-sh plugs.
- 0.1" pin spacing – 100% breadboard compatible.
- 0.1" cutouts & [mousebites](https://github.com/madworm/Panelization.pretty)
- smallest component size: 0402 (1005 metric)
- optimized for pcbway design rules

### open source

<a href="https://github.com/torbers/bentoboard">bentoboard project</a> © 2025 by <a href="http://sambkothe.com">Sam Kothe (torbers)</a> is licensed under <a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a>

(this means that you can use my designs in your own projects, and you can create & sell your own bentoboards for others to enjoy! but you must include attribution to me in the final product or source code, and your work must use the same license.)

many schematics and layouts in this project were adapted from excellent open-source designs and tutorials by Adafruit and others. Please support their businesses! <br>
- [Adafruit](https://www.adafruit.com/)

---

## bb00 survey session

these are the things people need most often in my electronics lab, and the things i reach for when i need to solve a problem. it's the stuff that will take you the farthest with the least kerfuffle. a practical survey of what's possible.

### 2 controllers
 - bc00 RP2040 feather
 - bc01 ESP32-S3 feather

### 10 devices
 - bd00 CAP1188 capacitive touch pad ruler
 - bd01 MCP23008 16x digital IO expander
 - bd02 AW9523 16x constant-current LED driver
 - bd03 soil moisture sensor
 - bd04 LIS3DH accelerometer motion sensor
 - bd05 APDS9960 light/color/motion/gesture sensor
 - bd06 MCP3008 SPI analog-to-digital converter
 - bd07 I2C 4x dc/2x stepper motor driver
 - bd08 MAX98357 I2S mono audio dac & amp
 - bd09 8x WS2812 neopixel stick

### 1 power supply
 - be00 lipo charger & 5V 3A boost converter
