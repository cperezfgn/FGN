FGN
===

HUMEDALES DE LA MANCHA
<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <meta name="viewport" content="initial-scale=1, maximum-scale=1,user-scalable=no"/>
    <title>Simple Map</title>
    <link rel="stylesheet" href="http://js.arcgis.com/3.10/js/esri/css/esri.css">
    <style>
      html, body, #map {
        height: 100%;
        width: 100%;
        margin: 0;
        padding: 0;
      }
      body {
        background-color: #FFF;
        overflow: hidden;
        font-family: "Trebuchet MS";
      }
    </style>
    <script src="http://js.arcgis.com/3.10/"></script>
    <script>
      var map;

      require(["esri/map", "dojo/domReady!"], function(Map) {
        map = new Map("map", {
          basemap: "topo",
          center: [-122.45, 37.75], // longitude, latitude
          zoom: 13
        });
      });
    </script>
  </head>

  <body>
    <div id="map"></div>
  </body>
</html>
