# State Shapes

So you want to make a map of the US states. You go to the Census to get the [TIGER shapefiles](https://www.census.gov/geo/maps-data/data/tiger.html), download the state files, and load them up.

![The states](http://cl.ly/image/1Y1i0f2Q2k03/QGIS.png)

Great! ...er, wait. Wasn't there a Long Island Sound? Didn't the Florida Keys used to be islands? And what the heck happened to Michigan?!

What's going on? The main TIGER files contain both land *and territorial waters* of each state. That's not usually what we have in mind.

The Census does have some land-only borders, however, in the [Cartographic Boundary Files](https://www.census.gov/geo/maps-data/data/tiger-cart-boundary.html). The state versions of those are presented here (at 20m, 5m, and 500k resolutions) in shapefile, geojson, and topojson formats, and rendered into SVG and Adobe Illustrator files (using an Albers projection with modified positions for Alaska and Hawaii).

Enjoy!
