# 🚗 Vehicle Route Optimization Engine

This project focuses on solving the **Vehicle Routing Problem (VRP)** in a real-world city (London) using geospatial data and graph theory. It computes the **shortest route** for a single vehicle to visit multiple delivery points using **Google OR-Tools**, **OpenStreetMap**, and **Python** visualization libraries.

---

## 📌 Features

- ✅ Real-world city data (London) with latitude/longitude coordinates  
- ✅ Graph creation using road networks from OpenStreetMap via OSMnx  
- ✅ Distance matrix computation based on **travel time** using Dijkstra’s algorithm  
- ✅ Route optimization using **Google OR-Tools**  
- ✅ Visualization of the optimized path using **Folium**  
- ✅ Animated simulation of the vehicle route using **Plotly Mapbox**  
- ✅ Heatmap for path connectivity and sanity check  

---

## 🗺️ Sample Output

<p align="center">
  <img src="https://user-images.githubusercontent.com/your-animation-link.gif" alt="Route Animation" width="700"/>
</p>

---

## 🔧 Tech Stack

| Tool            | Purpose                          |
|-----------------|----------------------------------|
| `Python`        | Programming language             |
| `Pandas`        | Data manipulation                |
| `OSMnx`         | Graph from OpenStreetMap data    |
| `NetworkX`      | Shortest path calculations       |
| `Google OR-Tools` | Route optimization solver (TSP) |
| `Folium`        | Map plotting                     |
| `Plotly`        | Animated route visualization     |
| `Matplotlib/Seaborn` | Static plots and heatmaps   |

---


---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/AnshuVairagade/Vehicle-Route-Optimization-Engine-.git
cd Vehicle-Route-Optimization-Engine-

---

## 📦 Requirements

To successfully run this project, ensure you have the following:

- ✅ Python **3.7+**
- 🌐 **Internet connection** (required for downloading road network data via OSMnx)
- 📄 A properly formatted `data_stores.csv` file containing:
  - `City`
  - `Street Address`
  - `Latitude`
  - `Longitude`

---

## 🧪 Results

After running the script, the following outputs are generated:

- 🚗 **Optimized route sequence** for the vehicle
- 📏 **Total travel distance and time**
- 🗺️ **Map visualization** of all delivery points and the computed route using **Folium**
- 🎞️ **Animated simulation** of the vehicle path using **Plotly Mapbox**
- 🔥 **Heatmap** showing graph connectivity and node relationships

---

## 🎯 Applications

This project can be extended and applied in various domains such as:

- 📦 **Last-mile delivery optimization** for e-commerce and logistics
- 🔧 **Field service route planning** (e.g., maintenance, inspection)
- 🚌 **Public transport route design**
- 🏙️ **Smart city planning** and mobility optimization

---


