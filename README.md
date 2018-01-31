# Leaflet.EdgeScaleBar
Leaflet plugin that creates scale bars along top and right edge of a map in the Web Mercator projection.

![EdgeScaleBar for Leaflet](https://github.com/GEOF-OSGL/Leaflet.EdgeScaleBar/blob/gh-pages/edgescalebar.png)

Change of linear scale with latitude in Web Mercator projection can affect determination of distances from the map, especially for large areas. Standard scale bar corresponds to the map center. This plugin gives variable scale bar along map edges (concept used on nautical charts) which can be used to see the effect of linear scale change or for estimation of distances between objects. Simply by panning the map one can bring part of the map closer to the scale bar and estimate distance or size.

See the [demo](http://geof-osgl.github.io/Leaflet.EdgeScaleBar/).

To add edge scale bar to your map in Web Mercator projection include the script *leaflet.edgescalebar.js* and add scale bar to your map:

L.edgeScaleBar().addTo(map);

Authors: Dražen Tutić (dtutic@geof.hr) and Ana Kuveždić Divjak (akuvezdic@geof.hr), University of Zagreb, Faculty of Geodesy, GEOF-OSGL Lab
