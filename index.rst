.. _mainindex:

==============================
SPADE Documentation
==============================

Welcome to the SPADE Documentation.
The Documentation is divided in four main sections:

:ref:`spade_overview`
  This section guides the user to an overview of SPADE and its main components.

  At the end of this section you will have a clear view of what SPADE is and can do. You will be able also to use the SPADE main functionalities and understand some of the basic concepts of the system infrastructure.

:ref:`spade_map_viewer`
  In this section, you will find detailed information about the SPADE Map Viewer and its components.

:ref:`data_administration`
  This section describes how to use the GeoNode going in depth into what we can do with software application.
  At the end of this section you will master all the GeoNode sections and entities from a user perspective.

  You will know how to:

  1. Manage users accounts and how to modify them.
  2. Use and manage the different GeoNode basic resouces.
  3. Use the GeoNode searching tools to find your resources.
  4. Manage Layers and Maps, update the styles and publish them.
  5. Load datasets into GeoNode and keep them synchronized with GeoServer.

  *Prerequisites*
      Before proceeding with the reading, it is strongly recommended to be sure having clear the following concepts:

      1. GeoNode and Django framework basic concepts
      2. What is Python
      3. What is a geospatial server and a basic knowledge of the geospatial web services.
      4. What is a metadata and a catalog.
      5. What is a map and a legend.

:ref:`admin_workshop`
  This section describes how to manage a deployment of the `GeoNode <http://geonode.org/>`_ software application.
  At the end of this section you will master all the GeoNode sections and entities from an administrator perspective.

  You will know how to:

  1. Use the GeoNode's Django Administration Panel.
  2. Use the console Management Commands for GeoNode.
  3. Configure and customize your GeoNode installation.

  *Prerequisites*
      Before proceeding with the reading, it is strongly recommended to be sure having clear the following concepts:

      1. GeoNode and Django framework concepts
      2. Good knowledge of Python
      3. Good knowledge of what is a geospatial server and geospatial web services.
      4. Good knowledge of what is metadata and catalog.
      5. Good knowledge of HTML and CSS.


.. note::
  SPADE is a customized version of the `GeoNode Open Source Geospatial Content Management System  <https://geonode.org>`_. This documentation is based on the `GeoNode Training Documentation Portal <https://training.geonode.geo-solutions.it>`_ (`source <https://github.com/geosolutions-it/doc-geonode/>`_).
  As a result, the name GeoNode will be used when generic functions are described. In sections that focus on SPADE specific functionality, the  name SPADE will be used.

License Information
-------------------

Documentation
.............

Documentation is released under a :term:`Creative Commons` license with the following conditions.

You are free to Share (to copy, distribute and transmit) and to Remix (to adapt) the documentation under the following conditions:

- Attribution. You must attribute the documentation to the author.

- Share Alike. If you alter, transform, or build upon this work, you may distribute the resulting work only under the same or similar license to this one.

With the understanding that:

- Any of the above conditions can be waived if you get permission from the copyright holder.

- Public Domain. Where the work or any of its elements is in the public domain under applicable law, that status is in no way affected by the license.

Other Rights. In no way are any of the following rights affected by the license:

- Your fair dealing or fair use rights, or other applicable copyright exceptions and limitations;

- The author's moral rights;

- Rights other persons may have either in the work itself or in how the work is used, such as publicity or privacy rights.

Notice: For any reuse or distribution, you must make clear to others the license terms of this work. The best way to do this is with a link to this web page.

You may obtain a copy of the License at `Creative Commons Attribution-ShareAlike 3.0 Unported License <http://creativecommons.org/licenses/by-sa/3.0/>`_

The document is written in reStructuredText format for consistency and portability.

Author Information
..................

This documentation was written by Royal HaskoningDHV, based on the `GeoNode Training Documentation Portal <https://training.geonode.geo-solutions.it>`_ written by GeoSolutions.

The layout for the reStructuredText based documentation is based on the work done by the `GeoNode <http://geonode.org/>`_ project and the `Sphinx <http://sphinx.pocoo.org/>`_ framework.

.. glossary::

   Creative Commons
      `Creative Commons Attribution-ShareAlike 3.0 Unported License <http://creativecommons.org/licenses/by-sa/3.0/>`_
      Creative Commons (CC) is a non-profit organization devoted to
      expanding the range of creative works available for others to build
      upon legally and to share. The organization has released several
      copyright-licenses known as Creative Commons licenses free of charge
      to the public. These licenses allow creators to communicate which
      rights they reserve, and which rights they waive for the benefit of
      recipients or other creators. An easy-to-understand one-page
      explanation of rights, with associated visual symbols, explains the
      specifics of each Creative Commons license. Creative Commons licenses
      do not replace copyright, but are based upon it. They replace
      individual negotiations for specific rights between copyright owne
      (licensor) and licensee, which are necessary under an "all rights
      reserved" copyright management, with a "some rights reserved"
      management employing standardized licenses for re-use cases where no
      commercial compensation is sought by the copyright owner. The result
      is an agile, low-overhead and low-cost copyright-management regime,
      profiting both copyright owners and licensees.

.. toctree::
    :hidden:

    001_spade_overview/index
    002_spade_client/index
    003_data_administration/index
    004_system_administration/index
