# arduino-nano-cc1101-T-charging-port-opener

////////////////////////////////////////////////
created by daan_tech1
////////////////////////////////////////////////

This file is only for educational purposes only
This file is only allowed to use on youw own T

This file only opens the charging port of T
This file only works in the EU


how to connect the CC1101 to Arduino Nano
+----------------+-------------------+----------------------------+
| CC1101 Pin     | Arduino Nano Pin  | Notes                      |
+----------------+-------------------+----------------------------+
| GDO0           | D2                | Optional: interrupt / status |
| GDO2           | D3                | Optional: interrupt / status |
| CSN / CS       | D10               | SPI Chip Select            |
| SCK            | D13               | SPI Clock                  |
| MOSI           | D11               | SPI Master Out             |
| MISO           | D12               | SPI Master In              |
| VCC            | 3.3V              | Make sure it’s 3.3V, not 5V! |
| GND            | GND               | Ground                     |
| VCO / VCC_RF   | 3.3V              | Some modules have extra RF supply |
+----------------+-------------------+----------------------------+

