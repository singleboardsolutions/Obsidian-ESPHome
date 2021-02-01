# Obsidian-ESPHome
ESPHome profiles for RPi hats using the Obsidian ESP32
-----

This repo contains ESPHome yaml profiles for Raspberry Pi hats compatible with the Obsidian ESP32: 
https://www.crowdsupply.com/thomas-mckahan/obsidian-esp32

Note that these are the contents needed after the auto-generated parts if you use the wizard,
These do not contain the header or the wifi information/etc.  Cut and paste the contents of these
files into your node definitions.

Boards Supported:

| Board | Notes |
|--|--|
| [Adafruit TFT Bonnet](https://www.adafruit.com/product/4506) | Screen resolution may be incorrect, not fully tested |
| [Pimoroni Automation Hat](https://shop.pimoroni.com/products/automation-hat) | No LED's or ADC at present, lacking drivers |
| [Pimoroni Automation Hat Mini](https://shop.pimoroni.com/products/automation-hat-mini) | No LCD or ADC at present, lacking drivers |
