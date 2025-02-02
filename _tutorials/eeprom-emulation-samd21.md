---
layout: tutorials
title: EEPROM Emulation with Arduino API
hardware:
  - arduino
  - m0
  - samd21
  - robotdyn
  - eeprom
  - flash
references:
  - name: RobotDyn SAMD21 M0-Mini a quick look
    url: http://www.armlearning.com/hardware/robotdyn-samd21-m0-mini-quick-look.php
  - name: Arduino Flash Storage library
    url: https://github.com/cmaglie/FlashStorage
  - name: Emulating as EEPROM code example
    url: https://github.com/cmaglie/FlashStorage/blob/master/examples/EmulateEEPROM/EmulateEEPROM.ino
  - name: Arduino EEPROM Library
    url: https://www.arduino.cc/en/Reference/EEPROM
prerequisites:
  - name: Blinky Arduino M0
    url: ./blinky-m0
---

Read and write to the flash memory of a SAMD21 board (E.g. Arduino M0 or RobotDyn SAMD21 M0-Mini) with the EEPROM Arduino API.

The following APIs are used in the example:

1. `EEPROM.isValid()`
1. `EEPROM.length()`
1. `EEPROM.commit()`
1. `EEPROM.write`
1. `EEPROM.read`
