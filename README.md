This notebook, Twitter_Data_Geospatial_Density_Analysis.ipynb, performs a geospatial analysis of Twitter activity in London using a grid-mapping approach. It processes raw tweet data to visualize geographic "hotspots" and statistical distribution across the city.

Key Features
Data Integration: Merges multiple JSON data sources containing geo-tagged tweets from London (September 2022) into a unified dataset for analysis.

Haversine Grid Mapping: Implements the Haversine formula to calculate geographic distances and divides the London area into a precise 1km x 1km grid (48 rows x 59 columns).

Density Distribution: Calculates tweet counts per grid cell and visualizes the statistical distribution using logarithmic scaling to account for high-variance activity.

Geospatial Visualization: Generates a high-resolution Heatmap using Seaborn to identify peak areas of social media activity across London’s coordinates.

Results
A statistical summary of tweet density (mean, max, and frequency) across 2,832 geographic grid cells.

A visual heatmap representing the spatial concentration of Twitter users in the Greater London area.
