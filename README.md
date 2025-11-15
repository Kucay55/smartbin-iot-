# smartbin-iot-
Real-time Smart Bin IoT system for waste monitoring using ESP32, Firebase, and Web Dashboard.“Initialize this repository with a README”

# 🗑️ Smart Bin IoT – Real-Time Waste Monitoring

![Platform](https://img.shields.io/badge/platform-ESP32%20%7C%20Python%20%7C%20Firebase-blue)
![Status](https://img.shields.io/badge/status-experimental-yellow)
![License](https://img.shields.io/badge/license-MIT-green)

Sistem Smart Bin ini dirancang untuk memantau kapasitas tempat sampah secara real-time menggunakan sensor ultrasonik dan konektivitas cloud. Cocok untuk diterapkan di rumah sakit, ruang publik, dan fasilitas layanan masyarakat.

---

## 🚀 Tujuan Eksperimen

- Deteksi tingkat kepenuhan tempat sampah menggunakan sensor ultrasonik
- Pengiriman data ke Firebase secara berkala via Wi-Fi
- Visualisasi status bin melalui dashboard web
- Integrasi antara perangkat keras, perangkat lunak, dan cloud

---

## 📁 Struktur Folder
SmartBin-IoT/
├── Arduino/
│   └── smart_bin.ino
├── Python/
│   └── firebase_push.py
├── Dashboard/
│   ├── index.html
│   └── script.js
├── Docs/
│   ├── architecture_diagram.png
│   └── flowchart.pdf
├── requirements.txt
└── README.md

## ⚙️ Cara Menjalankan

### 1. Perangkat Keras
- Upload `smart_bin.ino` ke ESP32
- Pastikan sensor ultrasonik terhubung ke pin yang sesuai

### 2. Simulasi Python (Opsional)
```bash
pip install -r requirements.txt
python firebase_push.py
Dashboard Web
- Buka Dashboard/index.html di browser
- Pastikan konfigurasi Firebase sudah diatur di script.js

🔐 Konfigurasi Firebase
Pastikan Anda sudah membuat project Firebase dan mendapatkan:
- apiKey
- authDomain
- databaseURL
- projectId
Masukkan konfigurasi tersebut ke dalam file:
- smart_bin.ino
- firebase_push.py
- script.jsM
https://github.com/kucay/smartbin-iot

