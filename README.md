LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.
LIRI uses the following commands:
- `my-tweets`

- `spotify-this-song`

- `movie-this`

- `do-what-it-says`

How to Run:

1: node liri.js my-tweets
shows your last tweets

2: node liri.js spotify-this-song `<song name here>`
Shows the following information about the song 
    - Artist(s)
    - The song's name
    - A preview link of the song from Spotify
    - The album that the song is from

3: node liri.js movie-this `<movie name here>`

    - Title of the movie.
    - Year the movie came out.
    - IMDB Rating of the movie.
    - Country where the movie was produced.
    - Language of the movie.
    - Plot of the movie.
    - Actors in the movie.
    - Rotten Tomatoes Rating.
    - Rotten Tomatoes URL.

   
4: node liri.js do-what-it-says
-This will output the command placed in random.txt file
