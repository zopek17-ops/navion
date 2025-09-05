# NAVION Flight Computer PCB 🚀

This repository contains the design files for **NAVION**, a custom PCB flight controller built around the **ESP32-S3-WROOM-1U (N4R2)** module.  
It is designed for model rocket avionics, with sensor fusion, data logging, and pyro event control.

---

## ✨ Features

- **ESP32-S3-WROOM-1U (N4R2)** – dual-core MCU with Wi-Fi & Bluetooth  
- **MS5611** – high-resolution barometer for altitude measurement  
- **ICM-42688** – 6-axis IMU (accelerometer + gyro) for orientation and dynamics  
- **ADXL375** – 3-axis high-G accelerometer for launch and burnout detection  
- **MAX-M10S GPS** – GNSS module with active antenna support  
- **MicroSD card slot (SPI)** – onboard data logging  
- **AO3400 MOSFETs** – pyro channel control for separation/deployment  
- **USB Type-C** – programming and power  
- **3.3V LDO regulator (TLV767)** – power supply for ESP32 and sensors  

---



