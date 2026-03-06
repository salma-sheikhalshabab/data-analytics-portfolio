# 🏠 IoT Smart Home Analysis

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![IoT](https://img.shields.io/badge/IoT-Analytics-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📌 Project Overview

An interactive IoT monitoring dashboard built in **Power BI** that analyzes smart home sensor data across multiple rooms. The dashboard tracks **power consumption, temperature, humidity, and device status** — providing actionable insights for energy efficiency and home automation.

A **custom 3D map visual** was used to display power consumption by room area, making the dashboard highly visual and intuitive.

---

## 📊 Dashboard Preview

![Dashboard](dashboard.png)

---

## 🔍 Key Insights

| Metric | Value |
|---|---|
| Total Power Consumption | 61.94 kW |
| Avg Temperature | 24.1 °C |
| Avg Humidity | 50% |
| Occupancy Rate | 0.5% |
| Devices ON | 27 (75%) |

### 📈 Highlights:
- **Entrance** consumes the most power (11.89 kW) despite being a transitional space
- **Bathroom** has the highest temperature (28°C) and humidity (75%) — potential energy waste
- **Bedroom** is the most energy-efficient room (8.58 kW)
- 75% of devices are currently **ON** — opportunity to optimize with automation rules
- **Living Room** maintains the most comfortable conditions (23.6°C, 42% humidity)

---

## 💡 Recommendations

1. **Install motion sensors** in the Entrance to reduce unnecessary power consumption
2. **Add ventilation controls** in the Bathroom to manage high humidity (75%)
3. **Automate device schedules** — 25% of devices OFF suggests potential for smart timers
4. **Monitor Bedroom temperature** — currently lowest at 22°C, may need heating optimization

---

## 🛠️ Tools Used

- **Power BI Desktop** — Dashboard & Visualizations
- **Custom Map Visual** — 3D floor plan for room-level analysis
- **Power Query** — Data transformation & room categorization
- **DAX** — Aggregations & conditional measures

---

## 📁 Files

```
📁 iot-smart-home-analysis/
├── 📊 IoT_Dashboard.pbix
├── dashboard.png
└── 📄 README.md
```

---

## 📚 Data Source

- **Dataset:** IoT smart home sensor readings
- **Features:** Room ID, Device Status, Power (kW), Temperature (°C), Humidity (%), Occupancy
