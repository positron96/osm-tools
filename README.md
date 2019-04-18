# osm-tools
This project is a web application that filters out large changesets (most often created by bots) from OpenStreetMaps changeset feeds


It you want to follow changes of OpenStreetMaps.org, you do not wish for large changesets covering half of the planet to appear in your rss feed (most of such changesets do not contain changes to the area you specified anyway) This web-based application is designed to filter out huge changesets and leave only local changes.

Specifically, this application filters out changesets based on <georss:box> element of rss items and drops those entries that cover more that 20 degrees of latitude or 40 degrees of longitude. However, this behaviour may be improved in future versions.

Go to project page to use the service: http://positron96.appspot.com/osmfilter.html Usage instructions are included into the main page.

The project is in development stage, so any comments, suggestions and bugreports are welcome. 
