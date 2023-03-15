# OregonLampreyDistributionModel
### Species Distribution Models for Pacific Lamprey and Western Brook Lamprey
#### Parker Jung
I will be making models to predict the presence of pacific lamprey and western brook lamprey in the southern Oregon coastal watershed based on detected presence at sample sites. The objective of this project is to use species presence at points to visualize the distributions on a watershed scale.
<br>
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Datasets**
1. South Slough Lamprey eDNA Results (2019-2021)
2. Oregon 10m Digital Elevation Model
-  https://spatialdata.oregonexplorer.info/geoportal/details;id=7a82c1be50504f56a9d49d13c7b4d9aa
-  https://ftp.gis.oregon.gov/framework/elevation/DEM/Statewide_Filegeodatabase/DEM_DOWNLOAD_HELP_README.txt
3. Canopy Cover and Forest Type from OSU LEMMA
- https://lemma.forestry.oregonstate.edu/data/species-maps
4. Oregon Watershed Boundary Dataset (Hydrologic Unit Boundaries) - 2015
- https://spatialdata.oregonexplorer.info/geoportal/details;id=4b1b008d5a764a209b2df040689c0779
5. Oregon Water Bodies - 2005
- https://spatialdata.oregonexplorer.info/geoportal/details;id=3439a3c43f9f4c4499802f55898b7dd8
\
<br>**Python Packages**
- jupyter
- matplotlib
- geopandas
- numpy
- pandas
- rasterio
- sklearn
\
<br>**Methods**
- Get data for landcover, elevation, slope, aspect, and hillshade from Oregon Spatial Data Library layers.
- Filter and format data in ArcGIS Pro, calculate stream density
- Test correlation between species presence and each of the factors above.
- Test different models for predicting species presence and select the one that performs best.
- Plot results
\
<br> The goal is to produce a raster layer of the distribution of each species to be used in a future comparative analysis.
\
<br> **References**
- Wydoski, & Whitney, R. R. (2003). Inland fishes of Washington (2nd ed., rev. and expanded.). American Fisheries Society in association with University of Washington Press.
