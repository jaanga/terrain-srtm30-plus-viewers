Jaanga Terrain SRTM30 Plus PNG TMS7 Viewer 3D unFlatland Read Me
===

<span style=display:none; >[View as web page]( http://jaanga.github.io/terrain-srtm30-plus-viewers/terrain-srtm30-plus-viewers.html#./png-tms7-viewer-3d-unflatland-features/readme.md# "view the files as a web app." ) <input value="<< You are here" size=15 style="font:bold 11pt monospace;border-width:0;" ></span>  

Latest release: [Jaanga Terrain SRTM30 Plus PNG TMS7 Viewer 3D unFlatland]( http://jaanga.github.io/terrain-srtm30-plus-viewers/png-tms7-viewer-3d-unflatland-features/latest/index.html )  
[Source code on GitHub]( https://github.com/jaanga/terrain-srtm30-plus-viewers/tree/gh-pages/png-tms7-viewer-3d-unflatland-features/ )  
[FAQ]( http://jaanga.github.io/terrain-r2/terrain.html#faq.md# )

Want a new feature? Have an issue? Send a message to jaanga [at] googlegroups [dot] com

## Concept

View the Scripps SRTM 30 Plus data in 3D

A fully interactive 3D data viewer for SRTM30 Plus data files created by the <a href=http://topex.ucsd.edu/WWW_html/srtm30_plus.html  target="_blank" >Satellite Geodesy research group at Scripps Institution of Oceanography, University of California San Diego</a> 


## Features

* Access the entire globe with an accuracy of 120 pixels per degree (~1km per pixel ).
* Zoom, pan and rotate the display in real-time
* Navigate between tiles using
	* Latitude and longitude
	* TMS X and Y tiles
	* Clicking on arrow icons
* Access two click-and-go gazetteers
	* Golembeck with over 2,000 city location
	* GEBCO with over 3,000 undersea locations
* Seven levels of zoom
* Click-and-go location map
* Click on map to display heads-up placard with latitude, longitude and elevation
* 14 Map Overlays including 
	* Real maps
	* Color by normalized height
	* Wireframe
	* Source height map
* Display placards with Gazetteer place names and indicated altitude
* Display grid and axis 
* Display edges of 3D faces in meshes
* Adjust vertical scale
* Create permalink button
* Open and view local height maps
* And much more

## Issues

* Code needs a clean-up and functions put into a logical arrangement
* World location map does not load all 4 images the first time
* Overlay mis-registration at low zoom levels
	* Actual data vs Mercator data issue


## Road Map

* Add artifact clean-up algorithms

* Mobile enable
* Zoom extents
* Navigate between tiles using cursor keys
* Add first person camera
* Add shade and shadows toggle
* Add Three.js color look up table
* Display placard at permaink lat/lon
* Mouse over height map image provides readout of altitude/depth and lat/lon at cursor position
* Gazetteer data to be displayed as points, lines and polygons - not just points


## Change Log

2015-04-29 ~ Theo

Dealt with
* NSEW arrow buttons create errors at edge of world
	* Should just continue going seamlessly

2015-04-28 Theo

* Add vertex color by normalized height
* Map overlay extracted into stand alone JavaScript file
Dealt with
* Vertical scale could go even lower
* heightmap displays gazetteer locations in wrong position

2015-04-25 ~ Theo

* Fix terrain not zooming issue

2015-03-29 ~ Theo

* Add Click on location map to go there
* Fixed ( mostly ) altitudes incorrectly calculated 

2015-03-28 ~ Theo

* Folders and files added