# Google-Map
This is an assessment project requested from a hiring company.

The goal of this project is to type a keyword in the search bar and the map changes upon pressing enter or picking from a list the required location.

The HTML code contains titles, styles, and headers.

The body contains 2 div elements the map, and a container with the search bar. and the required script for returning API action using Google Maps API.

In the JS file, the function was defined with a new variable called map where map has 3 elements LonLat (longitude, Latitude), Dimensions of map zoom, type of map.
After defining the input as variable using the input id, i created a new variable to initiate the search from the function.

If the search is empty it does not change, but if the search is true, look in Data base and retrieve place geometry location as place.geometry.location and create
an icon from a pre-existing location with dimensions to size origin anchor and scaled size, then assign the marker to the place from database to the searched name.

If place exists as a small scale use union, else use extend, then display the map.

**NOTE**
files can only be viewed on a live server or xampp.
********
