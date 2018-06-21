.. _layers.upload:

Uploading a layer
=================

Vector data (shapefile, kml, geojson) and raster data (GeoTIFF) can be uploaded into GeoNode.

#. Navigate to the GeoNode welcome page.

#. Click the :guilabel:`Layers` link on the top toolbar. This will bring up the Layers menu.

   .. figure:: img/toolbar.png

      *Main toolbar for GeoNode*

   .. figure:: img/layers.png

      *Layers menu*

#. Click :guilabel:`Upload Layers` in the Layers toolbar. This will bring up the upload form

   .. figure:: img/uploadform.png

      *Upload Layers form*

#. Fill out the form.

   * Click on the :guilabel:`Browse...` button. This will bring up a local file dialog. Navigate to your data folder and select all of the four files composing the shapefile (:file:`<filename>.shp`, :file:`<filename>.dbf`, :file:`<filename>.shx`, :file:`<filename>.prj`). Alternatively you could drag and drop the four files in the :guilabel:`Drop files here` area.

   * The upload form should appear like this now:

   .. figure:: img/uploadformfilled.png

      *Files ready for upload*

#. GeoNode has the ability to restrict who can view, edit, and manage layers. On the right side of the page, under :guilabel:`Who can view and download this data?`, select :guilabel:`Any registered user`. This will ensure that anonymous view access is disabled.

#. In the same area, under :guilabel:`Who can edit this data?`, select the :guilabel:`Only the following users or groups` option and type your username. This will ensure that only you are able to edit the data in the layer.

   .. figure:: img/uploadpermissions.png

      *Permissions for new layer*

#. Click :guilabel:`Upload` to upload the data and create a layer. A dialog will display showing the progress of the upload.

   .. figure:: img/uploading.png

      *Upload in progress*

#. Your layer has been uploaded to GeoNode. Now you will be able to access to the its info page (clicking on the :guilabel:`Layer Info` button), access to its metadata edit form (clicking on the :guilabel:`Edit Metadata` button) or to manage the styles for it (clicking on the :guilabel:`Manage Styles` button).

   .. figure:: img/afterupload.png
