# Linki Drive - NFC Media Player

Media player controller for [Home Assistant](https://www.home-assistant.io/) based on ESP32 and PN532 NFC tag reader.

![Linki Drive](images/linki_drive.jpg)

Linki Drive is a media player controller for Linkis.

# What's a linki?

Linki is an open format that specifies the size, shape and position of NFC tag to be usable across different media player usage. It is inspired by 3.5" floppy discs that have a great phsyical properties to fit nice art work and still be portable. Main idea is to create common format for internet based media that is usable on any NFC reader (like smartphones). Linki format specifies that the link to media must be in NDEF fields. Linki is a nice physical object for an URL.

[Website of the Linki project](https://www.linki.cc)

# Linki Drive

The device is based on ESP32, includes sensors for touch, LED feedback and rotary encoder for volume control. The device is battery powered and chargable over micro USB port.

Linki Drive is open hardware project. All degrees of freedom allowed!

# Components

The electronics of Linki Drive are simple and based on off-the-shelf components. To create a physically stable device, it is adviced to buy or manufacture the PCB.

To build Linki Drive you will need:

## Electronics

* ESP32 board
* [PN532 NFC reader](https://www.aliexpress.com/item/32794353925.html)
* RGB LED
* rotary encoder
* custom PCB
* LiPo battery 
* Battery holder

## Materials

* M6 bolts or similar
* plastic washers
* M6 nuts
* M6 washers
* 6mm plywood
* wood glue
* paint, oil, wax etc

# Author

Artist Timo Toots created the format after designing a museum exhibit based on floppy discs. It has been used for media player purposes in his home since 2017. The project is opening this idea up for anybody interested. Latest advancements in Home Assistant software has made it possible to easily integrate it with any media player.
