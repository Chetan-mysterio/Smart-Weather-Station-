# 🌦️ Digital Weather Station with Air Quality Monitoring (Arduino Project)

A low-cost, Arduino-based real-time **weather and air quality monitoring system**. This project measures **temperature**, **humidity**, **barometric pressure**, and **air quality**, displaying all data on a **0.96" SH1106 OLED display**. It's perfect for learning embedded systems, environmental monitoring, and basic IoT concepts.

---

## 📷 Project Preview

![Weather Station Front View](images/weather_station_front.jpg)
![Sensor Wiring](images/weather_station_wiring.jpg)

> _Place your actual project images in a folder named `/images` in the repo._

---

## 🔧 Features

- Real-time display of:
  - Temperature (°C)
  - Humidity (%)
  - Pressure (hPa)
  - Air Quality (analog reading)
- Compact OLED display (SH1106)
- Low-cost components (total under ₹1000)
- Beginner-friendly code and circuit
- Expandable with SD card or IoT modules

---

## 🧰 Components Used

| Component                 | Description                           | Cost (INR) |
|--------------------------|---------------------------------------|------------|
| Arduino Uno              | Microcontroller Board                 | ₹400       |
| DHT11                    | Temperature and Humidity Sensor       | ₹150       |
| BMP180                   | Barometric Pressure Sensor            | ₹200       |
| MQ135                   | Air Quality Sensor                    | ₹150       |
| SH1106 OLED Display (0.96") | 128x64 I2C OLED Display            | ₹180       |
| Jumper Wires + PCB       | For circuit connections               | ₹80        |

> 💸 **Total Estimated Cost:** ₹1000

---

## 🔌 Wiring Connections

| Component  | Arduino UNO Pins |
|------------|------------------|
| DHT11      | VCC → 5V, GND → GND, Data → D2 |
| BMP180     | VCC → 3.3V, GND → GND, SDA → A4, SCL → A5 |
| MQ135      | VCC → 5V, GND → GND, AOUT → A0 |
| SH1106 OLED| VCC → 3.3V, GND → GND, SDA → A4, SCL → A5 |

---

## 📚 Required Libraries

Install these from the Arduino Library Manager:

- `Adafruit_Sensor`
- `Adafruit_BMP085`
- `DHT sensor library`
- `Adafruit GFX`
- `Adafruit SH1106 (or SH110X)`

---

## 🚀 How to Use

1. Wire all components as per the table above.
2. Upload the provided Arduino sketch to the Uno.
3. Power the Uno via USB or battery.
4. Watch real-time data appear on the OLED screen.
5. Optionally extend the project with SD card logging or cloud IoT services.

---

## 🔮 Future Scope

- Add **SD card module** to log data locally
- Integrate **Wi-Fi (ESP8266/ESP32)** for remote monitoring
- Use **ThingSpeak or Blynk** for IoT dashboards
- Add **AI/ML models** for weather prediction
- Create **pollution alerts** via buzzer or mobile app

---

## 📍 Applications

- Indoor air monitoring in homes, offices, and schools
- Smart farming and greenhouse automation
- Educational labs for embedded systems and IoT
- Smart city prototypes for environmental data
- Portable weather stations for field researchers

---

## 📃 License

This project is open-source under the [MIT License](LICENSE).

---

## 🙌 Contributions

Feel free to fork this repository, suggest changes, or contribute enhancements via pull requests. All contributions are welcome!

---

## 📞 Contact

Created by **[Your Name]**  
📧 Email: [your.email@example.com]  
🌐 LinkedIn/GitHub: [yourprofilelink]

