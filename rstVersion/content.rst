============
osm @ spline
============

about
-----

This is the OSM project at SPLINE_. We are wokring at free software around the OpenStreetMap project. In the future we plan to set up a tiles mirror in order to provide a faster mapreading experience in middle europe.

.. _SPLINE: http://www.spline.de

current projects
----------------

* reimplementation_ of the osm-xapi_
* openlayers experiments_
* tile server written in node (github_)
* planet file mirror @ ftp.spline.de_

.. _reimplementation: http://github.com/osm-spline/xappy.js
.. _osm-xapi: http://wiki.openstreetmap.org/wiki/Xapi
.. _experiments: http://map.osm.spline.de/
.. _github: https://github.com/booo/node_tile
.. _ftp.spline.de: http://ftp.spline.de/mirrors/openstreetmap/

contact
-------

* mailinglist_
* irc_ on freenode #spline

.. _mailinglist: mailto:osm@lists.spline.de
.. _irc: irc://irc.freenode.net/#spline

server infrastructure
---------------------

* V-Server-Hosts
  * promm.spline.de (AMD Opteron 4x2.4Gh with 10 GB Memory)
* V-Servers
  * www.osm.spline.de (webspace, runs xapi instances)
  * databases (postgres)
    * xapi_{berlin, germany, europe, world, testing, petra [#]_}
    * routing [#]_

.. [#] petra contains predefined data which is useful for testing complex sql queries.
.. [#] Routing contains routing data for berlin based on pgrouting.
