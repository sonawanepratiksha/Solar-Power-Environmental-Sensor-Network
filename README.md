
# 🌞 Solar-Powered Environmental Sensor Network 🌱

A low-power IoT system that collects environmental data (soil moisture, temperature, humidity, and light intensity) using an ESP32 microcontroller. The system is powered by a solar panel and stores data locally or can upload it to the cloud (optional).

---

## 📸 Project Overview

![alt text](<circuit diagram.png>)

This project aims to monitor the environment in agricultural or remote areas using clean solar energy. It is ideal for smart farming, garden monitoring, or educational IoT applications.

---

## 🔧 Features

- 🌱 Soil moisture detection
- 🌡️ Temperature and humidity monitoring (DHT11)
- ☀️ Light intensity measurement (LDR)
- 🔋 Solar-powered with rechargeable battery backup
- 📶 ESP32 microcontroller with Wi-Fi (optional cloud connection)
- 📊 Data logging (via Serial or storage)

---

## 🧰 Hardware Components

See [`component_list.md`](component_list.md) for the full list of parts.

---

## ⚙️ Circuit Diagram

> *(Insert your Fritzing diagram or setup image in the `images/` folder)*

---

## 🖥️ How It Works

1. ESP32 collects data from sensors every fixed interval.
2. Data is printed to Serial Monitor or sent to cloud (optional).
3. The system is powered entirely by solar energy using TP4056 and 18650 battery.

---

## 🛠️ Setup Instructions

1. Wire all components as shown in the circuit diagram.
2. Upload the code from `code/main.ino` using the Arduino IDE.
3. Use 9600 baud rate on Serial Monitor to observe data.
4. Power the system via the solar panel or directly with USB for testing.

---

## 📁 Project Structure

```
solar-sensor-network/
├── code/
│   └── main.ino
├── hardware/
│   ├── circuit_diagrams/
│   └── component_list.md
├── images/
│   └── setup_photo.jpg
├── data/
│   └── sample_readings.csv
├── README.md
└── LICENSE
```

---

## 🚀 Future Enhancements

- Integrate with Firebase or Thingspeak for live dashboard
- Add deep sleep mode to conserve energy
- Expand with additional sensors (rain, air quality)
- Create a 3D-printed weatherproof case

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributing

Feel free to fork the repo, open issues, or submit pull requests. Contributions are welcome!

---
