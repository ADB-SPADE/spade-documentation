.. _admin_workshop:

=======================
SPADE Administration
=======================

This section will teach how to manage a deployment of the `GeoNode <http://geonode.org/>`_ software application.
At the end of this section you will master all the GeoNode sections and entities from an administrator perspective.

You will know how to:

1. Use the GeoNode’s Django Administration Panel.
2. Use the console Management Commands for GeoNode.
3. Configure and customize your GeoNode installation.

*Prerequisites*

    Before proceeding with the reading, it is strongly recommended to be sure having clear the following concepts:

    1. GeoNode and Django framework concepts
    2. Good knowledge of Python
    3. Good knowledge of what is a geospatial server and geospatial web services.
    4. Good knowledge of what is metadata and catalog.
    5. Good knowledge of HTML and CSS.

.. toctree::
    :hidden:

    001_admin_panel/index
    002_admin_panel_spade/index
    003_system_architecture/index
    004_admin_mgmt_commands/index
    005_debug_geonode/index
    007_loading_data_into_geonode/index
    008_more_on_security_and_permissions/index

:ref:`admin_panel`
  GeoNode has an administration panel based on the Django admin which can be used to do some database operations. Although most of the operations can and should be done through the normal GeoNode interface, the admin panel provides a quick overview and management tool over the database.

:ref:`admin_panel_spade`
  Some of the objects specific for SPADE (cities, charts, time-enabled rasters, swipable layers & clippable layers) are currently administered using the administration panel.

:ref:`system_architecture`
  Describes SPADE specific aspects of the system architecture and how the machines can be accessed for system administration tasks.

:ref:`admin_mgmt_commands`
    GeoNode comes with administrative commands to help with day to day tasks. This section shows the list of the ones that come from the GeoNode application.

:ref:`debug_geonode`
    There are several mechanisms to debug GeoNode installations, the most common ones are discussed in this section.

:ref:`data`
    This module will walk you through the various options available to load data into your GeoNode from GeoServer, on the command-line or programatically. You can choose from among these techniques depending on what kind of data you have and how you have your GeoNode setup.

:ref:`more_on_security_and_permissions`
    This tutorial will guide you through the steps that can be done in order to restrict the access on your data uploaded to GeoNode.

    First of all it will be shown how a user can be created and what permissions he can have. Secondly we will take a closer look on to layers, maps and documents and the different opportunities you have in order to ban certain users from viewing or editing your data.
