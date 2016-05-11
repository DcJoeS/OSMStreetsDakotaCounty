# OSMStreetsDakotaCounty
Street Centerlines extracted from the Dakota County database that do not intersect existing OSM streets.
1. Select streets that intersect with an extract of streets from OSM.  Allow for selection within 10 feet to overcome situations where divided streets exist or original streets digitized into OSM may be slightly off.  (The purpose of making this data available at this time is mostly to fill in missing streets.  The selection may show streets that doesn't share alignment between Dakota County data and OSM.)
2. The selection is inverted and limited to local roads
3. Exported to a shapefile with appropriate keys and values for OSM.
4. Using JOSM, I opened the shp and saved it as OSM.

Let me know if anything is wonky.

Happy download and edit.

## Downloads
OSM file - [Street_2016005111027_osm.zip] (https://github.com/DcJoeS/OSMStreetsDakotaCounty/blob/master/osm/Street_201605111027_osm.zip)

Shapefile - [Street_2016005111027.zip] (https://github.com/DcJoeS/OSMStreetsDakotaCounty/blob/master/shp/Street_201605111027.zip)

## WMS 2015 Aerial Photography
Feel free to access Dakota County's 2015 Aerial Photography by adding a WMS to JOSM.  Not sure why it throws errors/warnings because it looks just fine.

 http://gis2.co.dakota.mn.us/arcgis/services/AerialPhotography/2015AirPhotoLeafOff6Inch/ImageServer/WMSServer?request=GetCapabilities&service=WMS


