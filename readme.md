# 🌍 Disaster Response Visual Analytics Dashboard
### 🚀 *VAST Challenge 2019 - Mini Challenge 1*

📌 **An interactive data visualization dashboard to aid emergency responders in analyzing earthquake impact and efficiently allocating resources.**  

![image](https://github.com/user-attachments/assets/2e1361ec-7eda-446e-81e9-9f4526680c59)
  

---

## 📖 Overview
This project presents a **real-time visual analytics dashboard** designed to assist emergency responders in assessing the damage caused by an earthquake in **St. Himark**. By leveraging **D3.js, JavaScript, HTML, and CSS**, the dashboard integrates multiple interactive visualizations such as:
- 🗺️ **Choropleth Maps** – To identify the most affected areas.  
- 📊 **Bar & Violin Charts** – To analyze damage distribution and data reliability.  
- ⏳ **Stream Graphs & Slope Graphs** – To track changes in conditions over time.

This visualization system **enhances decision-making** by providing emergency teams with **insights into critical infrastructure failures**, prioritizing **resource allocation**, and assessing **data uncertainty** from citizen reports.

---

## 🛠 Technologies Used
- **Frontend:** JavaScript, D3.js, HTML, CSS  
- **Data Processing:** CSV & GeoJSON datasets  
- **Visualization Techniques:** Choropleth maps, bar charts, stream graphs, violin plots, pie charts, slope graphs  

---

## 🎯 Key Features
✅ **Interactive Map** – Displays earthquake damage across different neighborhoods.  
✅ **Time-Based Analysis** – Allows responders to track damage trends over time.  
✅ **Reliability Assessment** – Highlights uncertainty in citizen-reported data.  
✅ **Resource Optimization** – Helps prioritize neighborhoods for immediate response.  

---

## 📂 Dataset Information
The dashboard processes **citizen-reported earthquake data** from **St. Himark**.  
- 🏠 **Location-based impact** on **sewer, water, power, roads, medical, and buildings**.  
- 📅 **Time-based damage tracking** for informed decision-making.  
- 🌍 **GeoJSON Mapping** for spatial visualization.  

### 📁 Files Used:
- `mc1-reports-data.csv` – Contains categorical earthquake impact data.  
- `StHimark.geojson` – Geographical boundaries for spatial mapping.  

---

## 🚀 How to Run the Project
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/disaster-response-dashboard.git
cd disaster-response-dashboard
``` 
### 2️⃣ Open the Dashboard in Browser
Simply open the index.html file in a web browser to explore the interactive visualizations.

#### Alternative: Run a Local Server (Optional)
If you experience issues loading local files, use a simple HTTP server:
```bash
# Python 3 (built-in HTTP server)
python -m http.server 8000

# Then open: http://localhost:8000 in your browser
```


