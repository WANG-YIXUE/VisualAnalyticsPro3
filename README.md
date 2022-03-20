# VisualAnalyticsPro3

Visual Analytics Assessment 3 – Exploring Patterns in Census Data

This project aims to gain new insights into patterns of deprivation within Edinburgh (selected variables for deprivation analysis) and to assess the efficacy of self-organizing maps on the 2016 dataset to help decision-makers target resources effectively.

Edinburgh boundary map source: SG_SIMD_2016_EDINBURGH.shp

Source of raw data：SIMD16 indicator data.xlsx

Source of data for SOM in R：assignment3.csv

Where the data in assignment3.csv is normalized to the data in SIMD16 indicator data.xlsx. The standardization method: Log10. The formula is x'=log10(x)/log10(max(xi))

SOM analysis using R. 
Code located at: SOM
SOM analysis using the kohonen package, plotted using ggplot2.
Steps：
1. Data processing and data loading
2. Checking the data
3. SOM Training
4. SOM visualisation
5. Clustering of SOM results
6. SOM Spatial and Geospatial Linking
