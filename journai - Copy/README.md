# README #

This application is run locally. Open up the folder in your IDE and run it. On your browser type localhost:8080/registerPage to begin.
This project was a demo project for my team to practice working with Generative AI.
This was my first time working  with external API's which was a lot of fun. I used the OpenAPI to generate the name of point of interest address. The address was then inputted into the Geocoding API to get the coordinates of  the address. Finally the coordinates were inputted to the MapBox API to generate the route. Thymeleaf was used to create the front end. I used  HTML, CSS and Javascript to create the front end.

### What is this repository for? ###
This project is a generative AI powered journey planning application. It works by getting the start location, end location, point of interest and range from the user.
The app generates a map with a route connecting your start and end destination. Within a given range the route will detour to a location relted to the users point of interest.
The applicaiton is powered by the OpenAPI, MapBox API  and GoogleMaps Geocoder API.


**Other Technologies**
Spring Boot
Thymeleaf
Postgres

