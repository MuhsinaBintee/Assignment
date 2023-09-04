<script>
    import Map from 'ol/Map.js';
    import OSM from 'ol/source/OSM.js';
    import TileLayer from 'ol/layer/Tile.js';
    import View from 'ol/View.js';
    var myview=new ol.View({
        center:[0,0],
        zoom:4
    })
    var mylayer=new ol.layer.Tile({
        source:new ol.source.OSM()
    })
    var layer=[mylayer]

    var map=new ol.map({
        target:'map',
        layers:[mylayer],
        view:myview
    })
</script>
<main>
   <div class="map"></div>
</main>
<style>
   .map{
    height: 400px;
     width: 100%;
   }
</style>