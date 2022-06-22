Setup
The interface uses 3 APIs:

The NY Taxi Fare prediction API
The MapBox Maps API to display a map and address autocomplete
The MapBox Directions API to display the route on the map
These APIs require credentials and the following steps will guide you to get them and set the interface with.

NY Taxi Fare prediction API
Update the script.js to get prediction from your own API hosted on GCP (make sure to use https, not http):

Hint: alternatively, you may use this Le Wagon Prediction API if you do not have one in production:

https://taxifare.lewagon.ai/predict

Note: the following setup steps are optional as you can use Mapbox credentials given by Le Wagon

MapBox Maps and Directions APIs (optional)
Go to MapBox and create an account
Go to your Account and grab your Access Token then set it into the script.js
//...
mapboxgl.accessToken = 'YOUR_MAPBOX_API_ACCESS_TOKEN';
