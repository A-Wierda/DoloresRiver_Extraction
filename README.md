# DoloresRiver_Extraction
This code using NAIP imagery extract the Dolores River and calculate its surface area over time. 

## Geometries
1. Download DEM data from GEE for export into ArcGIS to caluclate sinuosity
2. Draw and export general Dolores streamline geojson to buffer to clip NAIP imagery (dolores_buffered)
3. Draw and export a smaller Dolores geometry geojson to clip to classified imagery to exclude holding ponds and shadows (dolores_river_geo)

## River Extraction
1. NAIP: Aug. 2021-used for test/train models
2. Method 1: Remove shadows, NDWI, NLCD mask
3. Method 2: NIR mask (#2)
4. Method 3: Random Forest Classification (#1)
5. Method 4: SVM Classification
6. Visual analysis using widgets & accurracy rating, classifcation reports, and confusion matrix

## Statistical Analysis of Dolores River
1. Sinuosity
2. Water Pixel count

## Analysis Per Year
1. Load Imagery
2. Extract river
3. Count pixels
