# SOWA_FC
The main goal of this project is to create a free open-source flight controller you can use for your personal needs.
Features:
- STM32F405
- ICM42688P gyroscope + accelerometer
- Blackbox
- OSD
- 3-8S voltage
- Powerful 3.5A DC converters
- 3.3V / 5V / 10V rails
- SCL and SDA pins for GPS
- 6 UARTs
- 8 motor/servo outputs
- RX2 inverter (for SBUS)
- SWD and SWC pins for direkt programming via bootloader (ex. ST-Link)

Size: 40/40/1,6 mm

Drill diameter: 4 mm

Drill distance: 30,5 mm (center to center)

![Pinout](https://github.com/PoplavskyiB/SOWA_FC/assets/167243322/e67117a9-e37e-4fd5-865a-a49e9ddd90c3)

# Wiring diagram:
![Wiring](https://github.com/PoplavskyiB/SOWA_FC/assets/167243322/2423a88a-3354-4313-ac50-48c41776823a)
![WiringGPS](https://github.com/PoplavskyiB/SOWA_FC/assets/167243322/1aa1573c-b4a7-4d55-b7f9-d5b83f3ceccf)

# Software flashing

For this moment, it is only available to flash the software to the board as an unofficial Betaflight target.
1) Make sure you have installed all the needed drivers (Zadig, ImpulseRS)
2) Connect the board to your PC via TYPE-C cable while holding the "BOOT" button. After that, a device in DFU mode should be detected
3) Go to "Firmware Flasher" tab and load the .hex file by clicking on the "Load Firmware [Lokal]" tab
4) Click the "Flash Firmware" button
5) Once the firmware flashed successfully, press the "Connect" button and go to the "CLI" tab
6) Press "Load from file" button and select .config file
7) Load the commands to the CLI and reconnect the FC

# Schematics
This board is designed in the EasyEDA PCB creating tool. Here is the link where you can find all the schemas and PCB designs: https://easyeda.com/editor#project_id=f8ffbb6a306b4466b63a5c79629c3a20
![Schematic_SOWA-F4_2024-06-24](https://github.com/PoplavskyiB/SOWA_FC/assets/167243322/1b62517a-4905-46a9-8bb6-6d8feb7ada3f)


# My contacts

If you would like to contact me for any reason, feel free to write me either via E-Mail at poplavskiyb@gmail.com or via Telegram to @Poplavskyib (https://t.me/poplavskyib)

