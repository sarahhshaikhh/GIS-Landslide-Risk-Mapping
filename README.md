# 🌍 Landslide Safety Zones - GIS Mapping & Analysis <br>
This project leverages GIS (Geographic Information Systems) and data science to detect landslide-prone areas and identify safe evacuation zones in India from 2007 to 2021. By visualizing landslide data, the goal is to assist in disaster management by pinpointing regions at risk and providing safe areas for evacuation.

# 🔍 Key Features:
- **Landslide Detection:** Identifies regions prone to landslides based on historical data.
- **Safe Evacuation Zones:** Uses clustering algorithms to find and visualize safe zones for evacuation.<br> Severity Classification: Categorizes landslides by severity—Small, Medium, Large, Very Large, Catastrophic.
- Interactive Map: Visualizes landslides across India with color-coded points based on severity.
- AI-driven Clustering: K-means clustering to group landslides and suggest safe zones.

# 🚀 Technologies Used:
- **QGIS:** For handling GIS data and visualizing landslide regions.
- **Python:** For data manipulation, clustering, and generating insights.
- **Pandas & GeoPandas:** For data handling and geospatial data manipulation.
- **K-means Clustering:** Used to cluster landslides and suggest evacuation zones.
- **Matplotlib:** For plotting and visualizing results.
- **Shapefiles:** Data source for mapping landslide-prone regions.

# 🌍 Data Sources:
- Landslide data for India (2007-2021).
- Indian shapefile for geographic plotting.

# 📈 How It Works:
- **Data Preprocessing:** The dataset is cleaned and formatted for GIS mapping.
- **Landslide Categorization:** Landslides are classified by size (small to catastrophic) based on historical data.
- **Clustering Algorithm:** K-means clustering is applied to identify safe zones based on landslide clusters.
- **Visualization:** The results are displayed using QGIS and Matplotlib, showing regions of interest for disaster preparedness.

# 📋 Installation & Setup:
1. Clone the repository: <br>
git clone https://github.com/your-username/landslide-safety-zones.git
2. Install the necessary libraries:<br>
pip install pandas geopandas matplotlib
3. Load the data files (shapefiles and CSV) into QGIS.
4. Run the Python script (landslide_analysis.py) to process the data and display results.
