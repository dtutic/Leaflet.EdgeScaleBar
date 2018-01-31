# Leaflet.EdgeScaleBar
Creates scale bars along top and right edge of a map in Web Mercator projection.

Change of linear scale with latitude in Web Mercator projection can affect determination of distances from the map, especially for large areas. This plugin gives variable scale bar along map edges (similar as on nautical chars) which can be used to detect effect of linear scale change or for determination of distances between objects. Simply by panning the map one can bring part of map closer to the scale bar and estimate distance or size.

See the [demo](http://geof-osgl.github.com]

To add edge scale bar to your map in Web Mercator projection include the script leaflet.edgescalebar.js and add scale bar to your my:

L.edgeScaleBar().addTo(map);

Authors: Dražen Tutić (dtutic@geof.hr) and Ana Kuveždić Divjak (akuvezdic@geof.hr), University of Zagreb, Faculty of Geodesy, GEOF-OSGL Lab
