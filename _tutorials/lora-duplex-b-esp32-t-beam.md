---
layout: tutorials
title: LoRa Duplex B with ESP32 T-Beam
hardware:
  - arduino
  - esp32
  - t-beam
  - lora
  - duplex
references:
  - name: Arduino LoRa firmware
    url: https://github.com/sandeepmistry/arduino-LoRa
  - name: Arduino LoRa firmware duplex example
    url: https://github.com/sandeepmistry/arduino-LoRa/blob/master/examples/LoRaDuplex/LoRaDuplex.ino
  - name: SEMTech SX1276/77/78/79 datasheet
    url: https://www.mouser.com/datasheet/2/761/sx1276-1278113.pdf
  - name: Adafruit RFM95W LoRa Radio Transceiver Breakout
    url: https://www.adafruit.com/product/3072
  - name: LilyGO-T-Beam Arduino Lora sender code example
    url: https://github.com/Xinyuan-LilyGO/LilyGO-T-Beam/blob/master/examples/ArduinoLoRa/LoRaSender/LoRaSender.ino
---

Send and receive at the same time from another node! Use this code with [duplex a](lora-duplex-a-esp32-t-beam).

```c
byte localAddress = 0xBB;
byte destination = 0xAA;
```
