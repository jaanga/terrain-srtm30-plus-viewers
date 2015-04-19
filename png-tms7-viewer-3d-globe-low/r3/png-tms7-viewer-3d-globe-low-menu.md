[Jaanga]( ../../../index.html ) &raquo; [Terrain]( ../terrain-r2/terrain.html ) &raquo; [SRTM30 Plus]( ../../terrain-srtm30-plus-viewers.html ) &raquo;
[3D Globe LowRes R3]( png-tms7-viewer-3d-globe-low.html "View SRTM data prepared by the Scripps Institution of Oceanography at UCSD" )
===
Use your pointing device to zoom, pan and rotate the globe.

[Medium Resolution]( http://jaanga.github.io/terrain-srtm30-plus-viewers/png-tms7-viewer-3d-globe-medium/r1/png-tms7-viewer-3d-globe-medium.html )   
[unFlatland SRTM30]( http://jaanga.github.io/terrain-srtm30-plus-viewers/png-tms7-viewer-3d-unflatland-features/latest/index.html )  
[unFlatland USGS 1 Second]( http://jaanga.github.io/terrain-usgs-viewers/png-usgs-viewer-3d-unflatland/r1/png-usgs-viewer-3d-unflatland.html )


## Overlays (open)

Map overlay: <select id=selMap onchange=ifr.contentWindow.setTextureMapOverlays() /></select>


## Preferences (open)

Vertical Scale <input type=range id=inpScale min=1 max=50 value=25 step=1 onchange=ifr.contentWindow.updateTerrain(); title='Takes a few seconds to generate...' />

<input type=checkbox id=chkRotate checked /> Auto rotation 

<input type=checkbox id=inpHelpers onchange=ifr.contentWindow.setHelpers(); checked=true /> Display axis


## About


Fully interactive 3D globe viewer for data files created by the 
[Satellite Geodesy research group at Scripps Institution of Oceanography, UCSD]( http://topex.ucsd.edu/WWW_html/srtm30_plus.html )

### Overlays
['Elevation']( http://commons.wikimedia.org/wiki/File:Elevation.jpg ) is from Wikimedia. 

[GLOBALeb3colshade.jpg]( http://www.ngdc.noaa.gov/mgg/topo/pictures/ ) is from the [NOAA National Geophysical Data Center (NGDC)]( http://www.ngdc.noaa.gov/ngdc.html )


[Read Me]( http://jaanga.github.io/terrain-srtm30-plus-viewers/terrain-srtm30-plus-viewers.html#./png-tms7-viewer-3d-globe-low/readme.md# ) ~
[Source Code]( https://github.com/jaanga/terrain-srtm30-plus-viewers/tree/gh-pages/png-tms7-viewer-3d-globe-low/ ) 

Credits: [three.js]( http://threejs.org ) [webgl]( http://khronos.org/webgl/ ) [jaanga]( http://jaanga.github.io )

copyright &copy; 2015 Jaanga authors  
MIT license

<!--
## Messages

<div id=msg ></div>
<div id=msg1 ></div>
<div id=msg2 ></div>
-->