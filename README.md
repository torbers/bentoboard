# bentoboard

as many ready-to-use electronics as i could fit on a 4"x4" PCB.

### essential hardware

the stuff you need to get making.
- controllers. interfaces. wireless.
- sensors. adcs. io expanders.
- motor drivers. blinky lights. speaker amps.

### common interconnects

no weird proprietary connectors.
- I2C via stemma qt/qwiic/jst-sh plugs.
- 0.1" pin spacing – 100% breadboard compatible.

### open source

licensed under CC-BY-SA.
many schematics and layouts in this project were adapted from excellent open-source designs and tutorials by Adafruit and others. Please support their businesses! <br>
[Adafruit](https://www.adafruit.com/)

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
