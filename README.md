# 8188GU-armbian-op5
Enable  USB WIFI 8188GU in Armbian   

## Steps

### Update your system 
`sudo apt-get update`

### Install armbian firmware
`sudo apt-get install armbian-firmware-full`

### List your usb devices, you can see realtek device in "CD ROM Mode"
`lsusb`

### Fix with usb-modeswitch
`sudo apt-get install usb-modeswitch`

### Last, execute this command
`sudo usb_modeswitch -KW -v 0bda -p 1a2b`

### Enjoy
