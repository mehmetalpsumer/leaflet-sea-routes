# leaflet-sea-routes

A leaflet plugin for drawing routes on seas between two given points, using [elfalem's Leaflet.curve](https://github.com/elfalem/Leaflet.curve) and [bgrin's javascript-astar](https://github.com/bgrins/javascript-astar).

## Code example

```javascript
var source = [0,0];
var destination = [-37, 37];
var curve = L.pathCurve(source, destination);
curve.addTo(map);
```