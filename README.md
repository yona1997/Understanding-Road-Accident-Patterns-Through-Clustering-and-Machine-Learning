# Exploring Factors Contributing to Road Accidents in Israel: A Clustering Study
The purpose of this project is to utilize advanced clustering techniques to comprehensively understand the factors contributing to road accidents, particularly those with severe consequences. By analyzing parameters such as accident severity, weather conditions, and road state, the project aims to identify high-risk areas and inform authorities to implement targeted safety measures, ultimately reducing the occurrence of road accidents and improving overall road safety.

# Road Accident Factors Analysis - Machine Learning Project

## Project Overview
This project involves analyzing factors contributing to road accidents using clustering techniques in machine learning. By exploring geographic, environmental, and human-related factors, the project aims to identify patterns that could enhance accident prevention strategies.

## Objectives
- **Data Collection and Preparation**: The dataset is retrieved from an API and preprocessed to clean and structure the data for analysis.
- **Clustering Analysis**: Various clustering algorithms, including DBSCAN, KMeans, and Agglomerative Clustering, are applied to explore patterns in the data.
- **Geospatial Analysis**: Folium maps are used to visualize accident hotspots and geographic distribution.

## Techniques Used
- **Data Cleaning and Preprocessing**: Removal of irrelevant columns and handling of missing values.
- **Clustering Algorithms**: Application of DBSCAN, KMeans, and hierarchical clustering to group similar accident cases.
- **Evaluation Metrics**: Silhouette Score, Davies-Bouldin Score, and Calinski-Harabasz Score are used to evaluate the clustering quality.
- **Geospatial Visualization**: Folium and MarkerCluster are utilized to map accident locations and cluster results.

## Results
- Identification of key accident-prone areas and clustering patterns that highlight the significance of certain geographic and temporal factors.
- The clustering algorithms provide insights into common accident scenarios, enabling targeted interventions.

## Conclusion
The analysis reveals that clustering techniques can be effective in identifying patterns in road accident data, supporting better decision-making in urban planning and traffic management. The results demonstrate the potential for machine learning in enhancing public safety by analyzing complex datasets.

## Installation
To run this project, make sure you have the following Python packages installed:
- `numpy`
- `pandas`
- `sklearn`
- `folium`
- `matplotlib`

You can install the required packages using pip:
```bash
pip install numpy pandas scikit-learn folium matplotlib
