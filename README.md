# Lirc.conf-and-lircrc-
Configs for Adafruit universal remote and Logitech iPod dockstation with alarm clock (s-00067)


Folders needs to be placed in: /data/plugins/system_controller/ir_controller/configurations/
Then you can instantly choose correct config in volumio IR plugin menu.


IMPORTANT!

Make sure that dtoverlay and gpio pin_in are correctly setupped in /boot/config.txt!!!

dtoverlay=lirc-rpi,gpio_in_pin=*
*-your pin nr (BCM)
