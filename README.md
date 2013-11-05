Leaflet.singletilewms
=====================

Leaflet image overlay layer which pulls a single image for each extent from a 
WMS map service.

## Usage
Takes a URL and options. Options which are not part of L.ImageOverlay are
used as WMS parameters.

```javascript
var options = {
  layers: 'MA:MA_Towns',
  format: 'image/png',
  transparent: true,
  opacity: 1
};

var layer = new L.ImageOverlay.WMS('url to your wms map serivce', options);

layer.addTo(map);
```

## License

Leaflet.singletilewms is free software, and may be redistributed under 
the MIT-LICENSE.