[Jaanga]( ../../../index.html ) &raquo; [Terrain]( ../../../terrain-r2/terrain.html ) &raquo; [SRTM30 Plus]( ../../terrain-srtm30-plus-viewers.html ) &raquo;
[3D unFlatland R3]( png-tms7-viewer-3d-unflatland.html "View SRTM data prepared by the Scripps Institution of Oceanography at UCSD" )
===
[3D Globe lowRes]( http://jaanga.github.io/terrain-srtm30-plus-viewers/png-tms7-viewer-3d-globe-low/latest/index.html ) 
[USGS 1 Second]( http://jaanga.github.io/terrain-usgs-viewers/png-usgs-viewer-3d-unflatland/r1/png-usgs-viewer-3d-unflatland.html )

## Height Map

<div id=heightMapHolder ></div>  
<small>PNG height map image created from Scripps Institution of Oceanography data</small> 

## Zoom & Gazetteer (open)

Zoom Level: <select id=selZoom onchange=ifr.contentWindow.setZoom(); ></select>

Gazetteer: <select id=selPlace ></select>

<input type=radio id=inpGolem name=gaz onclick=ifr.contentWindow.setGazetteer(); title="Over 2,000 place names" checked /> Golembek 
<input type=radio id=inpGEBCO name=gaz onclick=ifr.contentWindow.setGazetteer(); title="over 3,800 undersea feature names" />GEBCO Undersea  
<input type=checkbox id=inpPlacards onchange=ifr.contentWindow.setPlacards(); checked /> Display placards


## Navigation

Lat: <select id=selLat onchange=ifr.contentWindow.selectFile(); ></select> 
Lon: <select id=selLon onchange=ifr.contentWindow.selectFile(); ></select>

TileX: <select id=selTileX onchange=ifr.contentWindow.setTileParameters(); ></select>
TileY: <select id=selTileY onchange=ifr.contentWindow.setTileParameters(); ></select>

Go: <button onclick=ifr.contentWindow.tileWest(); title="Go west" >&#8678;</button> 
<button onclick=ifr.contentWindow.tileEast(); title="Go east"  >&#8680;</button> 
<button onclick=ifr.contentWindow.tileNorth(); title="Go north" >&#8679;</button> 
<button onclick=ifr.contentWindow.tileSouth(); title="Go south" >&#8681;</button> 

<button onclick=ifr.contentWindow.setPermalink(); >Create Permalink</button>

## Overlays (open)

Map overlay: <select id=selMap onchange=ifr.contentWindow.setMapOverlay() /></select>

Vertical scale: <input type=range id=inpScale onchange=ifr.contentWindow.scale=parseFloat(this.value);ifr.contentWindow.initCanvas(); min=1 max=20 step=0.1 value=scale /></select>

<input type=checkbox id=inpGrid onchange=ifr.contentWindow.setHelpers(); checked=true /> Display grid & axis  
<input type=checkbox id=inpEdges onchange=ifr.contentWindow.setEdges(); /> Display edges

## Location Map (open)

<div id=locationMap title='Not fully Mercatorized yet...' ></div>  
<small>Click anywhere in this map to go there</small>

## About

Fully interactive 3D globe viewer for data files created by the 
[Satellite Geodesy research group at Scripps Institution of Oceanography, UCSD]( http://topex.ucsd.edu/WWW_html/srtm30_plus.html )


[FAQ]( http://jaanga.github.io/terrain-r2/terrain.html#faq.md# ) ~ 
[Read Me]( http://jaanga.github.io/terrain-srtm30-plus-viewers/terrain-srtm30-plus-viewers.html#./png-tms7-viewer-3d-unflatland-features/readme.md# ) ~
[Source Code]( https://github.com/jaanga/terrain-srtm30-plus-viewers/tree/gh-pages/png-tms7-viewer-3d-unflatland-features ) 

### Gazetteers

[Golembeck]( http://www.golombek.com/locations.html ) [GEBCO]( http://www.gebco.net/data_and_products/undersea_feature_names/ )

### Overlays
Map overlay image tiles are courtesy of:

[OpenStreetMap]( https://www.openstreetmap.org/ )
[Google Maps]( https://www.google.com/maps/ )  
[OpenCycleMap]( http://www.opencyclemap.org/ )
[MapQuest]( http://www.mapquest.com/ )
[Stamen]( http://stamen.com/ )

### Code

[three.js]( http://threejs.org ) [webgl]( http://khronos.org/webgl/ ) [jaanga]( http://jaanga.github.io )

copyright &copy; 2015 Jaanga authors  
MIT license


## Messages

<div id=msg ></div>
<div id=msg1 ></div>
<div id=msg2 ></div>
