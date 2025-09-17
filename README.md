<h1 align="center">📡 Mobile Network Coverage & QoS Analyzer</h1>

<p align="center">
  <img src="https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Chart.js-4.4-FF6384?logo=chartdotjs&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Active-blueviolet?style=for-the-badge" />
</p>

---

<div align="center">
  <img src="https://media.giphy.com/media/jnJQDOPIfv1ZjR6v7X/giphy.gif" width="80" />
  <b>Advanced analytics with ML predictions and interactive visualizations</b>
  <img src="https://media.giphy.com/media/jnJQDOPIfv1ZjR6v7X/giphy.gif" width="80" />
</div>

---

## ✨ Features

- 🎯 **Data Upload & Parsing** – Upload CSV files with network measurement data  
- 🚀 **Sample Data Generator** – Quickly generate mock network data for testing  
- 📊 **Interactive Dashboard** – Signal strength bar chart, scatter plots & more  
- 🧠 **Machine Learning Predictions** – Built-in linear regression predictor  
- 🔍 **Filters & Insights** – Apply locality, network type, and latency filters  
- 🛡 **Error Handling** – Debug panel and graceful error recovery  

---

## 🛠️ Tech Stack

- ⚛️ **React** (via Babel CDN)  
- 📈 **Chart.js** for visualizations  
- 🎨 **CSS3** with gradients, shadows, and responsive layout  
- 🤖 **Custom ML (Linear Regression)** in Python


---

## 📊 Dataset Format  

CSV should have the following columns:  

| Column | Description |
|--------|-------------|
| timestamp | Time of measurement |
| locality | Area / location |
| latitude | Geo latitude |
| longitude | Geo longitude |
| signalStrength | Signal in dBm |
| signalQuality | Quality in % |
| dataThroughput | Mbps |
| latency | ms |
| networkType | 3G / 4G / 5G / LTE |
| bb60cMeasurement | SDR metric |
| srsranMeasurement | SDR metric |
| bladeRFMeasurement | SDR metric |

---


