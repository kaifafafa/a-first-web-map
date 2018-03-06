<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <meta name="viewport" content="initial-scale=1, maximum-scale=1,user-scalable=no">
    <title></title>
    <link rel="stylesheet" href="https://js.arcgis.com/3.23/esri/css/esri.css">
    <script src="https://js.arcgis.com/3.23/"></script>
    <style>
      html, body, #map {
        height: 100%;
        padding: 0;
        margin: 0;
      }
    </style>

    <script>
    var map;
    require(["esri/map", "dojo/domReady!"], function(Map) {
      map = new Map("map", {
        basemap: "topo",
        center: [-122.45, 37.75],
        zoom: 13
      });
    });
    </script>
  </head>
  <body class="claro">
  <div id="map"></div>
</body>
</html>
