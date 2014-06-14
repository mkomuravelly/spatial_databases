shp file   : 

The Esri shapefile, or simply a shapefile, is a popular geospatial vector data format for geographic information system software. 
It is developed and regulated by Esri as a (mostly) open specification for data interoperability among Esri and other GIS
 software products.[1] Shapefiles spatially describe vector features: points, lines, and polygons, representing, for example,
 water wells, rivers, and lakes.
 Each item usually has attributes that describe it, such as name or temperature.
 
 
 OSM file   : 
 
 The OpenStreetMap data model is a powerful yet simple way to represent geographic information. 
 Understanding the data model enables you to interact with OpenStreetMap data in its raw form so that you can manipulate it
 into formats that are more useful for what you're trying to do. You'll want to understand the data model if you are interested in 
 writing a map editor, converting the raw OpenStreetMap data into a format for use in an application, 
 or if any of the existing software tools don't provide functionality that you want.
 
 Geojson   : 
 
 
 GeoJSON is a format for encoding a variety of geographic data structures. 
 A GeoJSON object may represent a geometry, a feature, or a collection of features.
 GeoJSON supports the following geometry types: Point, LineString, Polygon, MultiPoint, MultiLineString, MultiPolygon, 
 and GeometryCollection. Features in GeoJSON contain a geometry object and additional properties, and a feature collection 
 represents a list of features.
 
 GPX        : 
 
GPX, or GPS Exchange Format, is an XML schema designed as a common GPS data format for software applications.
It can be used to describe waypoints, tracks, and routes. The format is open and can be used without the
 need to pay license fees. Its tags store location, elevation, and time and can in this way be used to interchange data
 between GPS devices and software packages. Such computer programs allow users, for example, to view their tracks, project their
 tracks on satellite images or other maps, annotate maps, and tag photographs with the geolocation
 in the Exif metadata.
 
 KML        : 
 
 Keyhole Markup Language (KML) is an XML notation for expressing geographic annotation and visualization within Internet-based, 
 two-dimensional maps and three-dimensional Earth browsers. KML was developed for use with Google Earth, which was originally named
 Keyhole Earth Viewer. It was created by Keyhole, Inc, which was acquired by Google in 2004.
 KML became an international standard of the Open Geospatial Consortium in 2008.[1][2] Google Earth was the first program able to 
 view and graphically edit KML files.
 
 NMEA       : 
 
 NMEA is a standard protocol, used by GPS receivers to transmit data. NMEA 0183 sentences are all ASCII. 
Each sentence begins with a dollar sign ($) and ends with a carriage return linefeed (<CR><LF>). Data is 
comma delimited. All commas must be included as they act as markers. Some GPS do not send some of 
the fields. 


CSV         : 


The CSV ("Comma Separated Value") file format is often used to exchange data between disparate applications.
 The file format, as it is used in Microsoft Excel, has become a pseudo standard throughout the industry,
 even among non-Microsoft platforms.
As is the case with most exchange formats since XML, CSV files have become somewhat of a legacy format.
 New applications that wish to include an export format will generally use XML today (though there may be exceptions). 
 In legacy systems though (pre-XML), CSV files had indeed become a de facto industry standard.
 Just as there are still billions of lines of CoBOL code in use today that need to be maintained, support for a 
legacy standard such as CSV is likely to be required long after it has stopped being implemented in new designs.
 Other projects such as Marble have also started to develop KML support.


QGIS       : 


QGIS uses the OGR library to read and write vector data formats (GRASS vector and PostgreSQL support is supplied by native
 QGIS data provider plugins),including ESRI Shapefiles, MapInfo and Microstation file formats; PostGIS, SpatiaLite,
 Oracle Spatial databases and many more. 
 
 
 GPSBABEL   : 
 
 GPSBabel is a cross-platform, free software to transfer routes, tracks, and waypoint data to and from consumer GPS units, 
 and to convert between over a hundred types of GPS data formats.[1] It has a command-line interface and a graphical interface
 for Windows, OS X, and Linux users.

GPSBabel is part of many Linux distributions including Debian GNU/Linux and Fedora, and also part of the 'fink' system for getting Unix software on Mac OS X.
The vector data can also be loaded in read mode from zip and gzip archives into QGIS. 
