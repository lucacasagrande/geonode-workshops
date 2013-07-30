==================
Geonode Quickstart
==================

Open Source Geospatial Content Management System

GeoNode is a web-based application and platform for developing geospatial information systems (GIS) and for deploying spatial data infrastructures (SDI). 

In this Quickstart guide you will learn the following:

    #. to register a new account to get started
    #. add a new layer
    #. create a map using your new layer
    #. share your map with others
    
To start GeoNode you have to choose *Geospatial* => *Browser Clients* => *Start GeoNode* and the GeoNode webpage will automatically
be opened at http://localhost:8000/ (I assume!). The page will look like shown in the image below.

    .. figure:: img/start_page.png
    .. todo:: add this image

1. Register a new account
----------------------

From the interface shown above, one can view and modify existing spatial layers and maps, as well as find information on other GeoNode users. But, without being logged in, you are limited to read-only access of public layers. In order to create a map and add layers to it, you have to have create an account first.

#. From any page in the web interface, you will see a *Sign in* link. Click that link, and in the dialog that displays, click the *Register now* link.

   .. figure:: ../accounts/img/signin.png


#. On the next page, fill out the form. Enter a user name and password in the fields. Also, enter your email address for verification.

   .. figure:: ../accounts/img/signup.png


#. You will be returned to the welcome page. An email will be sent confirming that you have signed up. While you are now logged in, you will need to confirm your account. Navigate to the link that was sent in the email.

   .. figure:: ../accounts/img/confirm.png
   

#. By clicking *Confirm* you will be returned to the homepage. Now you've registered an account, you are able to add layers to it as well as create maps and share those with other users. 


2. Add a new layer
------------------

Layers are a published resource representing a raster or vector spatial data source. Layers also can be associated with metadata, ratings, and comments.

#. To add a layer to your account, navigate to the welcome page. There the following toolbar can be seen:

    .. figure:: ../layers/img/toolbar.png

#. By clicking the *Layers* link you will be brought to the *Layers* menu where a new subtoolbar can be seen. This toolbar allows you to *Explore*, *Search* and *Upload* layers. 

   .. figure:: ../layers/img/layerstoolbar.png

#. Now click *Upload Layers* and you'll see the upload form.

   .. figure:: ../layers/img/uploadform.png

#. Fill out this form, according to the following steps:

 * Leave the title blank for now (it will be autopopulated based on the file name).
 * Next to the Data field, click the *Browse* button. This will bring up a local file dialog. Navigate to your data folder and select   	the file you want to upload (.shp).
 *  A few new options will appear once this shapefile is selected. Next to the DBF field, click the *Browse* button. This will bring up    		the same local file dialog. Select the a .dbf file.
 * Repeat the same process for the SHX and PRJ fields.
 * Leave the rest of the fields blank.

#. GeoNode has the ability to restrict who can view, edit, and manage layers. On the right side of the page, under *Who can view and download this data*, select *Any registered user*. This will ensure that anonymous view access is disabled.

#. In the same area, under *Who can edit this data*, select your username. This will ensure that only you are able to edit the data in the layer.

#. Click *Upload* to upload the data and create a layer.


3. Create a new map
-------------------

The next step for you is to create a map and to add the newly created layer to this map.

#. Click the *Maps* link on the top toolbar. This will bring up the list of maps. 

   .. figure:: ../intro/img/maps.png


#. Currently, there aren't any maps here. To add one click the *Create a New Map* button and a map composition interface will display.

   .. figure:: ../maps/img/createmap.png


In this interface there is a toolbar, layer list, and map window. The map window contains the MapQuest OpenStreetMap layer by default. There are other service layers available here as well:  Blue Marble, Bing Aerial With Labels, MapQuest, and OpenStreetMap.

#. Click on the *New Layers* button and select *Add Layers*. 

   .. figure:: ../maps/img/addlayerslink.png


#. Now you should be able to see all the availabel layers. In your case, this should only be the one you've added before.
#. Select all of the San Andreas layers by clicking the top entry and Shift-clicking the bottom one. Click *Add Layers* to add them all to the map.

   .. figure:: ../maps/img/addlayersselect.png

   .. note:: This selection includes not only the two layers uploaded in the previous section, but also the layers that were already hosted on GeoNode at the beginning of the workshop.

#. The layers will be added to the map. Click *Done* (right next to *Add Layers* at the bottom) to return to the main layers list.

   .. figure:: ../maps/img/layersadded.png
   

#. To save the map click on the *Map* button in the toolbar, and select *Save Map*.

   .. figure:: ../maps/img/savemaplink.png


#. Enter a title and abstract for your map.

   .. figure:: ../maps/img/savemapdialog.png


#. Click *Save*. Notice that the link on the top right of the page changed to reflect the map's name.

   .. figure:: ../maps/img/mapname.png


   This link contains a permalink to your map. If you open this link in a new window, your map will appear exactly as it was saved.


4. Share your map
-----------------

Now let's finish our map.

#. Check the box next to the *highway* layer to activate it.  If it is not below the *POI* layer in the list, click and drag it down.

   .. figure:: ../maps/img/mapcomposition.png


#. Make any final adjustments to the map composition as desired, including zoom and pan settings.

#. Click the *Map* button in the toolbar, and then click *Publish Map*.

   .. figure:: ../maps/img/publishmaplink.png


#. The title and abstract as previously created should still be there. Make any adjustments as necessary, and click *Save*.

#. A new dialog will appear with instructions on how to embed this map in a webpage, including a code snippet. You can adjust the parameters as necessary.

   .. figure:: ../maps/img/publishmap.png


Your map can now be shared!

To be continued
---------------

Now you've gotten a quick insight in the possibilities of GeoNode. To learn more about GeoNode and its features, visit our webpage www.geonode.org. 
To install GeoNode on your own server, follow the guidelines from http://docs.geonode.org/en/latest/intro/install.html (quickstart) or http://docs.geonode.org/en/latest/deploy/install.html (complete installation). 
In order to get started with GeoNode our documentation might be useful. This can be found http://docs.geonode.org/en/latest/index.html. 

If you need help or want to get some information about a specific topic please don't hasitate to ask us! You can do this through the #geonode IRC channel using http://webchat.freenode.net/
or by asking your question in our google group https://groups.google.com/forum/#!forum/geonode-users !

    .. todo:: links!!!
    
    
