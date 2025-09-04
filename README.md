# 💡 Light Intensity Monitoring System

This project monitors **light intensity** using a **Bolt IoT device** and visualizes the collected data with **Google Charts**.  
Different types of graphs are implemented to better understand variations in light levels.  

---

## ⚙️ Hardware Setup

- Connected an **LDR sensor** with Bolt WiFi module to measure light intensity.  
- Sensor data is uploaded to **Bolt Cloud** for storage and processing.  

**Sensor Connection**  
![Sensor Connection](![1sT_Sensor_Conn](https://github.com/user-attachments/assets/6ffd1f72-35a5-43f6-a780-b075e80a4504)
)  

**Bolt Cloud Linked with Sensor**  
![Bolt Cloud](<img width="1920" height="1080" alt="Cloud_liked_1St_sensor" src="https://github.com/user-attachments/assets/e38f24c4-9147-4c55-9d72-d6b760222e57" />
)  

**Hardware Setup**  
![Hardware Setup](<img width="1920" height="1080" alt="hardware_1st_sensor" src="https://github.com/user-attachments/assets/8056619f-51aa-4802-83ec-b90f4d9e3fef" />
)  

---

## 📜 Code for Data Collection

- The following code fetches sensor data from **Bolt Cloud**.  
- Data is stored for visualization using **Google Charts**.  

**Code**  
![Code](<img width="1920" height="1080" alt="code_1st_sensor" src="https://github.com/user-attachments/assets/19f1e521-b68d-4b55-a366-bf12b77b6cb7" />
)  

**Collected Data**  
![Collected Data](<img width="1920" height="1080" alt="Data_Collected_!st_sensor" src="https://github.com/user-attachments/assets/394794e7-f968-4e87-a981-c5fe5ff72507" />
)  

---

## 📈 Graphical Visualizations  

We use **Google Chart Library** to visualize sensor data in different formats.  

---

### 🔹 Line Graph  

- Shows **trends over time** for light intensity.  
- Useful for observing **rising and falling patterns**.  

**Line Graph Code**  
![Line Graph Code](<img width="1920" height="1080" alt="Sesnor_data_withLineGraph_Code" src="https://github.com/user-attachments/assets/16f65c63-1022-4168-8b5c-2d3ac88a4d27" />
)  

**Line Graph Output**  
![Line Graph Output](<img width="1920" height="1080" alt="linegraph" src="https://github.com/user-attachments/assets/90d41c4d-c4e9-4654-a1d6-2b3e99bfcc37" />
)  

---

### 🔹 Bar Graph  

- Displays sensor values as **bars**.  
- Makes it easy to **compare values** at different times.  

**Bar Graph Code**  
![Bar Graph Code](<img width="1920" height="1080" alt="bargraph_code" src="https://github.com/user-attachments/assets/298236dd-153e-4d7a-962e-e302bf259d65" />
)  

**Bar Graph Output**  
![Bar Graph Output](<img width="1920" height="1080" alt="barpgraph" src="https://github.com/user-attachments/assets/63775a68-61ad-4ffe-a749-d1c461cc17c3" />
)  

---

### 🔹 Scatter Graph  

- Plots sensor data as **points** across time.  
- Helps identify **fluctuations** and **outliers**.  

**Scatter Graph Code**  
![Scatter Graph Code](<img width="1920" height="1080" alt="scatterGraph_code" src="https://github.com/user-attachments/assets/bf133e1e-73ec-46f7-b3b9-d149de1615ad" />
)  

**Scatter Graph Output**  
![Scatter Graph Output](<img width="1920" height="1080" alt="Scatter_graph" src="https://github.com/user-attachments/assets/688b762f-c672-4a27-92d3-62f6f570fd94" />
)  

---

### 🔹 Area Graph  

- Highlights the **cumulative data** by shading under the curve.  
- Shows overall **data distribution** clearly.  

**Area Graph Code**  
![Area Graph Code](<img width="1920" height="1080" alt="area_graph_code" src="https://github.com/user-attachments/assets/d5a09898-5065-405a-b2f3-6c07f88b720c" />
)  

**Area Graph Output**  
![Area Graph Output](<img width="1920" height="1080" alt="area_graph" src="https://github.com/user-attachments/assets/6e343acd-3c96-441f-aa68-7e0979719eeb" />
)  

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
![Customized Area Graph](images/customized_areagraph.png)  
![Customized Area Graph](<img width="1920" height="1080" alt="area_Graph_final" src="https://github.com/user-attachments/assets/60829d99-e58e-44ce-a45e-f2462946c199" />
)

### 🔹 Gauge Graph  

- The **Gauge Graph** works like a **speedometer**, showing real-time sensor value on a dial.  
- Useful for monitoring whether light intensity is **low, medium, or high** at a glance.  

**Gauge Graph Code**  
![Gauge Graph Code](<img width="1920" height="1080" alt="gauge_code" src="https://github.com/user-attachments/assets/50648776-65b4-4f15-8a15-91dddf44045b" />
)  

**Gauge Graph Output**  
![Gauge Graph Output](<img width="1920" height="1080" alt="gauge_graph" src="https://github.com/user-attachments/assets/6cf72f82-a5a6-4444-a5de-b8608b18d141" />
)  

---


