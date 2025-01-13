---
title: "DYNATTIC ESP32C6 LED Panel"
description: "RGB LED Matrix Panel with OTA support"
---

# DYNATTIC ESP32C6 LED Panel

| Model | ESP32C6_LED_PANEL |
|-------|-------------------|
| Vendor  | DYNATTIC |
| Description | RGB LED Matrix Panel with OTA support |
| Exposes | light (state, brightness, color_xy), effect, power_on_behavior |
| Picture | ![DYNATTIC ESP32C6 LED Panel](../images/devices/dynattic/ESP32C6_LED_PANEL.png) |

## Notes
- Supports OTA updates through Zigbee2MQTT
- RGB color control (xy color space)
- Brightness control (0-254)
- Power-on behavior configuration
- Effects support (blink, breathe, etc.)

## Device Type
This is a Zigbee Router device.

## OTA Updates
The device supports OTA updates with following parameters:
- Manufacturer Code: 0x1234
- Image Type: 0x5678
