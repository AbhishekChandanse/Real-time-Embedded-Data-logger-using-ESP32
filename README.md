# 📈 Real-Time Embedded Data Logger using ESP32

A real-time data logging system built on the **ESP32 microcontroller** that collects and stores environmental data from various sensors to an **SD card**, with accurate time-stamping via an **RTC module**. Ideal for applications like weather monitoring, environmental research, and IoT systems.

---

## 🔧 Features

- 📅 **Real-Time Clock (RTC)**: Time-stamps each data entry using a DS3231 module.
- 🌡️ **DHT11 Sensor**: Logs ambient temperature and humidity.
- ⛰️ **BMP180 Sensor**: Records atmospheric pressure and calculates altitude.
- 💾 **SD Card Module**: Stores data in `.CSV` format for easy analysis.
- 🔁 **Periodic Logging**: Data is logged at fixed intervals using a timer or delay loop.
- 🔌 **Low Power Design**: Suitable for continuous operation in remote environments.

---

## 🧰 Hardware Used

- ESP32 Dev Board  
- DHT11 Temperature & Humidity Sensor  
- BMP180 Pressure & Altitude Sensor  
- DS3231 RTC Module  
- Micro SD Card Module  
- Jumper wires and breadboard

---

## 🛠️ Software & Tools

- Arduino IDE / PlatformIO  
- C/C++ (Embedded C)  
- CSV formatting for data storage  
- Serial monitor for debugging

---

## 📂 Data Sample output

Date, Time, Temperature (°C), Humidity (%), Pressure (Pa)
2025-04-17, 14:35:22, 25.6, 60.2, 100870


