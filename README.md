<h1 align="center">RTOS-Making-Firmware</h1>

<p align="center">
  <img src="https://img.shields.io/badge/STM32-RTOS-blue?style=for-the-badge" alt="RTOS STM32">
  <img src="https://img.shields.io/badge/FreeRTOS-Embedded-brightgreen?style=for-the-badge" alt="FreeRTOS">
</p>

<p align="center">
  Proyek ini adalah implementasi RTOS pada STM32 untuk mengelola multitasking dan kontrol firmware menggunakan STM32CubeIDE dan FreeRTOS. 🚀
</p>

---

## ✨ Fitur

- ⏲ **Task Scheduling**: Penjadwalan berbagai task dengan RTOS.
- 💡 **Multitasking**: Menjalankan task LED hijau dan merah secara paralel.
- 🔄 **RTOS Integration**: Penggunaan fitur preemptive multitasking dan delay management.

## 🛠 Instalasi

Untuk menjalankan proyek ini, ikuti langkah-langkah berikut:

1. Clone repositori ini:
   ```bash
   git clone https://github.com/Lailymau/RTOS-Making-Firmware.git
2. Buka proyek di STM32CubeIDE.
3. Konfigurasi perangkat keras sesuai dengan board STM32 yang digunakan.
4. Build proyek dan flash firmware ke perangkat STM32 Anda.

## Prasyarat

- STM32CubeIDE: IDE untuk pengembangan dengan STM32.
- STM32CubeMX: Untuk konfigurasi peripheral STM32 dan FreeRTOS.
- FreeRTOS: Middleware RTOS yang digunakan

## 🚀 Penggunaan

Setelah di-flash, task RTOS akan berjalan sesuai dengan jadwal. Task yang ada saat ini meliputi:
- FlashGreenLedTask: Task untuk mengontrol LED hijau.
- FlashRedLedTask: Task untuk mengontrol LED merah.
- Task baru dapat ditambahkan atau diatur di file Tasks.c.

## 📂 Struktur Folder

    ```bash
    ├── Core
    │   ├── Inc            # Header files
    │   ├── Src            # Source code files
    ├── Drivers            # STM32 HAL Drivers
    ├── Middlewares        # FreeRTOS Middleware
    ├── .gitignore         # Git ignore file
    ├── README.md          # Dokumentasi proyek
    └── STM32CubeIDE       # File konfigurasi STM32CubeIDE

## 📄 Lisensi

Proyek ini dilisensikan di bawah MIT License. Lihat file LICENSE untuk informasi lebih lanjut.

## 📬 Kontak

Dikembangkan oleh **LailyMau**. Jika ada pertanyaan lebih lanjut, hubungi saya melalui [GitHub](https://github.com/Lailymau).
<p align="center">⭐ Jangan lupa beri bintang (star) proyek ini jika bermanfaat! ⭐</p>
