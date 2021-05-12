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

Flash wled into your Esp32 with "esptool.py write_flash 0x10000 ./WLED_0.12.0_ESP32.bin"

--You can compile your own wled version with source code and compile it with VisualStudio. I did so to make wifi-connection easier and and to code my own light-programs. I'm not going to share it for security purposes.


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

