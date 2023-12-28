Data is satellite view of a country near Nantes (France).
We create Geotiff from CAD software by using Open Street Map (OSM).
And we convert Geotiff with GDAL command (https://www.cogeo.org/) : gdal_translate input.tif output.tif -of COG -co COMPRESS=LZW.