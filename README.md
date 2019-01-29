# Liri-Bot 
Using node.js and api keys

### To install the npm packages, cd into the folder, then run

```
npm install 
```

 ### How does it work?
1. To retrieve the data that will power this app, requests will be sent to the Bands in Town, Spotify and OMDB APIs.
2. LIRI will use the following Node packages:
    • Node-Spotify-API
    • Axios
    • Moment
    • DotEnv


### Commands to run LIRI

Follow the format presented in these queries
```
-node liri.js concert-this '<artist/band name here>'
-node liri.js spotify-this-song '<song name here>'
-node liri.js movie-this '<movie name here>'
-node liri.js do-what-it-says 
```
### Link to video of demonstration
https://drive.google.com/file/d/1Nu_m2bytMg5zzNMr0E4yKku_JxXKXs_5/view

### API Credential sites

Bandsintown: http://www.artists.bandsintown.com/bandsintown-api

Spotify: https://developer.spotify.com/my-applications/

OMDb API: http://www.omdbapi.com/apikey.aspx

## Bonus
Using appendFile, a log.txt is generated with each search the user makes, which collects the same information the user enters and receives.