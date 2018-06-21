.. _terminology:

============================
Terminology
============================

* **Features** – geographical attributes on a map represented as points, lines or polygons (areas). This geo-referenced information is associated with one or more attributes.

* **Attribute** – Descriptive data often associated to specific features through geographic information contained in the attribute. For example, an attribute can contain information on the estimated population of a country, where the name of the attribute could be shortened POPEST for easy recognition of what the values of the attribute actually represents.

* **Data values** – the data of a specific attribute e.g. representing the number of an estimated population or the name of a city.

* **Attribute table** – table displaying all the attributes of a specific feature and their associated values.

* **Vector Layer** – data layer representing points, lines and polygons on a map.

* **Shapefile** – file format used by ADB-SPADE for uploading a vector layer. It is a digital vector storage format for storing geometric location and associated attribute information, including the four file formats:

  * **.shp** – shape format; the feature geometry
  * **.shx** – shape index format; a positional index of the feature geometry to allow seeking forwards and backwards quickly
  * **.dbf** – attribute format; columnar attributes for each shape
  * **.prj** - projection format; the coordinate system and projection information, a plain text file describing the projection of the data

* **Raster Layer** – data layer comprised of either digital aerial photographs, imagery from satellites, digital pictures, or even scanned maps. The layer consists of pixels organized into a grid where each cell contains a value representing information (such as e.g. temperature).

* **GeoTIFF** – file format used by ADB-SPADE to upload a raster layer. It is a public domain metadata standard that allows additional geo-referenced information to be embedded within a TIFF file. The additional information includes map projection, coordinate systems, ellipsoids, datum, and other information necessary to establish the exact spatial reference for the file.

* **Style a layer** – to modify the appearance of a layer by using less advanced features (such as symbols and colors) and more advanced features (such as setting rules for conditions and scales) to visualize certain data attributes.

* **SLD file** - GIS file created in the Styled Layer Descriptor format, an XML format used for specifying the display of map layers; can describe both raster and vector data and may include colors, labels, fonts, legend specifications, and other information. SLD files are used by a protocol called the Web Map Service (WMS).

.. toctree::
    :hidden:
