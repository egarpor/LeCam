## Overview

Marc Hallin, emeritus professor at Université libre de Bruxelles and [Excellence Chair 2017](http://www.uc3m.es/ss/Satellite/UC3MInstitucional/es/TextoMixta/1371224147744/) at the [Carlos III University of Madrid](http://www.uc3m.es) (UC3M), will give on the 22-24th of May a monographic workshop in Le Cam's asymptotic theory of statistical experiments. The workshop is organized by the [Department of Statistics](http://portal.uc3m.es/portal/page/portal/dpto_estadistica/home) of UC3M.

<center>
<img style="width:100%;" id="March UC3M" src="https://raw.githubusercontent.com/egarpor/nonparamarch/master/images/march2.jpg?token=ABNl9quGFSC6xeZ2IWvx7i3ylQnjP08rks5YoevwwA%3D%3D">
<br>

<i>The Department of Statistics at UC3M (Getafe)</i>
</center>
<br>

## About Le Cam's theory and the workshop

TODO.

## About Marc Hallin

TODO.

## Workshop schedule

The **12 hours** workshop will take place in the **22nd, 23rd and 24th of May** and consists of two sessions per day: 9:00-11:00 and 12:00-14:00. The language of the workshop will be **English**.
 
Lessons are to be held in *Sala Costas Goutis* 10.0.23 in the Getafe campus of UC3M. The classroom is located at the ground floor of building 10 (*Campomanes*). The exact coordinates are given in the map below.

<style>
    #map {
        width: 100%;
        height: 400px;
    }
</style>

<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAWD32Ge3oaMcGn4HwR0eGkxi-CDaUR1vc&sensor=false" type="text/javascript">
</script>
<script type="text/javascript">

    function init() {
        // Basic options for a simple Google Map
        // For more options see: https://developers.google.com/maps/documentation/javascript/reference#MapOptions
        var mapOptions = {

            // How zoomed in you want the map to start at (always required)
            zoom: 17,

            // The latitude and longitude to center the map (always required)
            center: new google.maps.LatLng(40.315099, -3.725728),

            // How you would like to style the map.
            // This is where you would paste any style found on Snazzy Maps.
            styles: [{"featureType":"landscape.man_made","elementType":"geometry","stylers":[{"color":"#f7f1df"}]},{"featureType":"landscape.natural","elementType":"geometry","stylers":[{"color":"#d0e3b4"}]},{"featureType":"landscape.natural.terrain","elementType":"geometry","stylers":[{"visibility":"off"}]},{"featureType":"poi","elementType":"labels","stylers":[{"visibility":"off"}]},{"featureType":"poi.business","elementType":"all","stylers":[{"visibility":"off"}]},{"featureType":"poi.medical","elementType":"geometry","stylers":[{"color":"#fbd3da"}]},{"featureType":"poi.park","elementType":"geometry","stylers":[{"color":"#bde6ab"}]},{"featureType":"road","elementType":"geometry.stroke","stylers":[{"visibility":"off"}]},{"featureType":"road","elementType":"labels","stylers":[{"visibility":"off"}]},{"featureType":"road.highway","elementType":"geometry.fill","stylers":[{"color":"#ffe15f"}]},{"featureType":"road.highway","elementType":"geometry.stroke","stylers":[{"color":"#efd151"}]},{"featureType":"road.arterial","elementType":"geometry.fill","stylers":[{"color":"#ffffff"}]},{"featureType":"road.local","elementType":"geometry.fill","stylers":[{"color":"black"}]},{"featureType":"transit.station.airport","elementType":"geometry.fill","stylers":[{"color":"#cfb2db"}]},{"featureType":"water","elementType":"geometry","stylers":[{"color":"#a2daf2"}]}]
        };

        // Get the HTML DOM element that will contain your map
        // We are using a div with id="map" seen below in the <body>
        var mapElement = document.getElementById('map');

        // Create the Google Map using out element and options defined above
        var map = new google.maps.Map(mapElement, mapOptions);

        // To add the marker to the map, use the 'map' property
        var markerUC3M = new google.maps.Marker({
            position: new google.maps.LatLng(40.314107, -3.726073),
            map: map,
            title:"Sala Costas Goutis 10.0.23"
        });

        //Content structure of info Window for the Markers
        var contentStringUC3M = $('<div class="marker-info-win">'+
        '<div class="marker-inner-win"><span class="info-content">'+
        '<strong>Sala Costas Goutis 10.0.23<\/strong>'+
        '<\/span>'+
        '<\/div><\/div>');

        //Create an infoWindow
        var infowindowUC3M = new google.maps.InfoWindow();

        //set the content of infoWindow
        infowindowUC3M.setContent(contentStringUC3M[0]);

        //open infowindow when the page loads
        infowindowUC3M.open(map, markerUC3M);

        //add click event listener to marker which will open infoWindow
        google.maps.event.addListener(markerUC3M, 'click', function() {
            infowindowUC3M.open(map,markerUC3M); // click on marker opens info window
        });

    }

    // When the window has finished loading create our google map below
    google.maps.event.addDomListener(window, 'load', init);

</script> 

<div id="map">
</div>
<br>

## Registration and certificate

The registration is **free of charge**, but is **mandatory to sign up in advance**. To that end, send an email to <edgarcia@est-econ.uc3m.es> with the subject "Le Cam workshop registration". Participants attending to **all** the sessions will receive a certificate.

## How to get to Getafe

The easiest way to get to Getafe from Madrid is *Cercanías* line **C-4**, either departing from *Sol*, *Atocha* or *Nuevos Ministerios*. The closest stops to the UC3M campus are *Las Margaritas* or *Getafe Centro*, both at a 14 minutes walking distance. The direction towards Madrid is either *Alcobendas-San Sebastián de los Reyes* or *Colmenar Viejo*; the direction towards Getafe is *Parla*. This is a schematic representation of the line:

| Parla | Getafe | Madrid | Alcobendas-S.S. de los Reyes / Colmenar Viejo |

Recall that line C-3 also goes through Getafe but the train stop (*Getafe industrial*) is *far away* from the campus.

## Meals and accomodation

TODO.

## Scientific and organizing comittee

[Esther Ruíz Ortega](http://portal.uc3m.es/portal/page/portal/dpto_estadistica/personal/esther_ruiz_ortega) and [Eduardo García Portugués](https://egarpor.github.io).

## Contact

In case of questions, you may contact <edgarcia@est-econ.uc3m.es>.
