# liri-node-app

How to use:
    Use node to run this program. using node liri.js to run one of the following.
        * concert-this
        * spotify-this-song
        * movie-this
        * do-what-it-says

"Example: node liri.js movie-this star wars"

Concert-this command will provided you with:
    * Name of the venue
    * Venue location
    * Date of the Event

spotify-this-song command will provided you with:
    * Artist(s)
    * The song's name
    * A preview link of the song from Spotify
    * The album that the song is from
    * If no song is provided then your program will default to "The Sign" by Ace of Base. 

Movie-this command will provided you with:
    * Title of the movie.
    * Year the movie came out.
    * IMDB Rating of the movie.
    * Rotten Tomatoes Rating of the movie.
    * Country where the movie was produced.
    * Language of the movie.
    * Plot of the movie.
    * Actors in the movie.

Using Do-what-it-says does:
    * Using the `fs` Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.

    * It should run `spotify-this-song` for "I Want it That Way," as follows the text in `random.txt`.

    * Edit the text in random.txt to test out the feature for movie-this and concert-this.


Technologies Used:
    *javaScript
    *node.js
    *spotify API
    *Bands in Town API
    *OMDB API



