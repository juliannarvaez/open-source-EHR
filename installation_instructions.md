# GNU Health Raspberry Pi Installation Instructions

## Supplies Needed

| Item                          | Cost   | Purchase Link                                       |
|-------------------------------|--------|-----------------------------------------------------|
| Raspberry Pi 4\*              | $100\* |[Raspberry Pi 4](https://www.canakit.com/raspberry-pi-4-starter-kit.html)|
| Micro HDMI to HDMI Cable\*    |        |               |
| Raspberry Pi 4 Power Supply\* |        |               |
| USB Card Reader Dongle\*      |        |               |
|  32GB MicroSD Card\*          |        |               |
|  Ethernet Cable               | $10    |[Ethernet Cable] (https://www.amazon.com/AmazonBasics-RJ45-Cat-6-Ethernet-Patch-Cable-25-Feet-7-6-Meters/dp/B00N2VIWPY/)        |
|  USB Keyboard                 | $13    |[USB Keyboard] (https://www.amazon.com/AmazonBasics-Matte-Keyboard-QWERTY-Layout/dp/B07WJ5D3H4/)|
|  USB Mouse                    | $8     |[USB Mouse] (https://www.amazon.com/Logitech-800dpi-Optical-3-button-Ambidextrous/dp/B003L62T7W)               |

\* Materials included with Canakit Raspberry Pi 4 Kit



## Downloading the Raspberry Pi .img File

1. You can either download directly the image from a browser or using wget through a terminal

`https://www.gnuhealth.org/downloads/embedded/raspberry/rpi4/`
`$ wget https://www.gnuhealth.org/downloads/embedded/raspberry/rpi4/gnuhealth-3.6.4-rpi4-SD-opensuse-leap15.2-xfce.img.gz`

2. Unzip the file onto the laptop/desktop computer

## Installing the .img File

1. Install the Raspberry Pi Imager application onto the laptop/desktop computer
https://www.raspberrypi.org/downloads/
2. Remove the SD card from the packaging
3. Insert the SD card into the USB Card Reader Dongle and insert the dongle into the laptop/desktop computer
4. Open the Raspberry Pi Imager application
5. Select the img. file downloaded from GNU health using the “Use Custom” .img option in the “Select OS” tab
6. Select the 32GB Mass Storage Device in the “SD Card” tab
7. Press write and wait for the SD card to be formatted and verified


## Initializing the GNU Health Application

1. Remove the SD card from the dongle and insert the newly formatted SD card into the Raspberry Pi 4
2. Insert the USB Keyboard, USB Mouse, Ethernet Cable, and HDMI cable into the Raspberry Pi 4
3. Log into OS using following credentials

`User: gnuhealth`
`Password: freedom`

4. Open GNU Health application
5. Login using following credentials

`Host: gh`
`Database: health36rpi`
`User name: admin`
`Password: gnusolidario`

#### Instructions adapted from:
[https://en.wikibooks.org/wiki/GNU_Health/The_Demo_database#Connection_to_the_GNU_Health_HMIS_and_LIMS
](https://en.wikibooks.org/wiki/GNU_Health/The_Demo_database#Connection_to_the_GNU_Health_HMIS_and_LIMS)
[https://en.wikibooks.org/wiki/GNU_Health/Embedded](https://en.wikibooks.org/wiki/GNU_Health/Embedded)
