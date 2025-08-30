# 🌦 Power BI Real-Time Weather Dashboard

## 📌 Overview

This project is a **real-time weather dashboard** built using **Power BI**, powered by live data from [WeatherAPI.com](https://www.weatherapi.com/).

Unlike traditional dashboards that rely on static CSV/Excel files, this solution fetches **live JSON data** directly from APIs. It brings in **current weather conditions, forecasts, and air quality metrics**, and displays them in an **interactive, dark-themed dashboard** with **dynamic filters and automatic refresh**.

---

## ✨ Features

* 🌐 **Live Data** – Fetches real-time weather information from multiple cities.
* 🧹 **Data Modeling** – Separate tables for **Current Weather**, **Forecasts**, and **Air Quality**.
* 🎨 **Dark-Themed Design** – Sleek visuals optimized for readability.
* 🚦 **Dynamic KPIs** – Color-coded alerts for extreme weather & pollution.
* 🌅 **Extra Insights** – Sunrise/sunset, precipitation probability, and temperature trends.
* 🔄 **Automatic Refresh** – Always up-to-date in Power BI Service.

---

## 📂 Folder Structure

```
PowerBI-Weather-Dashboard/
│── Dashboard.pbix          # Main Power BI dashboard file
│── Images/
│   └── dashboard_preview.png
│── weather_icons/           # (Optional) Weather icons used in dashboard
└── README.md                # Project documentation
```

## ⚙️ Setup Instructions

### 1️⃣ Get Your API Key

* Go to [WeatherAPI.com](https://www.weatherapi.com/).
* Sign up for a **free account**.
* Copy your **API Key**.

### 2️⃣ Check API Endpoints

Examples:

```bash
# Current weather for London
http://api.weatherapi.com/v1/current.json?key=YOUR_KEY&q=London  

# 7-day forecast for New York
http://api.weatherapi.com/v1/forecast.json?key=YOUR_KEY&q=New York&days=7  
```

### 3️⃣ Connect to Power BI

* Open **Power BI Desktop**.
* Go to **Get Data → Web**.
* Paste the API URL (replace `CITY` & `YOUR_KEY`).
* Load & transform data in **Power Query**.

### 4️⃣ Data Transformation

* Merge multiple city data into one table.
* Split into **Current**, **Forecast**, and **Air Quality** tables.
* Format date/time columns & remove duplicates.
* Build relationships between tables.

### 5️⃣ Dashboard Design

* Apply **dark theme**.
* Add slicers for **City** & **Date**.
* Insert **KPIs with conditional formatting**.
* Display **weather icons dynamically** from URLs.

### 6️⃣ Automatic Refresh

* Publish to **Power BI Service**.
* Go to **Datasets → Schedule Refresh**.
* Set the desired refresh interval.

---

## 🔮 Future Enhancements

* 🌍 Add global map overlay with **live weather layers**.
* 📊 Include **historical weather & trend analysis**.
* 📱 Optimize for **mobile view** in Power BI.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🤝 Connect with Me

💼 **LinkedIn:** [Sneha_Khandelwal](https://github.com/sneha-0603])


