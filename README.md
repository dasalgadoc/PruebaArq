# PruebaArq


Adicionalmente use https://www.image-map.net/ para ayudarse a generar el HTML


Agregue esto antes de ese HTML
<!-- Image Map Generated by http://www.image-map.net/ -->
<!-- Add jQuery library -->
<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.7/jquery.min.js"></script>

<!-- Add maphilight plugin -->
<script type="text/javascript" src="jquery.maphilight.min.js"></script>

<!-- Activate maphilight plugin -->
<script type="text/javascript">$(function() {
        $('.map').maphilight();
    });
</script>

Y la clase a img class="map"

y luego a cada area esto 
data-maphilight="{&quot;strokeColor&quot;:&quot;C1C240&quot;,&quot;strokeWidth&quot;:5,&quot;fillColor&quot;:&quot;FFE97F&quot;,&quot;fillOpacity&quot;:0.4}"
