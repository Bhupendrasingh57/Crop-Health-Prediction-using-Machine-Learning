# Crop Health Detection using Multispectral Drone Imagery

## Project Overview
This project focuses on monitoring and analyzing crop health using multispectral data captured by drones. By utilizing various vegetation indices such as **NDVI, GNDVI, AND SAVI**,  we can identify areas of the field that are under stress (due to lack of water, nutrients, or pests) versus areas that are healthy.

## Key features
- -** Vegetation Indices:** Calculation and analysis of NDVI, SAVI, GNDVI, and EVI to assess plant vitality.
- -**Stress Detection:** Identifying "Healthy" vs"Stressed" crops based on NIR (Near-Infrared) and Red Edge reflectance.
- -**Data Visualization:** Comprehensive plots showing the distribution of crop health across the field.
- -**Scalable Solution:** A data-driven approach that can be integrated with real-time drone monitoring systems.

- ## Dataset Insights
- The dataset contains spectral data collected from a drone, including:
- -**Reflectance Values:** Blue, Green, Red Edge, and NIR bands.
- -**Calculated Indices:** Moisture Index, Canopy Density, and several vegetation indices.
- -**Spatial Data:** Grid coordinates (X, Y) for precise mapping of the field.

- ## Tech Stack
- -**Language:** Python 3.x
- -**Libraries:** - 'pandas & 'NumPy(Data Manipulation)
-       -'Matplotlib' & 'Seaborn'(Data Visualization)
-       -'Scikit-learn' (Exploratory Analysis)
-   ## Repository Structure
-   -'practice_.ipynb': The main Jupyter Notebook containing the analysis code and visualizations.
-   -'crop_data.csv': The dataset used for this analysis.
-   -'README.md': Project documentation.

-   ## Future Enhancements
-   -Integration of **Real-time Weather Data** to predict environmental stress.
-   -Application of **Advanced ML Model** (Random Forest) for automated classification.
-   -Inclusion of **Soil Moisture Sensors** data for higher accuracy.
-   ---
**Developed by:**[Bhupendra Singh]
