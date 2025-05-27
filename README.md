# Spartan-6 XC6SLX9 FPGA Development Board

This is a compact FPGA development board built around the **Xilinx Spartan-6 XC6SLX9** chip. It is ideal for **digital system design**, **embedded applications**, **educational purposes**, and **research-oriented prototyping**.

With onboard USB interfacing via **FT2232H**, this board allows **direct programming and debugging** without the need for an external programmer. It also includes external **SDRAM** and **SPI Flash**, making it suitable for more complex projects such as **image processing**, **soft-core processors**, and **lightweight embedded operating systems**.

---

## ⚙️ Key Features

- **FPGA**: Xilinx Spartan-6 XC6SLX9 (TQFP-144 package)
- **USB Interface**:
  - FTDI FT2232H (Dual-channel: JTAG & UART)
  - Supports programming, debugging, and serial communication
- **Memory**:
  - 64Mbit (8MB) SDRAM (K4S561632) for data buffering and application memory
  - 32Mbit SPI Flash (W25Q32) for bitstream storage or application data
- **Clock Source**:
  - 50 MHz onboard oscillator
  - Can be scaled via internal DCM/PLL blocks within the FPGA
- **Power Supply**:
  - Powered via USB (5V) through FT2232H interface
- **Expansion & IO**:
  - GPIO headers for connecting external modules and peripherals
  - Supports interfacing with sensors, displays, and more

---
