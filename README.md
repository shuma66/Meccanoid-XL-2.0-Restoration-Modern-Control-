# Meccanoid XL 2.0 Restoration & Modern Control 🦾
### By WAMYDH ELECTRONICS

A complete guide to repairing, upgrading, and controlling the **Meccanoid XL 2.0** using Kali Linux, custom hardware fixes, and community-verified software.

---

## 🛠 Hardware Repair & Battery Upgrades
Many units suffer from "No Power" or "Connection Lost" due to failures in the **DEV-06 Smart Servos**.

### **1. The "Dead Logic" Fix (OCB6F Regulator)**
The original 3.3V LDO regulator (**OCB6F**) often fails. 
- **The Fix:** Replace with a **3.3V LDO Regulator (SOT-89)**.
- **Pinout:** Pin 1: GND | Pin 2: VIN (6V-8.4V) | Pin 3: VOUT (3.3V).

### **2. Custom Battery Pack Build**
We replaced poor-quality stock cells with a custom **6V NiMH pack** using **5x AA 2000mAh Energizer cells** for superior torque and stability.

---

## 💻 Software & Control (Kali Linux)
Since official servers are offline, use our **Flask Web Dashboard** for local control via USB-HID.

- **Offline Control:** No internet or Spin Master servers required.
- **Real-time Interface:** Interactive sliders for all joints (Shoulders, Elbows, Neck).
- **Setup:** `pip install flask pyusb` and run `sudo ./venv/bin/python app.py`.

---

## 📱 Verified Android APK
Official apps are currently broken by server-authentication loops. Use our archived, verified version for direct Bluetooth control.

- **Download:** [meccanoid_fixed-aligned-debugSigned.apk](./APK/meccanoid_fixed-aligned-debugSigned.apk)
- **Features:** Bypasses "Internet Required" and "Server not reached" errors.
- **Pairing Code:** `000000` (six zeros).

---

## 🔗 Community Resources & Archives
For deep firmware fixes and official legacy documentation, we recommend:
- **[Neil Fraser’s Meccanoid Software Index](https://fraser.name):** The best archive for firmware updaters and offline data.
- **[Neil Fraser’s Meccanoid News](https://fraser.name):** Essential reading for understanding the robot's hardware logic.

---

## 🇪🇬 بالعربي (الملخص)
دليل شامل من **WAMYDH ELECTRONICS** لإصلاح روبوت Meccanoid XL 2.0. يشمل الدليل إصلاح منظم الجهد (OCB6F)، بناء بطارية 2000mAh مطورة، وتوفير نسخة APK تعمل بدون إنترنت، بالإضافة إلى واجهة تحكم برمجية لنظام Kali Linux.

---

## 🤝 Support
For professional repairs or consultation in Cairo, Egypt, contact **WAMYDH ELECTRONICS** via GitHub Issues or our official Facebook page.
