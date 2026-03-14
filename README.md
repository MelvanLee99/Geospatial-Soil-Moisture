# Geospatial Soil Moisture

A project of Visualization in Science. Our purpose of this project is to apply geostatistical interpolation techniques to generate continuous soil moisture maps of peatland regions in Sumatra, Indonesia. Soil moisture is a critical indicator of peatland hydrology and fire risk, yet monitoring systems often rely on sparse observation points.

Using 2023 PRIMS (BRGM) peatland monitoring data, the study focuses on three major peatland provinces: Riau, Jambi, and South Sumatra, with a total of 7,584 spatial sampling points.

Key contributions include:
- Preprocessed large-scale spatial datasets using GeoPandas (coordinate geometry, duplicates, missing values).
- Conducted experimental semivariogram analysis to model spatial autocorrelation.
- Fitted theoretical variogram models (Gaussian, spherical, exponential) and selected optimal models using RMSE evaluation.
- Implemented and compared Ordinary Kriging and Universal Kriging for soil moisture interpolation.
- Produced continuous contour maps highlighting regional moisture variability and fire-risk prone dry peat zones.
- Identified methodological differences across provinces:
  - Universal Kriging captured stronger spatial trends in heterogeneous regions (e.g., Jambi).
  - Ordinary Kriging preserved local variability in more homogeneous areas (e.g., Riau, South Sumatra).
