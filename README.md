# LED-valonauha

Dependencies

WLED for ESP32 

Python 3.9

Esptool

Hyperion


Installation

Install Python 3.9

Install esptool in python "$ pip install esptool"

Flash bootloader it into your Esp32 with Python with command "esptool.py write_flash 0x0 ./esp32_bootloader.bin"

Flash wled into your Esp32 with "esptool.py write_flash 0x10000 ./juhis_wled.bin"

--This is custom wled compiled from source code. I deleted my wifi-credentials but it has custom light settings and programs.


If your program is running correctly, ESP32 should now have orange light

Access your wled by writing 4.3.2.1 to your browser

Connect to your wifi

Check your router device list and you should be able to access you wled settings



Bonus part for Hyperion:

Download latest Hyperion release from https://github.com/hyperion-project/hyperion.ng

Connect it to wled by writing your hostname/ip into controller

Configurate your led layout

Success!

You can turn of Hyperion-capture from wled interface anytime

