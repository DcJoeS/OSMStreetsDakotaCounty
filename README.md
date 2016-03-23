# OSMStreetsDakotaCounty
Street Centerlines extracted from the Dakota County database that do not intersect existing OSM streets.  Select streets that intersect with an extract of streets from OSM.  Allow for selection within 5 meters to overcome situations where divided streets exist or original streets digitized into OSM may be slightly off.  (The purpose of making this data available at this time is to fill in missing streets.)  The selection is inverted and limited to local roads then exported to a shapefile with appropriate keys and values for OSM.  Using JOSM I opened the shp and saved it as OSM.

Happy download and edit.

## Downloads
OSM file - [Street_201603211813_osm.zip] (http://github.com/DcjoeS/OSMStreetsDakotaCounty/tree/master/osm/Street_201603211813_osm.zip)

Shapefile - [Street_201603211813.zip] (http://github.com/DcjoeS/OSMStreetsDakotaCounty/tree/master/shp/Street_201603211813_osm.zip)

## WMS 2015 Aerial Photography
Feel free to access Dakota County's 2015 Aerial Photography by adding a WMS to JOSM.  Not sure why it throws errors/warnings because it looks just fine.

 http://gis2.co.dakota.mn.us/arcgis/services/AerialPhotography/2015AirPhotoLeafOff6Inch/ImageServer/WMSServer?request=GetCapabilities&service=WMS


