# TWRP-RMX3191-RUI4.0
TWRP for RMX3191 ( Realme C25 ) .

# installation Guide

- first You should unlock bootloader before Doing this
- After that you should reboot to fastboot
  ```
  adb reboot bootloader
  ```
- To check connect your device with adb
  ```
  fastboot devices
  ```
  - for install TWRP ( You should put recovery.img in some folder Android-Tools or Drag and drop file )
  ```
  fastboot flash recovery recovery.img
  ```
  - if you want reboot to recovery
  ```
  fastboot reboot recovery
  ```
  - We are done .
  # Donate me
  [![PayPal donate button](https://img.shields.io/badge/Donate-PayPal-blue)](https://www.paypal.me/mustafahamedIQ)
  
