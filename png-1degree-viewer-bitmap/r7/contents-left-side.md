[Jaanga]( ../../../index.html ) &raquo; [Terrain]( ../terrain-r2/terrain.html ) &raquo; [SRTM30 Plus]( ../../terrain-srtm30-plus-viewers.html ) &raquo;
[TMS7+ HGT Viewer Bitmap R1]( index-left-side-hackette.html )
===

[GitHub web page]( http://va3c.github.io/viewer/va3c-hacker-cookbook/templates/left-side-hackette/index-left-side-hackette.html "view the files as apps." ) <input value="<< You are here" size=15 style="font:bold 11pt monospace;border-width:0;" >  
&raquo; [GitHub source code]( https://github.com/va3c/viewer/tree/gh-pages/va3c-hacker-cookbook/templates/left-side-hackette/ "View files with GitHub" ) <scan style=display:none ><< You are here</scan>  

[Read Me]( #../readme.md# )

## Open File (open)

<div id=msg ></div>

Pretty colors: <input id=inpPretty type=checkbox title="display a continuous range of colors" >  
Pretty mistake: <input id=inpPrettyMistake type=checkbox title="BGR instead of RGB" >

Select a file to open:  
<input type=file id=inpFile onchange=ifr.contentWindow.readFile(); />

Latitude: <select id=selLat onchange=ifr.contentWindow.selectFile(); ></select>  

Longitude: <select id=selLon onchange=ifr.contentWindow.selectFile(); ></select>

### Go Tiles

<button onclick=ifr.contentWindow.tileEast(); >Tile East</button>
<button onclick=ifr.contentWindow.tileWest(); >Tile West</button>  

<button onclick=ifr.contentWindow.tileNorth(); >Tile North</button>
<button onclick=ifr.contentWindow.tileSouth(); >Tile South</button>

## Header 2

lorem ipsum, quia dolor sit, amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt, ut labore et dolore magnam aliquam quaerat voluptatem. ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? quis autem vel eum iure reprehenderit, qui in ea voluptate velit esse, quam nihil molestiae consequatur, vel illum, qui dolorem eum fugiat, quo voluptas nulla pariatur?


## About

SRTM to HGT TMS7+ Viewer R7

Features include the following:</h4>

View any of the data sample HGT/SRTM files

* Humans can choose to see pretty colors
* Verifies data goes from HGT/SRTM file to heightmap and back to data
* Inspect the HGT/SRTM file for outliers
* Save file as PNG

<a href="https://github.com/jaanga/terrain-plus/tree/gh-pages/cookbook/hgt-viewer/" target="_blank">Source code</a>  
<a href="http://jaanga.github.io" target="_blank">jaanga</a>  
copyright &copy; 2015 Jaanga authors  
MIT license  