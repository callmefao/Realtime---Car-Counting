# 🚗 DAP - Counting Car From Camera then Project It on Folium  

This web application provides **real-time vehicle counting** on a road, displayed in **4 interactive frames**. The application visualizes traffic conditions using a **map, vehicle counts, pie charts, and time series data**. The system updates every few seconds to provide accurate traffic insights.  

## 🎥 Demo Videos  

### 📡 Live Stream Demo  
🔗 Source: [YouTube Video](https://www.youtube.com/watch?v=FsL_KQz4gpw)  
![Live Stream Demo](demo/Youtube_livestream_video.gif)  

### 🎞 Recorded Video Demo  
🔗 Source: [YouTube Video](https://www.youtube.com/watch?v=wqctLW0Hb_0)  
![Recorded Demo](demo/Youtube_video.gif)  

## 🚀 Features  

- **🗺 Frame 1 - Map**: Displays a **map** of the road with a **line representing traffic conditions**.  
  - The **line color** updates **every 2 seconds** based on vehicle density.  
  - Traffic density is **predicted by `traffic_model`**.  

- **🚗 Frame 2 - Vehicle Counting**:  
  - **Real-time vehicle detection & counting**.  
  - Data is used by the **traffic model** to determine road congestion.  

- **📊 Frame 3 - Pie Chart**:  
  - Visualizes the **ratio of different vehicle types**: 🚌 Bus, 🚗 Cars, 🏍 Motorcycles, 🚚 Trucks.  

- **📈 Frame 4 - Time Series Chart**:  
  - **Tracks total vehicle counts over time**.  
  - **Updates every 5 seconds** to provide real-time insights.  

## ⚙ Installation  

### 📌 Prerequisites  

<p align="left">
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" alt="Python Logo" width="20" style="vertical-align: middle; margin-right: 10px;"/>
  <strong>Python 3.x</strong>
</p>

### 🛠 Setup  

1. **Clone this repository**:  

   ```bash
   git clone https://github.com/callmefao/Realtime---Car-Counting.git

2. **Install the required dependencies**:

    ```bash
    cd Realtime---Car-Counting
    pip install -r requirements.txt
