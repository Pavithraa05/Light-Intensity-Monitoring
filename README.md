# 💡 Light Intensity Monitoring System

This project monitors **light intensity** using a **Bolt IoT device** and visualizes the collected data with **Google Charts**.  
Different types of graphs are implemented to better understand variations in light levels.  

---

## ⚙️ Hardware Setup

- Connected an **LDR sensor** with Bolt WiFi module to measure light intensity.  
- Sensor data is uploaded to **Bolt Cloud** for storage and processing.  

**Sensor Connection**  
![Sensor Connection](1sT_Sensor_Conn.jpg)

**Bolt Cloud Linked with Sensor**  
![Bolt Cloud](Cloud_liked_1St_sensor.png)  

**Hardware Setup**  
![Hardware Setup](hardware_1st_sensor.png)

---

## 📜 Code for Data Collection

- The following code fetches sensor data from **Bolt Cloud**.  
- Data is stored for visualization using **Google Charts**.  

**Code**  
![Code](code_1st_sensor.png)  

**Collected Data**  
![Collected Data](Data_Collected_!st_sensor.png)

---

## 📈 Graphical Visualizations  

We use **Google Chart Library** to visualize sensor data in different formats.  

---

### 🔹 Line Graph  

- Shows **trends over time** for light intensity.  
- Useful for observing **rising and falling patterns**.  

**Line Graph Code**  
![Line Graph Code](Sesnor_data_withLineGraph_Code.png)

**Line Graph Output**  
![Line Graph Output](linegraph.png)
---

### 🔹 Bar Graph  

- Displays sensor values as **bars**.  
- Makes it easy to **compare values** at different times.  

**Bar Graph Code**  
![Bar Graph Code](bargraph_code.png)
**Bar Graph Output**  
![Bar Graph Output](barpgraph.png)

---

### 🔹 Scatter Graph  

- Plots sensor data as **points** across time.  
- Helps identify **fluctuations** and **outliers**.  

**Scatter Graph Code**  
![Scatter Graph Code](scatterGraph_code.png)

**Scatter Graph Output**  
![Scatter Graph Output](Scatter_graph.png)

---

### 🔹 Area Graph  

- Highlights the **cumulative data** by shading under the curve.  
- Shows overall **data distribution** clearly.  

**Area Graph Code**  
![Area Graph Code](area_graph_code.png)
**Area Graph Output**  
![Area Graph Output](area_graph.png)
---

### 🔹 Customized Area Graph  

- Improved visuals with **colors and custom styles**.  
- Makes charts more **engaging and user-friendly**.


-Explanation of Code

setChartLibrary('google-chart') → Use Google Charts library

setChartTitle('Light Intensity Monitoring System') → Title for the chart

setChartType('areaGraph') → Type of chart is Area Graph

setAxisName('Time','Light') → X-axis = Time, Y-axis = Light

setCrossHair(true) → Show crosshair guideline on hover

plotChart('time_stamp','light') → Plot data (time vs light)

**Customized Area Graph**  
![Customized Area Graph](area_graph_final_code.png) 
![Customized Area Graph Output](area_Graph_final.png)

### 🔹 Gauge Graph  

- The **Gauge Graph** works like a **speedometer**, showing real-time sensor value on a dial.  
- Useful for monitoring whether light intensity is **low, medium, or high** at a glance.  

**Gauge Graph Code**  
![Gauge Graph Code](gauge_code.png)

**Gauge Graph Output**  
![Gauge Graph Output](gauge_graph.png)

## ✅ Final Outcome
- Successfully monitored **real-time light intensity** using a sensor.  
- Stored data securely in **Bolt Cloud**.  
- Visualized data with **multiple types of Google Charts**.  
- Compared graphs (line, bar, scatter, area, gauge) to analyze light intensity trends.  

---

## 📚 My Learnings
- Gained hands-on experience with **Bolt IoT Cloud** and its APIs.  
- Learned how to **collect, log, and retrieve sensor data** from the cloud.  
- Practiced using the **Google Chart library** to represent IoT data in different formats.  
- Understood how to **customize visualizations** (titles, axes, crosshairs, etc.).  
- Improved knowledge of **IoT systems**, **data visualization**, and **GitHub project documentation**.  

---


