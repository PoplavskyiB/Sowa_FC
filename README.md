# SOWA_FC
The main goal of this project is to create an open-source STM32 based flight controller SOWA F4

29.09.2024 --> ! Important update !
I have figured out that OSD doesn`t work correctly. 
Due to the lack of time nowadays, I will try to solve the problem as soon as I have a chance.
If somebody has of possibility of helping me to find a problem - I will be really gratefull.
In that case please contact me.
Thanks.

![Preview](https://github.com/PoplavskyiB/Sowa_FC/assets/167243322/16d51ae7-4e67-41d7-b5ab-8c3189c128e5)

Features:
- STM32F405 microcontroller
- ICM42688P gyroscope + accelerometer
- Blackbox (16Mb)
- OSD
- 3-8S voltage
- Powerful 3.5A DC converters allow you the usage of almost every high-consumption peripherals
- 3.3V (500mA) / 5V (3.5A) / 10V (3.5A) rails
- SCL and SDA pins for GPS
- 6 UARTs
- 8 motor/servo outputs
- RX4 inverter (for SBUS)
- Voltage & current sensor
- SWD and SWC pins for direkt programming via bootloader (ex. ST-Link)

Size: 40/40/1,6 mm

Drill diameter: 4 mm

Drill distance: 30,5 mm (center to center)
<img src="https://github.com/PoplavskyiB/SOWA_FC/assets/167243322/512cce53-6060-4659-90b6-d78159e6c609" width="800">

# Wiring diagram:
![Wiring](https://github.com/PoplavskyiB/SOWA_FC/assets/167243322/513a9a46-8e1d-4fa3-bf47-a577ab3b860f)
![Wiring_Bottom](https://github.com/PoplavskyiB/SOWA_FC/assets/167243322/1db0d280-d29a-41b1-86e8-74cb57edebc9)

# Software flashing

At this moment, it is only available to flash the software to the board as an unofficial Betaflight target.
1) Make sure you have installed all the needed drivers (Zadig, ImpulseRS)
2) Connect the board to your PC via TYPE-C cable while holding the "BOOT" button. After that, a device in DFU mode should be detected
3) Go to "Firmware Flasher" tab and load the .hex file by clicking on the "Load Firmware [Lokal]" tab
4) Click the "Flash Firmware" button
5) Once the firmware flashed successfully, press the "Connect" button and go to the "CLI" tab
6) Press "Load from file" button and select .config file
7) Load the commands to the CLI and reconnect the FC
   
[![Software flashing](http://img.youtube.com/vi/9PM7GFr9xXY/0.jpg)](http://www.youtube.com/watch?v=9PM7GFr9xXY)

# Schematics
This board is designed in the EasyEDA PCB creating tool. Here is the link where you can find all the schemas: https://oshwlab.com/poplavskyib/SOWA_F4
![Scheme_SOWA_FC](https://github.com/PoplavskyiB/SOWA_FC/assets/167243322/da704378-ec41-419f-8680-25431ffe545d)



<img src="https://github.com/user-attachments/assets/02c72859-bcfd-4577-8acb-458b7693caff" width="500">



# My contacts
For any questions or suggestions feel free to write me either by E-Mail poplavskiyb@gmail.com or via Telegram at @Poplavskyib (https://t.me/poplavskyib)


# Sponsors
I would like to express my sincere gratitude to the OSHWlab Stars 
program for their significant assistance in funding this project.

[<img src="https://github.com/PoplavskyiB/Sowa_FC/assets/167243322/6e54bb73-c080-4cfe-913c-1aecc6eb128a" width="200" height="200">](https://oshwlab.com/)
