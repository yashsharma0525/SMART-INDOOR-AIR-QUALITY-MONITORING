# SMART-INDOOR-AIR-QUALITY-MONITORING
Smart Air Quality Monitoring System An IoT-based indoor air quality monitoring system using ESP32, DHT11, SGP30, and OLED display with real-time data visualization and remote dashboard integration via ThingsBoard. Monitors temperature, humidity, TVOC, and eCO2 levels for smarter, healthier environments.
## 📸 Project Overview

🛠 Hardware Components
Component	Function	ESP32 Connection
ESP32	Microcontroller (WiFi/BLE)	-
SGP30	Measures TVOC & eCO₂	I2C (GPIO 21-SDA, GPIO 22-SCL)
DHT11	Measures Temperature & Humidity	GPIO 4 (Digital Pin)
OLED (SSD1306)	Displays sensor data	I2C (GPIO 21-SDA, GPIO 22-SCL)
ThingsBoard Platform
Breadboard & Jumper Wires	Circuit connections	-
5V Power Supply	USB or Battery	Micro-USB or 5V Pin

---

## 📦 Features

- 🌡️ Real-time temperature and humidity monitoring  
- 🏭 Air quality measurement (TVOC & eCO₂)  
- 📟 OLED display for local visualization  
- ☁️ Sends data to ThingsBoard dashboard  
- 🔔 Can be extended with alert systems for poor air quality  
- 📊 Historical data graphing via cloud

---

## 🧰 Hardware Required

 Component:-
 ESP32 Development Board 
 DHT11 Sensor | 1 |
 SGP30 Sensor | 1 |
 SSD1306 OLED Display | 1 |
 Breadboard and Jumper Wires | As required |
 Power Source (USB or Battery) | 1 |



## 🔌 Circuit Diagram

![Screenshot 2024-11-11 224811](https://github.com/user-attachments/assets/e2abaf3f-47e2-4911-ae40-cdf97ec18822)

## Block Diagram 
![Screenshot 2024-11-11 230415](https://github.com/user-attachments/assets/0e73c6c1-dcf8-4a9f-912e-9ce074347c8a)

## FlowChart
![Screenshot 2024-11-04 220555](https://github.com/user-attachments/assets/14883e0b-e440-4758-af9c-846197491f6a)

---

## 💻 Software Required

- Arduino IDE 
- ESP32 Board Support
- Required Libraries:
  - `Adafruit_SGP30`
  - `Adafruit_Sensor`
  - `DHT`
  - `Adafruit_SSD1306`
  - `Wire`
  - `WiFi.h`
  - `HTTPClient.h` or MQTT for ThingsBoard

---

## 🚀 How to Run

1. Clone or download this repository.
2. Open the code in Arduino IDE.
3. Install the required libraries from Library Manager.
4. Add your Wi-Fi credentials and ThingsBoard device access token in the code.
5. Upload the sketch to ESP32.
6. View real-time data on OLED and ThingsBoard dashboard.

---

## 🌐 ThingsBoard Setup

1. Sign up at [https://thingsboard.io](https://thingsboard.io)
2. Create a new device.
3. Copy the **Access Token** and paste it into the ESP32 code.
4. Use default ThingsBoard MQTT broker: `thingsboard.cloud`
5. Create widgets on the dashboard to display your data.

---

## 📊 Sample Output

Temperature: 28.5 °C
Humidity: 60 %
TVOC: 150 ppb
eCO₂: 420 ppm


---

## 📈 Future Improvements

- Add PM2.5/PM10 sensors (e.g., SDS011)
- Buzzer/LED for air quality alerts
- Mobile app integration
- Power optimization for solar use

---

## 🧠 Applications

- Smart homes
- Greenhouses
- Indoor farms
- School/office air monitoring
- Health-sensitive zones


## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.



## 📜 License

This project is open-source under the [MIT License](LICENSE).



## 👨‍💻 Developed By

**Yash Sharma**  
B.Tech CSE | Invertis University  
Email: yashtech0.525@gmail.com  
LinkedIn: www.linkedin.com/in/yash-sharma-126b3b2a0




