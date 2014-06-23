
FILE EXTENSIONS

shp file :

A shapefile, is a popular geospatial vector data format for geographic information system software. It is developed and regulated by Esri as a open specification for data interoperability among Esri and other GIS software products. Shapefiles spatially describe vector features: points, lines, and polygons, representing, for example, water wells, rivers, and lakes. Each item usually has attributes that describe it, such as name or temperature.

OSM file :

The OpenStreetMap data model is a powerful yet simple way to represent geographic information. Understanding the data model enables you to interact with OpenStreetMap data in its raw form so that you can manipulate it into formats that are more useful.

Geojson :

GeoJSON is a format for encoding a variety of geographic data structures. A GeoJSON object may represent a geometry, a feature, or a collection of features. GeoJSON supports the following geometry types: Point, LineString, Polygon, MultiPoint, MultiLineString, MultiPolygon, and GeometryCollection. Features in GeoJSON contain a geometry object and additional properties, and a feature collection represents a list of features.

GPX :

GPX, or GPS Exchange Format, is an XML schema designed as a common GPS data format for software applications. It can be used to describe waypoints, tracks, and routes. The format is open and can be used without the need to pay license fees. Its tags store location, elevation, and time and can in this way be used to interchange data between GPS devices and software packages.

KML :

Keyhole Markup Language (KML) is an XML notation for expressing geographic annotation and visualization within Internet-based, two-dimensional maps and three-dimensional Earth browsers. KML was developed for use with Google Earth, which was originally named Keyhole Earth Viewer. 
 
NMEA :

NMEA is a standard protocol, used by GPS receivers to transmit data. NMEA 0183 sentences are all ASCII. Each sentence begins with a dollar sign and ends with a carriage return linefeed (). Data is comma delimited. All commas must be included as they act as markers. Some GPS do not send some of the fields.

CSV :

The CSV ("Comma Separated Value") file format is often used to exchange data between disparate applications. The file format, as it is used in Microsoft Excel, has become a pseudo standard throughout the industry, even among non-Microsoft platforms. As is the case with most exchange formats since XML, CSV files have become somewhat of a legacy format.

WKT  :

Well-known text (WKT) is a text markup language for representing vector geometry objects on a map, spatial reference systems of spatial objects and transformations between spatial reference systems.


SOFTWARES


ArcGIS :

ArcGIS is a geographic information system (GIS) for working with maps and geographic information. It is used for creating and using maps, compiling geographic data, analyzing mapped information, sharing and discovering geographic information.

QGIS :

QGIS uses the OGR library to read and write vector data formats (GRASS vector and PostgreSQL support is supplied by native QGIS data provider plugins),including ESRI Shapefiles, MapInfo and Microstation file formats; PostGIS, SpatiaLite, Oracle Spatial databases and many more.

GPSBABEL :

GPSBabel is a cross-platform, free software to transfer routes, tracks, and waypoint data to and from consumer GPS units, and to convert between over a hundred types of GPS data formats.It has a command-line interface and a graphical interface for Windows, OS X, and Linux users.GPSBabel is part of many Linux distributions including Debian GNU/Linux and Fedora, and also part of the 'fink' system for getting Unix software on Mac OS X. The vector data can also be loaded in read mode from zip and gzip archives into QGIS.

GDAL:

GDAL (Geospatial Data Abstraction Library) is a library for reading and writing raster geospatial data formats, and is released under the permissive X/MIT style free software license by the Open Source Geospatial Foundation. As a library, it presents a single abstract data model to the calling application for all supported formats. It may also be built with a variety of useful command-line utilities for data translation and processing.


DEFINITIONS 


POINT:

A Point is a geometry that represents a single location in coordinate space.Point is defined as a zero-dimensional geometry.The boundary of a Point is the empty set.

CURVE:

A Curve is a one-dimensional geometry, usually represented by a sequence of points.Curve is a noninstantiable class.A Curve has the coordinates of its points.It is defined as a one-dimensional geometry.It is simple if it does not pass through the same point twice.A curve is closed if its start point is equal to its endpoint.The boundary of a closed Curve is empty.

LINESTRING:

A LineString is a Curve with linear interpolation between points.It has coordinates of segments, defined by each consecutive pair of points.
It is a Line if it consists of exactly two points and A LineString is a LinearRing if it is both closed and simple.

MULTICURVE:

A MultiCurve is a geometry collection composed of Curve elements.A MultiCurve is simple if and only if all of its elements are simple.


MULTILINESTRINGS:

A MultiLineString is a MultiCurve geometry collection composed of LineString elements.

Surface Polygons:

A Surface is a two-dimensional geometry. It is a noninstantiable class. Its only instantiable subclass is Polygon.A Surface is defined as a two-dimensional geometry.The boundary of a simple Surface is the set of closed curves corresponding to its exterior and interior boundaries.

MULTI POLYGONS:

A MultiPolygon has no two Polygon elements with interiors that intersect.It has no two Polygon elements that cross or that touch at an infinite number of points.It is a MultiSurface object composed of Polygon elements.


RELATIONSHIPS

Touches:

The geometries only touch edges and do not overlap in any way.

Crosses:

The geometries do more than touch, they actually overlap edges.

Within:

One geometry is completely within another (no touching edges).

Overlaps:

The geometries have some points in common. but not all. The overlapping section must be the same kind of shape as the two geometries.so two polygons that touch on a point are not considered to be overlapping.






































