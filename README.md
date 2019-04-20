Created By Louis Carter

LIRI will search Spotify for songs, Bands in Town for concerts, and OMDB for movies.
 liri.js can take in one of the following commands:

See the video of how the application works here:

https://drive.google.com/file/d/1ShA0kd455ztXcVwwA4y317cJzrkTKR3n/view

Screen shots are in the images file: 

To mke the application work there have been several applications and technologies that were used;

 Javascript
* Nodejs
* Node packages:
    * Node-Spotify-API
    * Request
    * Moment
    * DotEnv
* APIs used:
    * Bands in Town
    * OMDB
* Git
* GitHub

The way to do this is to log into a node server and type the folowing command followed by one of the commands listed below:

 EX: Node server.js `concert this bandname`

* `concert-this`

   * `spotify-this-song`

   * `movie-this`

   * `do-what-it-says`

    # concert-this: This will search the Bands in Town Artist Events API and display the following:
        * Name of the venue
        * Venue location
        * The date of the Event (use moment to format this as "MM/DD/YYYY").

    # spotify-this-song: This will retrieve data from Spotify and display the following information about the song in your terminal/bash window:
        * Artist(s)
        * The song's name
        * A preview link of the song from Spotify
        * The album that the song is from

    # movie-this: This will retrieve data from the OMDB API and output the following information to your terminal/bash window:
        * Title of the movie.
        * Year the movie came out.
        * IMDB Rating of the movie.
        * Rotten Tomatoes Rating of the movie.
        * Country where the movie was produced.
        * Language of the movie.
        * Plot of the movie.
        * Actors in the movie.

    #do-what-it-says: This will take the text inside of random.txt and then use it run spotify-this-song for the text in random.txt.

