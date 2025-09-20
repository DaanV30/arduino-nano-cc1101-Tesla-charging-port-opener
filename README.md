# arduino-nano-cc1101-T-charging-port-opener


created by daan_tech1


This file is only for educational purposes only
This file is only allowed to use on youw own T

This file only opens the charging port of T
This file only works in the EU

how to connect the CC1101 to Arduino Nano
🔹 Arduino Nano D2  → CC1101 GDO0    (optional: interrupt / status) ⚡
🔹 Arduino Nano D3  → CC1101 GDO2    (optional: interrupt / status) ⚡
🔹 Arduino Nano D10 → CC1101 CSN/CS  (SPI Chip Select) 🟢
🔹 Arduino Nano D11 → CC1101 MOSI    (SPI Master Out) 📨
🔹 Arduino Nano D12 → CC1101 MISO    (SPI Master In) 📩
🔹 Arduino Nano D13 → CC1101 SCK     (SPI Clock) ⏱️
🔹 Arduino Nano 3.3V → CC1101 VCC    (do NOT use 5V!) 🔋
🔹 Arduino Nano GND → CC1101 GND      (Ground) ⚫
🔹 Arduino Nano 3.3V → CC1101 VCO/VCC_RF (if present, extra RF supply) 🌐
