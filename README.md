# urp5560_pyt

URP 5560 (GIS Programming and Automation) Assignment 5: a Python toolbox and its shapefile output.

Muhammad Usama Aslam, Iowa State University

`analysis_output_Ankeny.zip` contains:

- `park_provisions.pyt` - Python toolbox with the tool "Open Space Access by Census Block". For a chosen Iowa city it selects the parks from the statewide OpenStreetMap POI polygons, clips them and the public conservation and recreation lands to the city buffer, and measures open space access for every 2010 census block.
- `analysis_output_Ankeny.shp` (with its .shx, .dbf, .prj, .cpg, .sbn, .sbx and .shp.xml files) - the output of the tool for the city of Ankeny: 756 census blocks with the fields `BLK_ACCESS`, `ACC_FRAC` and `SUM_INV_DI`.

The statewide input shapefiles are not included.
