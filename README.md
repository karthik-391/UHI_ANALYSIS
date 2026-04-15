Urban Heat Island Analysis 

Project Description
This project focuses on analyzing the Urban Heat Island (UHI) effect using satellite-based temperature data. Urban Heat Island refers to the condition where urban areas are hotter than surrounding rural areas due to buildings, roads, and human activities.
In this project, we use daytime and nighttime land surface temperature data to study how heat is distributed across regions and to identify areas where heat is retained more.

🎯 Aim
To analyze and predict Urban Heat Island effects using day and night temperature data through geospatial and machine learning techniques.

📊 Dataset
Source: NASA Earthdata
Dataset: SEDAC-CIESIN SEDAC SDEI LST 2013
Year: 2013
Region: Asia
Format: GeoTIFF (.tif)
The dataset includes:
Daytime Maximum Temperature
Nighttime Minimum Temperature

⚙️ Tools & Technologies
Python,Google Colab,NumPy (data processing),Matplotlib (visualization),Rasterio (TIF file handling),Scikit-learn (machine learning)

🔍 What This Project Does
Visualizes temperature data (day & night)
Calculates Diurnal Temperature Difference (DTD)
Identifies heat hotspots
Detects Urban Heat Island regions
Divides regions into cool, moderate, and hot zones using K-Means
Predicts heat patterns using machine learning
Analyzes cooling efficiency and heat risk

📈 Results
Urban areas show higher temperatures, especially at night
Heat retention is clearly visible using DTD
K-Means clustering successfully groups regions into thermal zones
Machine learning models accurately predict UHI areas
Heat risk maps highlight vulnerable regions
