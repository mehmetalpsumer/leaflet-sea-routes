# leaflet-sea-routes

A leaflet plugin for drawing routes on seas between two given points, using [elfalem's Leaflet.curve](https://github.com/elfalem/Leaflet.curve) and [bgrin's javascript-astar](https://github.com/bgrins/javascript-astar).

## Code example

```javascript
// Define coordinates
var source = [0,0];
var destination = [-37, 37];

// Get visuals or the array of the path
var curve = L.pathCurve(source, destination);
var path = L.route(source, destination);

// Add to map
curve.addTo(map);
```