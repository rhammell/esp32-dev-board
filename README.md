# esp32-dev-board
This repository contains the KiCad project files for a custom development board based on the ESP32-S3-WROOM module.

The board features a simplistic design, breaking out GPIO and power pins for easy prototyping, while using only essential components for power and data transfer. 

KiCad project files include the schematic and PCB designs which can be viewed and edited, and a full BOM with LCSC part numbers for sourcing and assembly. 

<p align="center">
  <img src="images/ESP32_Dev_Board_front.png" alt="ESP32 Dev Board Front" width="640">
</p>
<p align="center">
  <img src="images/ESP32_Dev_Board_back.png" alt="ESP32 Dev Board Back" width="640">
</p>

## Features

* **Core:** ESP32-S3-WROOM-1N8R8 module (8MB Flash + 8MB PSRAM).
* **USB Interface:** USB-C connector utilizing the S3's native USB Serial/JTAG controller.
* **Power:** Integrated 3.3V LDO regulator with a dedicated power LED indicator.
* **Prototyping:** Standard 2.54mm pitch header pins for full GPIO and power breakout.
* **Control:** Physical Reset and Boot buttons for manual flashing mode entry.
* **User IO:** Onboard programmable LED tied to **GPIO 21**.
* **Manufacturing:** Complete BOM included with **LCSC part numbers** for simplified sourcing and assembly.