<h1 align="center">RTOS-Making-Firmware</h1>

<p align="center">
  <img src="https://img.shields.io/badge/STM32-RTOS-blue?style=for-the-badge" alt="RTOS STM32">
  <img src="https://img.shields.io/badge/FreeRTOS-Embedded-brightgreen?style=for-the-badge" alt="FreeRTOS">
</p>

<p align="center">
  This project is an RTOS implementation on STM32 to manage multitasking and firmware control using STM32CubeIDE and FreeRTOS. 🚀
</p>

---

## ✨ Features

- ⏲ **Task Scheduling**: Scheduling various tasks with RTOS.
- 💡 **Multitasking**: Running various tasks, such as ADC, UART, OLED, and Button.
- 🔄 **RTOS Integration**: Using preemptive multitasking and delay management features.

## 🛠 Installation

To run this project, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/Lailymau/RTOS-Making-Firmware.git
2. Open the project in STM32CubeIDE.
3. Configure the hardware according to the STM32 board you are using.
4. Build the project and flash the firmware to your STM32 device.

## 📝 Prerequisites

- STM32CubeIDE: IDE for STM32 development.
- STM32CubeMX: For configuring STM32 peripherals and FreeRTOS.
- FreeRTOS: The RTOS middleware used.

## 📂 Node Diagram
    ├── Core
    │   ├── Inc            # Header files
    │   ├── Src            # Source code files
    ├── Drivers            # STM32 HAL Drivers
    ├── Middlewares        # FreeRTOS Middleware
    ├── .gitignore         # Git ignore file
    ├── README.md          # Dokumentasi proyek
    └── STM32CubeIDE       # File konfigurasi STM32CubeIDE

## 📷 Hardware Image

![Contoh Foto](https://github.com/Lailymau/demo-rtos/blob/main/demo.jpg?raw=true)

## 🎥 Demo Videos
![Contoh Video]

## 📄 Lisensi

This project is licensed under the MIT License. See the [LICENSE](https://github.com/Lailymau/RTOS-Making-Firmware/blob/main/LICENSE) file for more details.

## 📬 Kontak

Developed by LailyMau. If you have any further questions, feel free to contact me via [GitHub](https://github.com/Lailymau).
<p align="center">⭐ Don't forget to star this project if you found it useful! ⭐</p>
