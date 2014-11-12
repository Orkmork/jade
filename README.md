jade
====
Creating map with Tiled:
New map:
- Map > Properties .... create new "Custom Property" named "unity:scale" with value 0.01
- Map > Add External Tileset ... add all Tilesets needed and finished
- Layer > Add Tile Layer
	order like this:
		- Foreground (create new "Custom Property" named "unity:sortingLayerName" with value "Foreground")
		- Midground (create new "Custom Property" named "unity:sortingLayerName" with value "Midground")
		- Background (create new "Custom Property" named "unity:sortingLayerName" with value "Background")
		- Backwall (create new "Custom Property" named "unity:sortingLayerName" with value "Backwall")
- start with mapping ;)