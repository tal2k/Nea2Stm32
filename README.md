# Nea2Stm32
Driving a neato robot with stm32f4 

Neato vacuum cleaner driver for Stm32f4

Steps:

1. Control Neato 2 wheels and encoders using stm32f4 and toshiba motor controller

2. Add The xv11 lidar to the picture, use another toshiba controller to drive the lidar motor using pwm and pid to close  the loop,  and a uart port on the stm32 for getting the samples data.

3. Add Odroidxu4 - it will run as the ros master and all algorithms will run on it. the odrioid will connect to the stm32f4 using usb for both powering it and controlling the bot.


