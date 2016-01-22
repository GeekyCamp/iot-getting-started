# Parts list

We have tried to collect commonly used parts here, so that the it is easier to get started with your IoT project

## Boards
### ESP8266
A very popular board due to its price and built-in wifi. It can be programmed with Arduino, Lua and C++. There are several options
* [Newest know module] (http://www.aliexpress.com/item/5Pcs-lot-V3-Wireless-module-NodeMcu-4M-bytes-Lua-WIFI-Internet-of-Things-development-board-based/32469433622.html?btsid=1c01a4a2-e0a7-4607-9cc1-07bbf36e4851&ws_ab_test=searchweb201556_6%2Csearchweb201644_5_10001_10002_10005_301_10006_10003_10004_62_61%2Csearchweb201560_1%2Csearchweb1451318400_6148%2Csearchweb1451318411_6451&spm=2114.01010208.3.28.nqz0x0)
* [The old model] (http://www.aliexpress.com/item/New-Wireless-Module-5x-NodeMcu-Lua-WIFI-Internet-of-Things-development-board-based-ESP8266-with-pcb/32452157536.html?spm=2114.01010208.3.345.Wyl06k&ws_ab_test=searchweb201556_6,searchweb201644_5_10001_10002_10005_301_10006_10003_10004_62_61,searchweb201560_1,searchweb1451318400_6148,searchweb1451318411_6451&btsid=6e317f20-ffaa-4a95-8987-1b3e45c05c2a) used at the first GeekyCamp lecture
* [Naked module] (http://www.aliexpress.com/item/ESP8266-serial-WIFI-model-ESP-12-ESP12-Authenticity-Guaranteed-ESP-12E/32503234463.html?spm=2114.01010208.3.234.Ok7jTQ&ws_ab_test=searchweb201556_6,searchweb201644_5_10001_10002_10005_301_10006_10003_10004_62_61,searchweb201560_1,searchweb1451318400_6148,searchweb1451318411_6451&btsid=8efed771-3bce-4373-ae0b-14f968a1ba3f). This module is smaller and cheaper, but lacks USB to serial chip, so that an external USB to serial cable is required. It is more suitable for production (e.g. to save money and space) and for flying stuff, where weight matters a lot.

### Arduino
Very popular board with a lot of accessories (shields). This is the preferred choice if you want to work with some accesories (e.g. the ZumoRobot). More info on the [official website] (https://www.arduino.cc/)

### Raspberry PI
A full fledged Linux computer board. From IoT perspective, the main benefits of the board are that more complex Linux software, such as computer vision, can be used directly. Another advantage are the USB ports and the existing device drivers as well as higher level libraries, such as libnfc. There are different versions of Raspberry PI with varying capabilities. See [the shop] (https://www.raspberrypi.org/products/). There are also alternative boards with similar capabilities, such as the [Orange PI](http://www.orangepi.org/). The Orange PI comes in several models, of which the [Plus 2](http://www.aliexpress.com/store/product/Orange-Pi-Plus-2-H3-Quad-Core-1-6GHZ-2GB-RAM-4K-Open-source-development-board/1553371_32516755321.html) seems like the best option, due to the 2GB of RAM.
