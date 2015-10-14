# QGIS to Leaflet
##This repo will be ready Thursday morning 10.14.2015
We'll take a look at the [LA County data on Locations / Points of Interest](http://egis3.lacounty.gov/dataportal/2014/07/07/locationspoints-of-interest-lms-data/) and see what can be mapped using [Leaflet](http://leafletjs.com/).

Our main goal is to map certain data points from the LMS Data in the cities within LA County with the following:

1. Using QGIS to open vector files or [geodatabases](http://webhelp.esri.com/arcgisserver/9.3/java/index.htm#geodatabases/an_ove-2050156920.htm)
* Identifying the unique values in the fields of the data (EX: Arts and Recreation, Farmers Markets, Fire Stations)
* Styling the fields to highlight certain values using the RULE-BASED Styling (It's kind of like using functions in excel)
* Use a plugin like [OpenLayers](https://plugins.qgis.org/plugins/openlayers_plugin/) to add a base layer like Google Maps or Stamen Maps
* Select features using expressions (functions) and save the selected as geojson files to be loaded on leaflet
2. Load up the python [SimpleHTTPServer](http://www.pythonforbeginners.com/modules-in-python/how-to-use-simplehttpserver/) for local hosting your map
3. Leaflet 101, Webmap basics
4. Upload your map to Github for live hosting!

##What you'll need to install
You'll need the following software ready (If you are having issues, don't worry we'll help you through it):

- [QGIS](http://qgis.org/en/site/) | Free Open Source Geographic Information System
 - Please download and install, its about 300 mb.
 - Windows Users: Installation should be just downloading the install file.
 - Mac Users: Installation requires additional software to make QGIS work. [Instructions for additional software](http://maps.cga.harvard.edu/qgis/wkshop/mac.php)
- Text Editor | Software to write code like HTML, CSS and Javascript
 - [Sublime](http://www.sublimetext.com/)
 - [Brackets](http://brackets.io/)
 - [Atom](https://atom.io/)
- [Python](https://www.python.org/) | It's a programming language that has valuable tools and commands to help you build your maps like locally hosting your map on your computer with a command called <code>SimpleHTTPServer</code>
 - Windows Users: Download Python 2.7.10 ([Direct Link](https://www.python.org/downloads/)). During the install, in the setup labeled "Customize Python", scroll down to the feature "Add python.exe to Path" and select "Will be installed on local hard drive." This will allow you to call python commands when you are using your command terminal.
 - Mac Users : Python is already installed and you can call python when in terminal.
-Github | Is a coding repository service that manages your code and data
 -[Sign-up for a free account!](https://github.com/), This will allow you to fork (essentially copy) this repository to your computer and you can push your code and map to your account online to be hosted live!
 -Windows Users: Install [GitHub Desktop](https://desktop.github.com/). 
 -Mac Users: Install [GitHub Desktop](https://desktop.github.com/)

## Step 1 - Load, style your spatial data in QGIS

## Step 2 - Export your data into geojson

## Step 3 - Get a basic map in Leaflet

## Step 4 - Style your geojson file

## Step 5 - Add interactivity with tooltip (popup)

## Step 6 - Push your own map to github.
