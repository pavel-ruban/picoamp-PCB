# straddle usb-c connector option (fork changes first 3 images):

pcb|top|bottom|pcb|3d|dev-pcb|dev-3d
--|--|--|--|--|--|--
![pcb](../../blob/main/images/picoamp-straddle-pcb.png)|![top](../../blob/main/images/picoamp-straddle-top.png)|![bottom](../../blob/main/images/picoamp-straddle-bottom.png)|![pcb](../../blob/main/images/indexspeakerdacsmol-pcb.png)|![3d](../../blob/main/images/indexspeakerdacsmol-3d.png)|![dev-pcb](../../blob/main/images/indexspeakerdacdev-pcb.png)|![dev-3d](../../blob/main/images/indexspeakerdacdev-3d.png)

* usb c connector https://aliexpress.com/item/1005003274837739.html
* push button soldered on top of the pcb to interact with steamvr dashboard
https://aliexpress.com/item/32622269899.html?sku_id=59394778361

# indexspeakerdacsmol

compact usb-i2s dac using rp2040 and max98360a for powering speakers, like index bmr drivers

* I forgot the silkscreen for usb pins, but they should be clear from below images.
* 0201 components suck to work with.
* intended to use with a usb-c cable, however the CC wire needs 5.1K pull-down to ground which I forgot about

firmware for the device is at https://github.com/sctanf/picoamp

![finished board](../../blob/main/images/DSC_0404.webp)
