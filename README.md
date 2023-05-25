# CaliforniaNDVI
Severe drought conditions in the 2010s wiped out over 62 million trees in California alone.
This project examined vegetation health in southern California and Nevada from 2013-2020. 
Three study sites were examined: The LA area, the Las Vegas area, and the California central valley (including Bakersfield and Fresno).
I calculated the NDVI of radiometrically corrected, cloud-free Landsat 8 scenes for 2013 - 2015 (when the drought was most severe), & 2020 (after the drought had mostly ended). I then calculated NDVI change for each scene from the drought period (2013 - 2015) to the post drought period (2020).
Python libraries used:
*rasterio
*xarray/rioxarray
*fiona
*geopandas
*numpy
*earthpy
