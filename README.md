# Boardoza M032KG Educational Development Kit

The **Boardoza M032KG** is a comprehensive educational development kit designed around the **Nuvoton M032KG8AE** platform. It integrates a **M032 microcontroller** and a **Nu-Link2-Me-compatible debugger and programmer**, offering a complete environment for embedded development, learning, and rapid prototyping.

Inspired by the **Nuvoton Nu-Link2-Me**, this board is **fully compatible** with Nu-Link debugging tools and workflows, providing seamless integration with existing toolchains. It supports **on-board debugging, virtual COM (VCOM), power measurement, and modular expansion**.

This versatile kit includes peripherals such as a **rotary encoder**, **potentiometers**, **buzzer**, **RGB LED**, **NTC**, **LDR**, **DC motor driver**, **user LEDs and buttons**, **OLED Screen interface**, **ESP-01M Wi-Fi module header**, and more—making it ideal for education, experimentation, and IoT application development.

## [Click here to purchase!](https://www.ozdisan.com/maker-ve-iot-urunleri/boardoza/boardoza-egitim-kitleri/BOARDOZA-M032KG/1208247)

| Front Side | Back Side |
|:---:|:---:|
| ![M032KG Front](./assets/M032KG%20EVM%20Fornt.png) | ![M032KG Back](./assets/M032KG%20EVM%20Back.png) |

---

## Key Features

- **M032KG8AE MCU with 20 GPIO breakout header**
- **Compatible with Nu-Link2-Me**: Integrated on-board debugger & programmer
- **On-board Virtual COM Port (VCOM) support**
- **Power measurement header for ammeter connection**
- **OLED screen connector for UI/graphic development**
- **ESP-01M (Wi-Fi) header**
- **On-board peripherals:** Rotary encoder, potentiometer, user LEDs & buttons, NTC, LDR, buzzer, RGB LED
- **DC motor driver outputs**
- **USB Type-C for data/power, external 5–9V input support**
- **Multi-interface pinouts (1xUART, 1xI<sup>2</sup>C, 1xSPI)**

---

## Technical Specifications

**Model:** Boardoza M032KG Development Board  
**MCU Core:** Nuvoton M032KG8AE  
**Input Voltage:** 5V – 9V (via terminal block connector)
**USB Interface:** USB Type-C (data and power)  
**Debugger:** Nu-Link2-Me Compatible  
**Operating Temperature:** -25°C ~ +85°C  
**Board Dimensions:** 68mm x 116mm  
**Mounting Holes:** 4 × M3  

---

## Board Pinout Overview

### ESP-01M Wi-Fi Power Jumper (JP1)

| Pins | Function | Description |
|:---:|:---:|---|
| 1-2 | OPEN | ESP-01M Wi-Fi module power not active (default) |
| 1-2 | SHORT | ESP-01M Wi-Fi module power enabled |

---

### External Power Header (J6, J14, J18)

#### ( J6 ) 5V Power Output

| Pin | Name | Description |
|:---:|:---:|---|
| 1 | 5V | 5V Output |
| 2 | GND | Ground |

#### ( J14 ) 3.3V Power Output

| Pin | Name | Description |
|:---:|:---:|---|
| 1 | 3V3 | 3.3V Output |
| 2 | GND | Ground |

#### ( J18 ) Mixed Voltage Terminal 

| Pin | Name | Description |
|:---:|:---:|---|
| 1 | VIN | External Power Input (5V–9V) |
| 2 | GND | Ground |
| 3 | 5V | 5V Output |
| 4 | 3V3 | 3.3V Output |

---

### Debug Power Selection Jumper (J19)

| Pins | Function | Description |
|:---:|:---:|---|
| 1-2 | OPEN | Use USB from MCU side (default) |
| 1-2 | SHORT | Enable Nu-Link2-Me debugger connection |

---

### Motor Driver Output (J13)

| Pin | Name | Description |
|:---:|:---:|---|
| 1 | OUT1 | DC Motor Output |
| 2 | OUT2 | DC Motor Output |

---

### SWD Debug Header (J8)

| Pin | Name | Description |
|:---:|:---:|---|
| 1 | NC | Not Connected |
| 2 | VCC | Positive Supply |
| 3 | NC | Not Connected |
| 4 | DATA | SWD Data I/O |
| 5 | NC | Not Connected |
| 6 | CLK | SWD Clock |
| 7 | MCU_TX | MCU UART TX (PB.13) |
| 8 | nRST | MCU Reset |
| 9 | MCU_RX | MCU UART RX (PB.12) |
|10 | VSS | Ground |

---

### I2C Connector (J9)

| Pin | Name | Description |
|:---:|:---:|---|
| 1 | GND | Ground |
| 2 | 3V3 | Power |
| 3 | SCL | I2C0 PE.13 |
| 4 | SDA | I2C0 PC.8 |

---

### SPI Connector (J10)

| Pin | Name | Description |
|:---:|:---:|---|
| 1 | SS | SPI0 PA.3 |
| 2 | CLK | SPI0 PA.2 |
| 3 | MISO | SPI0 PA.1 |
| 4 | MOSI | SPI0 PA.0 |

---

### UART Connector (J11)

