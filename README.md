# Land Cover and NDVI Change Analysis in Google Earth Engine

This project leverages the Google Earth Engine (GEE) platform to analyze and classify land cover, as well as compute NDVI (Normalized Difference Vegetation Index) change over time for the Kashmir region. The script utilizes MODIS and Landsat data to detect and visualize land cover changes, and it applies a machine learning classifier (Random Forest) to predict land cover for 2024.

## Features
- **Land Cover Analysis**: Uses MODIS Landcover data from 2020 to train a Random Forest classifier.
- **NDVI Calculation**: Computes NDVI values using Landsat imagery for the years 2015 and 2024.
- **NDVI Change Detection**: Computes the NDVI change between 2015 and 2024.
- **Visualization**: Renders the predicted land cover for 2024 and NDVI change on an interactive map.

## Getting Started
To run this code, you need a Google Earth Engine account and access to the GEE JavaScript code editor.

1. **Log in to GEE**: [Google Earth Engine Code Editor](https://code.earthengine.google.com/).
2. **Create a new script**: Copy this code and paste it into a new GEE script.
3. **Run the Script**: Centered on the Kashmir region, this script visualizes both NDVI change and the predicted land cover for 2024.

## Code Breakdown
1. **MODIS Landcover Data**: The script fetches MODIS land cover data for 2020 as the basis for land classification.
2. **Landsat NDVI Calculation**: Calculates NDVI using Landsat data for 2015 and 2024.
3. **Random Forest Classification**: Samples land cover data and trains a Random Forest classifier, which is applied to predict 2024 land cover.
4. **Map Visualization**: Adds the NDVI change layer and classified land cover layer to the map.

## Prerequisites
- Google Earth Engine Account
- Basic understanding of JavaScript and GEE API functions.

## Usage
1. Adjust the area of interest by modifying the coordinates for the `kashmir` variable.
2. Modify the sample size or filtering parameters as needed for better performance or accuracy.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
