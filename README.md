# RescU
Assessing Rescue Factors in Densely Built Urban Areas

### Project Overview

This project explores the emergency rescue capabilities in densely populated urban environments through case studies in **Mong Kok (Hong Kong)** and **Dhaka (Bangladesh)**. These areas are known for their complex layouts, narrow streets, and high building density. 

The goal is to develop a **"rescue factor"**—a composite metric derived from geospatial analysis, image processing, and simulation—that quantifies the accessibility of different streets for emergency response. The resulting insights can support urban planning and emergency preparedness.

---

#### 1. Data Collection and Extraction

- **Satellite Imagery**  
  - [Sentinel Hub](https://www.sentinel-hub.com/)  
  - [Google Earth Engine](https://earthengine.google.com/)

- **Street-View Imagery**  
  - [Mapillary](https://www.mapillary.com/)

#### 2. Image Processing and Analysis

- **Building Layout Identification**
  - [QGIS](https://qgis.org/)
  - [GDAL](https://gdal.org/)

- **Escape Route Detection**
  - [Darknet (YOLOv4)](https://github.com/AlexeyAB/darknet)
  - [TensorFlow](https://www.tensorflow.org/)

#### 3. Proximity and Response Simulation

- **Fire Station Proximity**
  - [GeoPandas](https://geopandas.org/)

- **Rescue Time Simulation**
  - [OpenRouteService](https://openrouteservice.org/)

#### 4. Rescue Factor Calculation

- **Metric Development**
  - [NumPy](https://numpy.org/)
  - [Pandas](https://pandas.pydata.org/)

- **Statistical Analysis**
  - Assess relationships with building height, street width, and population density.

#### 5. Visualization and Reporting

- **Interactive Mapping**
  - [Folium](https://python-visualization.github.io/folium/)

- **Dashboard Development**
  - [Plotly Dash](https://plotly.com/dash/)
  - [Streamlit](https://streamlit.io/)

---

### Dataset and Tools

#### Datasets

- Satellite imagery (Sentinel Hub, Google Earth Engine)
- Street-level imagery (Mapillary)
- OpenStreetMap data for road networks and fire station locations
- Optional: Real-time traffic data from OSM-compatible APIs

#### Tools

- Image Processing: OpenCV, YOLOv5/Faster R-CNN
- Geospatial Analysis: QGIS, GDAL, GeoPandas, Shapely
- Routing Simulation: OpenRouteService
- Visualization: Folium, Streamlit, Dash

---

### 📄 License

To be determined.

