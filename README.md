# sentinel2-kanto2021
Raster tile from Sentinel2 (T54SUE, T54SUF, T54SVE, T54SVF) in late 2021 


# Source data
* Sentinel-2B data (4 scenes, Date and scene ID as follows)  
* Processing level L1C (TOA reflectance with georefereced)
* Data was downlodaded from USGS EarthExplorer  

| 2021-12-03 | 2021-11-28 |
|----------|---------|
| T54SUF | T54SVF |
| T54SUE | T54SVE |

# Processing
Processing was done in QGIS 3.16.6.
True color composite (RGB = B4,B3,B2) with color strech from 0-2000.
XYZ tile was generated by using TileXYZ.

# Tile
https://ubukawa.github.io/sentinel2-kanto2021/kanto2021-sentinel2/{z}/{x}/{y}.png  
minz 6   
maxz 13  
  
Quick view https://ubukawa.github.io/sentinel2-kanto2021/kanto2021-leaflet.html

# Citation
We follow the terms of use of the Sentinel2 data. We need to clearly specify the source.  

**Copernicus Sentinel data (2021, EUROPEAN COMMISSION) downloaded through U.S. Geological Survey EarthExplorer.**  


