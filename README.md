# SOLORA

**Solar. LoRa. Bitcoin.**

A solar-powered self-organizing LoRa mesh Bitcoin miner.

## What It Is

Solora is an open source hardware project. Each device:
- Mines real Bitcoin SHA-256 24/7 powered by sunlight
- Automatically forms a LoRa mesh network with nearby devices
- Requires no account, no registration, no ongoing service
- Works forever without any company or server

## Hardware

- Heltec WiFi LoRa 32 V3
- 2W 5V solar panel
- 1000-2000mAh LiPo battery

## Libraries Required

- RadioLib by Jan Gromes
- ESP8266 and ESP32 OLED driver for SSD1306 by ThingPulse
- WiFiManager by tzapu
- ArduinoJson by Benoit Blanchon v7

## Board Setup

- Board: Heltec WiFi LoRa 32(V3)
- Partition: Default 4MB with SPIFFS
- Board URL: https://espressif.github.io/arduino-esp32/package_esp32_index.json

## WiFi Setup

First boot creates a hotspot called **Solora-Setup**.
Connect your phone, open 192.168.4.1, enter your WiFi
credentials and optional Bitcoin address.

## The Principles

- Works forever without us
- No personal data collected ever
- Your Bitcoin address never leaves your device
- Open source — audit every line
- If we disappeared tomorrow your device keeps mining

## License

MIT — do whatever you want with it.

## Website

solora.network