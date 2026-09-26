# Smart City Digital Twin: Exploratory Data Analysis (EDA) Framework

This project provides an end-to-end Exploratory Data Analysis (EDA) framework for analyzing multi-domain urban operational data. Designed as a **Smart City Digital Twin**, it bridges raw sensor and administrative data with strategic urban decision-making across **8 connected city sectors**: traffic mobility, public transportation, power grid infrastructure, weather patterns, emergency response, air quality, district demographics, and city events.

---

## 📌 Project Summary Highlights

1. **Integrated Data Architecture:**
   * Processes and standardizes **8 core datasets** comprising over **520,000 hourly operational records** per domain spanning a multi-year period (2023–2025 across 20 distinct districts).
   * Features systematic data preparation workflows, including automated timestamp casting, missing data resolution (attributable to sensor communication losses), duplicate handling, and outlier assessments.

2. **Cross-Domain Strategic Objectives:**
   * **Mobility Efficiency & Road Safety:** Analyzes spatial and temporal congestion patterns, rush-hour volume interactions, and environmental/traffic drivers of accident risks.
   * **Public Transit Performance:** Identifies demand-service mismatches by pinpointing high-occupancy districts suffering from delays or service disruptions.
   * **Infrastructure & Energy Resilience:** Evaluates peak electricity grid load, stress indices, blackout durations, and the stabilizing role of renewable (solar/wind) power generation.
   * **Environmental Monitoring:** Examines air quality dynamics (PM2.5, PM10, NO2, O3, CO) against weather conditions and urban activity levels.
   * **Emergency Services Optimization:** Tracks emergency event hotspots, severity burdens, and factors influencing emergency response times.
   * **City Event Impact Assessment:** Measures operational surges (traffic delays, transit occupancy) before, during, and after major public events.

3. **Data-to-Decision Pipeline:**
   * Structured to answer **14 key business questions** designed to identify cross-system operational bottlenecks and assist municipal authorities in prioritizing targeted district-level interventions.

---

## 🌆 Domain Datasets

| Dataset | Core Features / Metrics | Primary Granularity |
| :--- | :--- | :--- |
| **Traffic Mobility** | Vehicle count, avg speed, congestion index, incident count | Hourly per District |
| **Public Transit** | Passenger volume, occupancy rate, delay minutes, service status | Hourly per Line/District |
| **Power Grid** | Demand (MW), load stress index, blackout duration, renewable share | Hourly per Grid Zone |
| **Weather** | Temperature, precipitation, wind speed, visibility, extreme alerts | Hourly City-wide / District |
| **Air Quality** | PM2.5, PM10, NO2, AQI, primary pollutant source | Hourly per Sensor Station |
| **Emergency Response** | Incident type, response time, severity level, dispatched units | Incident level / District |
| **Demographics** | Population density, commercial vs. residential ratio, median income | District level (Static/Annual) |
| **City Events** | Event type, venue location, expected attendance, road closures | Event schedule basis |

---

## 🎯 Key Analytical Questions

1. How do traffic congestion spikes correlate with weather anomalies across major arterial corridors?
2. Which public transit lines consistently operate above target occupancy capacity during peak hours?
3. What environmental factors (wind, humidity, temperature) exert the strongest influence on localized PM2.5 levels?
4. How does energy grid stress behave during simultaneous peak temperature events and high traffic demand?
5. Where are the critical geographic bottlenecks where emergency response times exceed municipal SLA thresholds?
6. What is the net impact of major city events on surrounding district traffic speeds and transit delays?
