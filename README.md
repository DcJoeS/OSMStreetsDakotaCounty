# OSMStreetsDakotaCounty
Street Centerlines extracted from the Dakota County database that do not intersect existing OSM streets.
1. Select streets that intersect with an extract of streets from OSM.  Allow for selection within 10 feet to overcome situations where divided streets exist or original streets digitized into OSM may be slightly off.  (The purpose of making this data available at this time is mostly to fill in missing streets.  The selection may show streets that doesn't share alignment between Dakota County data and OSM.)
2. The selection is inverted and limited to local roads
3. Exported to a shapefile with appropriate keys and values for OSM.  Assumed: Residential, 30mph, asphalt.  This should be proofed with local knowledge, streetview, etc.  Whatever you would normally do to proof data.
4. Using JOSM, I opened the shp and saved it as OSM.

Let me know if anything is wonky.

Happy download and edit.

## Downloads
OSM file - [Street_201702151621_osm.zip] (https://github.com/DcJoeS/OSMStreetsDakotaCounty/blob/master/osm/Street_201702151621_osm.zip)

Shapefile - [Street_201702151621.zip] (https://github.com/DcJoeS/OSMStreetsDakotaCounty/blob/master/shp/Street_201702151621.zip)

## WMS 2016 Aerial Photography - new
Feel free to access Dakota County's 2016 Aerial Photography by adding a WMS to JOSM.  Not sure why it throws errors/warnings because it looks just fine.

 http://gis2.co.dakota.mn.us/arcgis/services/AerialPhotography/2016AirPhotoLeafOff6Inch/ImageServer/WMSServer?request=GetCapabilities&service=WMS


