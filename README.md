# CGIS Help

CGIS is a city mapper for cyclists and public transit users.

## Basic Inputs

- Panning is done through clicking and draging the mouse. Zooming is through the mouse wheel.
- Intersection information can be displayed by right clicking. The nearest intersection will be highlighted and information will be displayed on the bottom left corner.
  - Holding CTRL while right clicking can highlight multiple intersections at once. Only the most recent intersection will have its information displayed.

## Search Bar

- Seaching is done through the search bar. Streets, points of interests, natural features, and preset cities can be searched directly. The camera will pan and zoom to the correct location.
  - Intersection search is done with a comma seperating the street names. For example, "`Dundas Street West, McCaul Street`" will search for the intersection between those two streets.
  - Clicking on a suggested result will replace the input text and search automatically. Alternatively, the user can press enter to search a partially completed name.
  - LatLon coordinate search can be initiated with the key word "LatLon", followed by a space. For example, "`LatLon 43.66447, -79.39225`". Note that the coordinates should be seperated by a comma.
  - Categories of points of interests or naturals features can also be searched. For example, "`streams`" will show all the streams.

## Switching the Map

- Map switching can be done through either the preset menu, found in `File->Open Preset->"map name"`, or through the file chooser in `File->Open Preset`. The latter option will bring up a file explorer. By choosing either the `.streets.bin` or `.osm.bin` of a chosen map will load that map after a confirmation.
- Switching the map to one of the presets will automatically change the language to the local language.
  - Saint Helena is currently bugged, and switching to that map will not center the map correctly.

