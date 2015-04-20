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

* Access the entire globe with an accuracy of 120 pixels per degree (~ 1kn per pixel ).
* Zoom, pand and rotate in real-time
* Access two click-and-go gazetteers
	* Golembeck with over 2,000 city location
	* GEBCO with over 3,000 undersea locations
* Seven levels of zoom
* Click-and-go location map
* Overlays with real maps
* Display placards with place names
* Display grid and axis 
* Adjust vertical scale
* And much more

## Issues

* heightmap displays gazetteer locations in wrong position
* NSEW arrow buttons create errors at edge of world
	* Should just continue going seamlessly
* Vertical scale could go even lower
* World location map does not load all 4 images the first time
* Overlay mis-registration at low zoom levels
	* Actual data vs Mercator data issue


## Road Map

* Add shade and shadows
* Permalinks
* Mouse over height map image provides readout of altitude/depth at cursor position
* Gazetteer data to be displayed as points, lines and polygons - not just points


## Change Log

2015-03-29 ~ Theo

* Add Click on location map to go there
* Fixed ( mostly ) altitudes incorrectly calculated 

2015-03-28 ~ Theo

* Folders and files added