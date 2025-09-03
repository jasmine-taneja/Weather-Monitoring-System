# IoT Weather Monitoring Dashboard

An interactive web dashboard showcasing live temperature and humidity readings. Powered by ThingSpeak and hosted on GitHub Pages.

** Live version**: https://jasmine-taneja.github.io/Weather-Monitoring-System/

---

##  Overview

This project presents a sleek and responsive **web dashboard** that visualizes data from an IoT-based weather monitoring system. The dashboard pulls in data from a ThingSpeak channel (ID: `3056719`) via API, displaying:

- Animated **live values** (latest temperature & humidity)
- Embedded **real-time graphs** from ThingSpeak

This makes it perfect for demonstrations, school projects, or small-scale IoT system monitoring.

---

##  Live Demo

Once live, the dashboard will display:

- Current **Temperature (°C)** and **Humidity (%)**
- Responsive charts embedded directly from your ThingSpeak channel

---

##  Technologies Used

| Component       | Description                                           |
|----------------|-------------------------------------------------------|
| HTML + CSS     | Structure and styling of the web dashboard            |
| JavaScript     | Fetches live data via ThingSpeak API every 5 seconds |
| ThingSpeak     | Cloud platform that collects IoT sensor data          |
| GitHub Pages   | Hosts the live website directly from this repository  |

---

##  Setup Instructions

If you'd like to deploy locally or adapt this dashboard:

1. **Clone the repository**

   ```bash
   git clone https://github.com/jasmine-taneja/Weather-Monitoring-System.git
   cd Weather-Monitoring-System
