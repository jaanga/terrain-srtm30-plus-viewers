SRTM30 Plus to PNG TMS7 Viewer 3D Read Me
===

[png-tms7-viewer-3d]( ./png-tms7-viewer-3d-features/latest/index.html )

## Concept

View the Scripps SRTM 30 Plus data in 3D


The demo is built up from three files:

* png-tms7-viewer-3d.html
	* The container that reads the content file and the menu file
	* Could be built using jQuery or any other UI library
* png-tms7-viewer-3d-menu.md
	* Menu file created using Markdown syntax
* template-png-tms7-viewer-3d.html
	* Standalone file to be loaded within an iframe
	* Loads, contains and process all 3D interaction
	* Completely workable when not in an iframe
	* Enables two-communication with parent when within an iframe
 
## Issues

* Incorrect links in About message
* Navigation > tileX/Y not updating the scene
* NSEW arrow buttons create errors at edge of world
	* Should just continue going seamlessly
* Vertical scale could go even lower
* World location map does not load all 44 images the first time
* Overlay mis-registration at low zoom levels
	* actual data vs Mercator data issue


## Road Map

* Permalinks
* Mouse over height map image provides readout of altitude/depth at cursor position



## Change Log

2015-03-29 ~ Theo

* Add Click on location map to go there
* Fixed ( mostly ) altitudes incorrectly calculated 

2015-03-28 ~ Theo

* Folders and files added