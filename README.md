# tiles-to-tiff
# This is a Fork of jimutt's tiles-to-tiff for retrieving the 2021 Orthofoto of the City of Vienna in 15cm² resolution
Python script for converting XYZ raster tiles for WMTS to a georeferenced TIFF image. 

I adapted a couple of lines in order to retrieve the Orthofoto of the City of Vienna for a Machine Learning project. 
The focus is classifying different building-types (e.g. Blocklike-Buildings, Single-Family Homes, Offices, etc.) and detecting cars. 

Jimutt originally wrote it for this tutorial: https://dev.to/jimutt/generate-merged-geotiff-imagery-from-web-maps-xyz-tile-servers-with-python-4d13

## Prerequisites:
- GDAL
- Empty "output" and "temp" folders in project directory. 

## Usage:
- Modify configuration in `tiles_to_tiff.py` according to personal preferences.
- Run script with `$ python tiles_to_tiff.py`

For more information see the accompanying dev.to post. 
