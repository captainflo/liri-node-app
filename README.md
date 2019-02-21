# liri-node-app

LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface.

## Git clone the repository
``` git clone https://github.com/captainflo/liri-node-app.git ```

###### Open your Terminal : 

## install the package (spotify, Imdb, Axios, Moment, DotEnv)
``` npm install ```

## This will search the Bands in Town Artist Events API 
```node liri.js concert-this <YourArtist>```

## This will show the following information about the song
```node liri.js spotify-this-song <YourSound>```

## This will output the following information about your Movies
```node liri.js movie-this <YourMovies>```

## Using the `fs` Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands
```node liri.js do-what-it-says```