| Pin | Name | Description |
|:---:|:---:|---|
| 1 | RXD | UART4 PC.6 |
| 2 | TXD | UART4 PC.7 |
| 3 | GND | Ground |

---

### GPIO Extension Headers

#### ( J15 ) GPIO Group A

| Pin | Name | Description |
|:---:|:---:|---|
| 1 | PE.7 | Multi-Function |
| 2 | PE.6 | Multi-Function |
| 3 | PE.5 | Multi-Function |
| 4 | PE.4 | Multi-Function |
| 5 | PH.8 | Multi-Function |
| 6 | PH.9 | Multi-Function |
| 7 | PB.10 | Multi-Function |
| 8 | PB.11 | Multi-Function |
| 9 | PB.8 | Multi-Function |
|10 | PB.9 | Multi-Function |

#### ( J16 ) GPIO Group B

| Pin | Name | Description |
|:---:|:---:|---|
| 1 | PA.10 | Multi-Function |
| 2 | PB.0  | Multi-Function |
| 3 | PA.8  | Multi-Function |
| 4 | PA.9  | Multi-Function |
| 5 | PD.11 | Multi-Function |
| 6 | PD.12 | Multi-Function |
| 7 | PG.2  | Multi-Function |
| 8 | PD.10 | Multi-Function |
| 9 | PF.9  | Multi-Function |
|10 | PF.10 | Multi-Function |

---

## Nu-Link2-Me Compatible Debugger

### ( J2 ) Power Output

| Pin | Name | Description |
|:---:|:---:|---|
| 1 | 3V3 | 3.3V Output |

### ( J5 ) SWD/ICE Debug Connector

| Pin | Name | Description |
|:---:|:---:|---|
| 1 | VCC | Power |
| 2 | NC | Not Connected |
| 3 | DATA | SWD Data I/O |
| 4 | NC | Not Connected |
| 5 | CLK | SWD Clock |
| 6 | NC | Not Connected |
| 7 | nRESET | Reset Line |
| 8 | ICE_RX | Debugger UART RX |
| 9 | VSS | Ground |
|10 | ICE_TX | Debugger UART TX |

### ( J4 ) UART Jumper Settings

| Pins | Name | Function |
|:---:|:---:|---|
| 1-2 | TXD | Connect PB.13 (UART0_TXD) to debugger |
| 3-4 | RXD | Connect PB.12 (UART0_RXD) to debugger |
| 5-6 | MSG EN | Enable/disable Virtual COM messages |
| 7-8 | NC | Not Connected |

---

## 📄 Technical Documents & Datasheets

This section provides official datasheets and technical references for components integrated on the **Boardoza M032KG Educational Development Kit**. These resources offer valuable insight for hardware debugging, low-level integration, and educational use.

### 🧠 Core MCU & Main Board

- [**M031/M032 Series Datasheet (v2.02)**](./assets/DS_M031_M032_Series_EN_Rev2.02.pdf)  
  Complete electrical specifications and memory/peripheral descriptions of the Nuvoton M031/M032 MCU series.

- [**M031/M032 Series Technical Reference Manual**](./assets/M031-M032%20Series%20Technical%20Reference%20Manuel.pdf)  
  Register-level technical guide for firmware developers working directly with MCU hardware features.

- [**M032KG EVM Schematic (Board Reference)**](./assets/B-M032KG-EVM-R01_github_sch.pdf)  
  The schematic layout of the development board.

### 🔧 Peripheral & User Interface Modules

- [**Buzzer – SPT-1230B-03040 (SANCO)**](./assets/Buzzer.pdf)  
  A compact piezoelectric sound module rated for typical alert or feedback signaling applications.

- [**Rotary Encoder – EC1123S (KLS)**](./assets/Rotary%20Encoder.pdf)  
  A mechanical incremental encoder providing tactile feedback, ideal for menu navigation or analog input.

- [**Potentiometer – B100K L25-F**](./assets/Pot.pdf)  
  Used to provide variable analog voltage levels into the microcontroller (for ADC testing or UI controls).

- [**RGB LED – Everlight EAST1608RGBA0**](./assets/RGB%20Led.pdf)  
  Multicolor indicator LED supporting common anode/cathode wiring, ideal for status display.

- [**LDR – GL55 Series**](./assets/Ldr.pdf)  
  Light-dependent resistor for analog light intensity sensing, often used in ambient or auto-dim features.

- [**DC Motor H-Bridge Driver – DRV8837/8838 (TI)**](./assets/H-Bridge%20Driver.pdf)  
  Low-power dual H-Bridge motor driver for DC motor direction and speed control.

- [**ESP-01M Wi-Fi Module (ESP8285)**](./assets/ESP-01M.pdf)  
  A compact Wi-Fi module with embedded TCP/IP stack, compatible with ESP8266 toolchains.

- [**NTC Thermistor – TSM Series (THINKING)**](./assets/Ntc.pdf)  
  Compact surface-mounted thermistor for temperature sensing. Features high reliability and -40°C to +125°C operating range. UL/TUV certified and used for monitoring on-board thermal behavior.

---

## Version History

- V1.0.0 – Initial release

---

## Support

For technical assistance or questions, please contact: **<support@boardoza.com>**

---

## License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]  

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].  

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]  

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/  
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png  
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
