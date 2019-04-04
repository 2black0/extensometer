# Extensometer
From wikipedia, its said An extensometer is a device that is used to measure changes in the length of an object. An extensometer is useful for stress-strain measurements and tensile tests. The purpose of this project is to build a extensometer and rainfall detector based on arduino uno with cheap sensor rotary encoder. All data sensor will be sent to a computer server and shown in apps.

## Peripheral
* Arduino Uno R3 [Pics](https://ik.imagekit.io/bfrs/tr:w-500,h-500,pr-true,cm-pad_resize,bg-FFFFFF/image_himeshreddivari/data/Arduino-Uno-2-500x500.jpg)
* Arduino LCD Keypad Shield for Uno R3 [Pics](https://5.imimg.com/data5/AL/CS/MY-19287108/sunrobotics-lcd-keypad-shield-for-arduino-500x500.jpg)

* Arduino Ethernet / LAN Shield for Uno R3 [Pics](https://s2.bukalapak.com/img/2818642371/w-1000/Arduino_Ethernet_LAN_Shield_W5100_for_Uno_Mega_2560.jpg)

* MPC23017 [Pics](https://raw.githubusercontent.com/maxgerhardt/rotary-encoder-over-mcp23017/8e88ec78b11ca20ef21b4b6da7cf25a6e9028db8/images/circuit_eight_encoders.png)

* Rain Gauge [Pics](https://ecs7.tokopedia.net/img/cache/700/product-1/2017/7/22/0/0_5243e113-96ac-4ef4-b6b8-629c9480294f_1024_576.jpg)

* RTC DS3231 [Pics](http://linhkienmachdien.com/wp-content/uploads/2017/02/ds3231-at24c32-i2c-real-time-clock-module.jpg)

* Lora SX1278 [Pics](https://robokits.co.in/bmz_cache/9/9c1184044e9a40c1b6235ab93a6d10ca.image.1066x800.jpg)

## Feature
* LCD 16x2 to show the menu :
  - Read all sensor (rotary encoder & rainfall sensor)
  - Reset all variable to zero
  - Calibration mode (for rotary encoder)
  - Edit date and time of RTC
  - Time of Polling sensor read (1minutes, 2minutes, or other)
  - Buzzer & Lamp Test
* Data sent to a Server via LAN Wired
* Buzzer & Lamp can operated via Apps on the server
* Not only measure change in the length but also its angle
* Solar cell system apply in this project
* Next : can send notification to smartphone apps (telegrambot)

![Extensometer System](https://raw.githubusercontent.com/2black0/extensometer/master/Picture/extensometer.jpg)

## How to Build
* next update
