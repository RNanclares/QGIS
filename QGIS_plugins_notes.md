QGIS Phyton Plugins
===================

*CC-BY-SA 2016 - M. Sevilla-Callejo*

<!-- toc -->

- [QGIS Phyton Plugins](#qgis-phyton-plugins)
	- [Links](#links)
	- [Must have Plug-ins](#must-have-plug-ins)
		- [mmqgis](#mmqgis)
		- [OpenLayers Plugin](#openlayers-plugin)
		- [Table Manager](#table-manager)
		- [Numerical Vertex Edit](#numerical-vertex-edit)
		- [Profile tool](#profile-tool)
		- [QSpatiaLite](#qspatialite)
		- [QuickOSM](#quickosm)
		- [Qgis2threejs](#qgis2threejs)
		- [qgis2web](#qgis2web)
		- [XyTools](#xytools)
		- [QConsolidate](#qconsolidate)
		- [qgis2leaf](#qgis2leaf)
		- [Layer Board](#layer-board)
	- [Interesting Plug-ins](#interesting-plug-ins)
		- [QSphere](#qsphere)
		- [Layer Combinations](#layer-combinations)
		- [Rectangles Ovals Digitizing](#rectangles-ovals-digitizing)
		- [Affine Transformations](#affine-transformations)
		- [Temporal/Spectral Profile Tool](#temporalspectral-profile-tool)
		- [QuickMapServices](#quickmapservices)
	- [Testing Plug-ins (to review)](#testing-plug-ins-to-review)
		- [Group Stats](#group-stats)
		- [AutoTrace Plugin (within version 2.14)](#autotrace-plugin-within-version-214)
		- [Descarga de imágenes PNOA ¿?](#descarga-de-imágenes-pnoa)
	- [QGIS alternative repositories (TO REVIEW)](#qgis-alternative-repositories-to-review)
	- [How to manually install a plugin (TO REVIEW)](#how-to-manually-install-a-plugin-to-review)

<!-- tocstop -->

---

## Links

* [QGIS plugins webpage](http://plugins.qgis.org/plugins/)
* [Featured plugins](http://plugins.qgis.org/plugins/featured/)
* [Popular plugins](http://plugins.qgis.org/plugins/popular/)

Must have Plug-ins
------------------

### mmqgis
MMQGIS is a set of plugins for manipulating vector map layers in Quantum GIS: CSV input/output/join, Geocoding, Geometry Conversion, Buffering, Hub Analysis, Simplification Column Modification, Color Ramps, and Simple Animation.

### OpenLayers Plugin
OpenStreetMap, Google Maps, Bing Maps, MapQuest layers and more
[GitHub - sourcepole/qgis-openlayers-plugin: Openlayers plugin for QGIS](https://github.com/sourcepole/qgis-openlayers-plugin)

### Table Manager
Manages the attribute table structure (rename, move, clone, delete...)

### Numerical Vertex Edit
Allows to edit a vertex in a numeric way by clicking on it.

### Profile tool
Plots terrain profile

### QSpatiaLite
Manage your SpatiaLite databases within QGis

### QuickOSM
QuickOSM allows you to work quickly with OSM datas in QGIS thanks to Overpass API.

### Qgis2threejs
3D visualization powered by WebGL technology and three.js JavaScript library

### qgis2web
Export to an OpenLayers 3/Leaflet webmap (merge of qgis-ol3 and qgis2leaf). -- PROBAR -- qgis2leaf es más completo

### XyTools
Tools for managing tabular data with x y columns. It can open spreadsheet files (Libre/OpenOffice, Excel) as point layers and save attribute tables as Excel file

You need to install dependecies (Linux):

	sudo apt-get install python-xlwt python-xlrd

### QConsolidate
Experimental (May 05-2015)
QConsolidate is a QGIS plugin used to consolidate all project layers into single user defined folder. This can be useful is you decide to share project with many layers from different directories with other person.
[GitHub page](https://github.com/alexbruy/qconsolidate)

### qgis2leaf
Export your QGIS project to a leaflet based webmap.

### Layer Board
View and edit vector and raster properties for the project layers in a table
This plugin helps to see and modify properties for vector and raster layers. It shows the layers in a table sheet, and the user can directly modify some properties such as layer name, title, abstract, minimum and maximum scales. Some actions can be performed on multiple layers at once, such as modifying spatial reference system and scale based visibility. The layers information can be exported to Comma Separated Values (CSV).


Interesting Plug-ins
--------------------

### QSphere
Tools for create INSPIRE and ISO 19139 metadata

### Layer Combinations
Store and restore layer visibilities, foldings and zooms in "combinations". The visibilites can then be dynamically assigned to composer maps.

### Rectangles Ovals Digitizing
Helps to create Rectangles,Circles and ovals

### Affine Transformations
Apply affine transformations to selected geometries.

### Temporal/Spectral Profile Tool
Plots profile from raster bands. Based on Profile Tool.
A QGIS plugin for interactive plotting of temporal or spectral information stored in multi-band rasters. Based on Profile tool plugin.

### QuickMapServices
Convenient list of basemaps. Easy to add as a layer, easy to create new basemaps and edit. Please leave feedback in issues and contribute new services!


Testing Plug-ins (to review)
----------------------------

### Group Stats
Stats and analysis for vector layers data

### AutoTrace Plugin (within version 2.14)
An editing tool for QGIS that allows users to 'trace' new feature geometry based on existing features

### Descarga de imágenes PNOA ¿?
[ver enlace](http://www.euwesttrail.net/PNOA/ortoPNOAhelp.html)


QGIS alternative repositories (TO REVIEW)
-----------------------------------------

[3rd party repositories button was discouraged (ver. > 1.8.0)](http://gis.stackexchange.com/questions/31490/add-3rd-party-repositories-button-not-in-version-1-8-0-lisboa)


* [GIS-Lab Repository](http://gis-lab.info/programs/qgis/qgis-repo.xml)
* [Sourcepole Repository](http://build.sourcepole.ch/qgis/plugins.xml)
* [Faunalia Repository](http://www.faunalia.it/qgis/plugins.xml)

How to manually install a plugin (TO REVIEW)
--------------------------------------------

Download the plugin directly from the repository url using your browser.  http://pyqgis.org/

Unzip the file. Copy the folder(usually one directory down the extracted folder) to your python plugins directory. In windows, this would be C:\Program Files\Quantum GIS Wroclaw\apps\qgis\python\plugins

Restart QGIS and now you can see this plugin installed. Just enable this plugin in the Plugin Manager.
