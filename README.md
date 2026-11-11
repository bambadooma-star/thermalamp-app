# ThermalAmp ⚡🔥 - Official Download & Marketing Portal

[![Download APK](https://img.shields.io/badge/Download-ThermalAmp%20APK-00E5FF?style=for-the-badge&logo=android)](ThermalAmp.apk)
[![Android](https://img.shields.io/badge/Android-8.0%2B%20(API%2026%2B)-10B981?style=for-the-badge&logo=android)](https://github.com/bambadooma-star/thermalamp-app)
[![License](https://img.shields.io/badge/License-Proprietary-FF7043?style=for-the-badge)](https://github.com/bambadooma-star/thermalamp-app)

Official public website and direct download portal for **ThermalAmp** — the ultra-lean, real-time Android hardware thermal, power (W), current (mA), and capacity (mAh) telemetry utility with segregated **Idle vs Active Discharge** tracking and floating screen overlay HUD.

---

## 📥 Direct Download

* **Direct APK Download:** [Download ThermalAmp.apk](ThermalAmp.apk) (`9.7 MB`)
* **Live Website / Marketing Page:** View `index.html` via GitHub Pages!

---

## 🌟 Highlights

* **Real Actual Temperature:** Physical thermistor sensor telemetry (°C and °F) with 0.1°C precision.
* **Real Power (Watts):** Net charging and discharging wattage ($W = V \times A$).
* **Real Instantaneous Current (mA):** Microampere to milliampere normalized net current.
* **Coulomb Counter (mAh):** Accurate remaining capacity readout and full battery capacity.
* **Idle vs. Active Discharge Segregation:** Quiescent standby sleep drain vs active screen-on in-use drain.
* **4-Hour Sliding Min / Max Statistics:** Rolling window aggregations.
* **Floating Screen Overlay HUD:** Draggable floating pill showing live stats over any game or app.
* **High-Temp Timer Hold Alarm:** Protective threshold alarm with continuous hold timer.
* **Zero-Drain Eco Architecture:** 0.0% CPU overhead during screen-off sleep.

---

## 📲 Installation

```bash
adb install -r -d -g ThermalAmp.apk
adb shell appops set com.thermalamp.app SYSTEM_ALERT_WINDOW allow
adb shell am start -n com.thermalamp.app/.MainActivity
```
