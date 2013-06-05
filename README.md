gw2emblem
=========

JavaScript Library used to generate SVG representation of GW2 Guild Emblem

How to use!

Include following files into HTML:
	raphael-min.js
	gw2emblem-defs.js
	gw2emblem.js

Init gw2emblem in empty div call:
	gw2emblem.init('gw2embelm-div', 256); // gw2embelm-div is div ID

Display GW2 Emblem with object fatched from GW2 API:
	gw2emblem.drawEmblemGw2({"background_id":2,"foreground_id":103,"flags":[],"background_color_id":673,"foreground_primary_color_id":443,"foreground_secondary_color_id":473});

TODO:
	"flags" proprty is ignored for now