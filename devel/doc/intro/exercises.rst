.. component_exercises:

Exercises
=========

Components and Services
-----------------------

Hint, if ``bash-completion`` is installed, try <TAB><TAB> to get completions.

#. start/stop services::

    sudo service apache2
    sudo service apache2 reload
    sudo service tomcat7
    sudo service postgresql

#. basic psql interactions ::

    sudo su - postgres
    psql
    help
    \?
    \l
    \c geonode
    \ds
    \dS layers_layer

OGC Standards
-------------

WMS
...

#. Use the layer preview functionality in GeoServer to bring up a web map.
#. Copy a the URL for the image in the map.
#. Alter URL parameters for the request.
#. Use *curl* to get the capabilities document::

    curl 'http://localhost/geoserver/wms?request=getcapabilities'
  

