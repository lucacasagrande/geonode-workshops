Geonode Quickstart
==================

Open Source Geospatial Content Management System

GeoNode is a web-based application and platform for developing geospatial information systems (GIS) and for deploying spatial data infrastructures (SDI). 

In this Quickstart guide you will learn the following:

    #. to register a new account to get started
    #. add a new layer
    #. create a map using your new layer
    #. share your map with others

1. To register a new account
----------------------------

#. If you open the GeoNode website you will see this page.

.. image:: image/start_page.png

#. From this interface, one can view and modify existing spatial layers and maps, as well as find information on other GeoNode users. But, without being logged in, you are limited to read-only access of public layers. In order to create a map and add layers to it, you have to have create an account first.

#. From any page in the web interface, you will see a *Sign in* link. Click that link, and in the dialog that displays, click the *Register now* link.

   .. figure:: img/signin.png

      *Sign in screen*

#. On the next page, fill out the form. Enter a user name and password in the fields. Also, enter your email address for verification.

   .. figure:: img/signup.png

      *Registering for a new account*

#. You will be returned to the welcome page. An email will be sent confirming that you have signed up. While you are now logged in, you will need to confirm your account. Navigate to the link that was sent in the email.

   .. figure:: img/confirm.png

      *Confirming your email address*

#. By clicking *Confirm* you will be returned to the homepage. Now you've registered an account, you are able to add layers to it as well as create maps and share those with other users. 


2. Add a new layer
------------------

Layers are a published resource representing a raster or vector spatial data source. Layers also can be associated with metadata, ratings, and comments.

#. To add a layer to your account, navigate to the welcome page. There the following toolbar can be seen:

.. image:: image/example.png

#. By clicking the *Layers* link you will be brought to the *Layers* menu. This menu allows you to *Explore*, *Search* and *Upload* layers. 

..image:: image/example.png

#. Click *Upload Layers* and you'll see the upload form.

..image:: image/example.png

#. Fill out this form, according (!!)to the following steps:

    #. Leave the title blank for now (it will be autopopulated based on the file name).
    #. Next to the Data field, click the *Browse* button. This will bring up a local file dialog. Navigate to your data folder and select   	the file you want to upload (.shp).
    #.  A few new options will appear once this shapefile is selected. Next to the DBF field, click the *Browse* button. This will bring up    		the same local file dialog. Select the a .dbf file.
    #. Repeat the same process for the SHX and PRJ fields.
    #. Leave the rest of the fields blank.

#. GeoNode has the ability to restrict who can view, edit, and manage layers. On the right side of the page, under *Who can view and download this data*, select *Any registered user*. This will ensure that anonymous view access is disabled.

#. In the same area, under *Who can edit this data*, select your username. This will ensure that only you are able to edit the data in the layer.

#. Click *Upload* to upload the data and create a layer. A dialog will display showing the progress of the upload.
    
..image:: image/example.png

Your layer has been uploaded to GeoNode.


3. Create a new map
-------------------

The next step is to create a map and to add the newly created layer to this map.

#. Click the :guilabel:`Maps` link on the top toolbar. This will bring up the list of maps. 

   .. figure:: ../intro/img/maps.png

      *Maps page*

#. Currently, there aren't any maps here. To add one click the :guilabel:`Create a New Map` button.

#. A map composition interface will display. 

   .. figure:: img/createmap.png

      *Create maps interface*

In this interface there is a toolbar, layer list, and map window. The map window contains the MapQuest OpenStreetMap layer by default. There are other service layers available here as well:  Blue Marble, Bing Aerial With Labels, MapQuest, and OpenStreetMap.

#. Click on the *New Layers* button and select *Add Layers*. 

   .. figure:: img/addlayerslink.png

      *Add layers link*

#. Now you should be able to see all the availabel layers. In your case, this should only be the one you've added before.
#. Select all of the San Andreas layers by clicking the top entry and Shift-clicking the bottom one. Click :guilabel:`Add Layers` to add them all to the map.

   .. figure:: img/addlayersselect.png

      *Selecting layers*

   .. note:: This selection includes not only the two layers uploaded in the previous section, but also the layers that were already hosted on GeoNode at the beginning of the workshop.

#. The layers will be added to the map. Click :guilabel:`Done` (right next to :guilabel:`Add Layers` at the bottom) to return to the main layers list.

   .. figure:: img/layersadded.png

      *Layers added to the map*

Saving the map
--------------

#. While we still have some work to do on our map, let's save it so that we can come back to it later. Click on the :guilabel:`Map` button in the toolbar, and select :guilabel:`Save Map`.

   .. figure:: img/savemaplink.png

      *Save map link*

#. Enter a title and abstract for your map.

   .. figure:: img/savemapdialog.png

      *Save map dialog*

#. Click :guilabel:`Save`. Notice that the link on the top right of the page changed to reflect the map's name.

   .. figure:: img/mapname.png

      *Saved map name*

   This link contains a permalink to your map. If you open this link in a new window, your map will appear exactly as it was saved.



Share your map with others
--------------------------

Share your map
==============

Now let's finish our map.

#. Check the box next to the :guilabel:`highway` layer to activate it.  If it is not below the :guilabel:`POI` layer in the list, click and drag it down.

   .. figure:: img/mapcomposition.png

      *Adjusting map composition*

#. Make any final adjustments to the map composition as desired, including zoom and pan settings.

#. Click the :guilabel:`Map` button in the toolbar, and then click :guilabel:`Publish Map`.

   .. figure:: img/publishmaplink.png

      *Publish map link*

#. The title and abstract as previously created should still be there. Make any adjustments as necessary, and click :guilabel:`Save`.

#. A new dialog will appear with instructions on how to embed this map in a webpage, including a code snippet. You can adjust the parameters as necessary.

   .. figure:: img/publishmap.png

      *Map publishing options*

Your map can now be shared!

