[Jaanga]( ../../../index.html ) &raquo; [Terrain]( ../../../index.html ) &raquo; [SRTM30 Plus]( ../../terrain-srtm30-plus-viewers.html ) &raquo;
[PNG TMS7 Viewer 3D]( png-tms7-viewer-3d.html )
===

## Height Map

<div id=heightMapHolder ></div>  
<small>PNG height map image created from Scripps institute data</small> 

## Zoom & Gazetteer (open)

Zoom Level: <select id=selZoom onchange=ifr.contentWindow.setZoom(); ></select>

Gazetteer: <select id=selPlace ></select>

<input type=radio id=inpGolem name=gaz onclick=ifr.contentWindow.setGazetteer(); checked /> Golembek <input type=radio id=inpGEDCO name=gaz onclick=ifr.contentWindow.setGazetteer(); />GEDCO Undersea  
<input type=checkbox id=inpPlacards onchange=ifr.contentWindow.setPlacards(); checked /> Display placards


## Navigation

Lat: <select id=selLat onchange=ifr.contentWindow.selectFile(); ></select> 
Lon: <select id=selLon onchange=ifr.contentWindow.selectFile(); ></select>

TileX: <select id=selTileX onchange=ifr.contentWindow.updateTileParameters(); ></select>
TileY: <select id=selTileY onchange=ifr.contentWindow.updateTileParameters(); ></select>

Go: <button onclick=ifr.contentWindow.tileWest(); title="Go west" >&#8678;</button> 
<button onclick=ifr.contentWindow.tileEast(); title="Go east"  >&#8680;</button> 
<button onclick=ifr.contentWindow.tileNorth(); title="Go north" >&#8679;</button> 
<button onclick=ifr.contentWindow.tileSouth(); title="Go south" >&#8681;</button> 

<div id=msg1 ></div>
<div id=msg2 ></div>

## Overlays (open)

Map overlay: <select id=selMap onchange=ifr.contentWindow.setTextureMap() /></select>

Vertical scale: <input type=range id=inpScale onchange=ifr.contentWindow.scale=parseFloat(this.value);ifr.contentWindow.initCanvas(); min=1 max=20 step=0.1 value=scale /></select>

<input type=checkbox id=inpGrid onchange=ifr.contentWindow.setHelpers(); checked=true /> Display grid & axis

## Location Map (open)

<div id=locationMap ></div>  
<small>Click anywhere in this map to go there</small>

## About

Features of the app include the following:

* Fully interactive 3D viewers for data files created by the 
<a href=http://topex.ucsd.edu/WWW_html/srtm30_plus.html  target="_blank" >Satellite Geodesy research group at Scripps Institution of Oceanography, University of California San Diego</a> 
* Based on the unFlatland series of scripts that make creating 3D views easier

<a href="http://jaanga.github.io/terrain-srtm30-plus/srtm-to-3d/readme-reader.html" target="_blank">Read Me ~</a> 
<a href="https://github.com/jaanga/terrain-srtm30-plus/tree/gh-pages/srtm-to-3d" target="_blank">Source Code ~ </a> 

Credits: <a href="http://threejs.org" target="_blank">three.js</a> - 
<a href="http://khronos.org/webgl/" target="_blank">webgl</a> - 
<a href="http://jaanga.github.io" target="_blank">jaanga</a>

copyright &copy; 2015 Jaanga authors  
MIT license

## Messages

<div id=msg ></div>
<div id=msg1 ></div>
<div id=msg2 ></div>
