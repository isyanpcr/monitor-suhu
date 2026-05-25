# Indoor Air Monitoring System using React + Vite

This project is a Big Data and Internet of Things (IoT) based indoor air monitoring system developed using React and Vite. The system analyzes and visualizes room temperature and humidity data in real-time to help mitigate the risk of Sick Building Syndrome (SBS).

The project integrates ESP32 and DHT22 sensors with MQTT communication, MongoDB Atlas storage, Node.js backend processing, and real-time dashboard visualization.

## Project Title

“Indoor Air Data Analysis and Visualization for Sick Building Syndrome (SBS) Risk Mitigation”

## Group Members

- Fikri Al Hashif (2355301073)
- Muhamma Isyan Maulana (2355301137)
- Rifky Faerana Alfarizi (2355301179)
- Rifqy Wafianerdza (2355301180)

## Lecturer / AIL

- Dr. Juni Nurma Sari, S.Kom., M.MT
- Prengki Ardiansyah

## Institution

Informatics Engineering Study Program  
Politeknik Caltex Riau  
Academic Year 2025 / 2026

---

## Features

- Real-time temperature monitoring
- Real-time humidity monitoring
- MQTT-based IoT communication
- MongoDB Atlas cloud database
- Rule-based SBS risk analysis
- Interactive dashboard visualization
- Historical environmental data analysis
- Real-time monitoring with Socket.IO

---

## Technologies Used

### Frontend
- React
- Vite
- Chart.js / Recharts
- Socket.IO Client

### Backend
- Node.js
- Express.js
- Socket.IO

### Database
- MongoDB Atlas

### IoT & Data Pipeline
- ESP32
- DHT22 Sensor
- MQTT Broker
- Node-RED

---

## Big Data Pipeline

The system implements a Big Data Pipeline consisting of:

1. Data Ingestion  
   Collecting temperature and humidity data from ESP32 and DHT22 sensors through MQTT.

2. Data Preprocessing (ETL)  
   Extracting, transforming, and loading sensor data into MongoDB Atlas.

3. Data Storage  
   Storing environmental data in a cloud-based NoSQL database.

4. Data Processing  
   Processing sensor data using Node.js backend and rule-based SBS prediction.

5. Data Visualization  
   Displaying data through charts, dashboards, and real-time monitoring interfaces.

---

## Sick Building Syndrome (SBS)

Sick Building Syndrome (SBS) is a condition where building occupants experience discomfort caused by poor indoor environmental conditions.

Ideal room conditions:
- Temperature: 23°C – 26°C
- Humidity: 40% – 70%

The system classifies room conditions into:
- LOW Risk
- MEDIUM Risk
- HIGH Risk

based on environmental sensor readings.

---

## Visualization Types

- Line Chart (Time Series)
- Histogram
- Scatter Plot
- Bar Chart

These visualizations help users analyze room conditions more effectively.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/username/monitor-suhu.git
```

Go to project directory:

```bash
cd monitor-suhu
```

Install dependencies:

```bash
npm install
```

Run development server:

```bash
npm run dev
```

---

## Project Structure

```bash
monitor-suhu/
│
├── public/
├── src/
├── package.json
├── vite.config.js
└── README.md
```

---

## Conclusion

This project demonstrates the implementation of Big Data Pipeline and IoT technologies for indoor environmental monitoring. The system provides real-time monitoring, data analysis, and visualization to help identify potential Sick Building Syndrome risks inside buildings.

---

## License

This project is developed for academic purposes at Politeknik Caltex Riau.
