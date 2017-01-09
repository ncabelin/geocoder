# Google Maps API Geocode server

## Synopsis

This server app returns the geographic coordinates ( longitude, latitude ) in JSON format
using NodeJS, Express and the Google Maps API

## Routes
The home route ('/') will return the following instructions if hosted in Heroku :
'Please put zipcode onto URL to get geolocation coordinates : e.g. https://googlygps.herokuapp.com/90016'

## Installation
1. Install NodeJS and ExpressJS 'npm install express --save'
2. Make sure to include a module named 'key.js' with your Google Maps API key in it on the home directory :

```
module.exports = '&key=INSERT_KEY_HERE';
```
3. Run the app, 'node server.js'

## Contributors

Neptune Michael Cabelin

## License

MIT
