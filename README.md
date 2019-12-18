# liri-node-app

# LIRI Bot
Created By: Hyejin Kim, Creator

Date: Dec. 18, 2019

- - -

### Overview

In this assignment, you will make LIRI. LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a _Language_ Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

# What is Liri?

1. LIRI will search Spotify for songs, Bands in Town for concerts, and OMDB for movies.
2. Using Below Reference (APIs): 
   * [Node-Spotify-API](https://www.npmjs.com/package/node-spotify-api)

   * [Axios](https://www.npmjs.com/package/axios)

     * You'll use Axios to grab data from the [OMDB API](http://www.omdbapi.com) and the [Bands In Town API](http://www.artists.bandsintown.com/bandsintown-api)

   * [Moment](https://www.npmjs.com/package/moment)

   * [DotEnv](https://www.npmjs.com/package/dotenv)
   
- - -

### Quick Instructions

1. install NPM packages

2. Make a `.gitignore` file and update:

```
node_modules
.DS_Store
.env
```

3. Make a JavaScript file named `keys.js` and add spotify exports

4. Next, create a file named `.env`, add the following to it, replacing the values with your API keys (no quotes) once you have them: so that you can keep your API keys private. 

5. Make a file called `random.txt`, and on file, add: 

     * spotify-this-song,"I Want it That Way"

6. Make a JavaScript file named `liri.js`, add code to make node comment to work.

7. Using your Terminal/ Git Bash, try 'node liri.js' can take in one of the following commands:

   * `concert-this`

   * `spotify-this-song`

   * `movie-this`

   * `do-what-it-says`

### What Each Command Should Do

1. `node liri.js concert-this <artist/band name here>`

   * This will search the Bands in Town Artist Events API for an artist and render the following information about each event to the terminal:

     * Name of the venue

     * Venue location

     * Date of the Event (use moment to format this as "MM/DD/YYYY")

2. `node liri.js spotify-this-song '<song name here>'`

   * This will show the following information about the song in your terminal/bash window

     * Artist(s)

     * The song's name

     * A preview link of the song from Spotify

     * The album that the song is from

3. `node liri.js movie-this '<movie name here>'`

   * This will output the following information to your terminal/bash window:

     ```
       * Title of the movie.
       * Year the movie came out.
       * IMDB Rating of the movie.
       * Rotten Tomatoes Rating of the movie.
       * Country where the movie was produced.
       * Language of the movie.
       * Plot of the movie.
       * Actors in the movie.
     ```

4. `node liri.js do-what-it-says`

   * Using the `fs` Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.

     * It should run using what it says in `random.txt`.


### IN ADDITION TO SCREENSHOTS

* In addition to logging the data to your terminal/bash window, output the data to a .txt file called `log.txt`. You will see the log of all comment output.



- - -

### SCREENSHOTS




- - -

### Links & Portfolio's Links
*  [Deployed Version of App](https://cshjnim.github.io/liri-node-app/)
*  [Hyejin's Portfolio](https://cshjnim.github.io/)

### Summary of Technologies Used on this project

* Javascript
* Nodejs
* Node packages:
  * Node-Spotify-API
  * Axios Request
  * Moment
  * DotEnv
* APIs used:
  * Spotify
  * Bands in Town
  * OMDB
* Git
* GitHub

- - -
### CHECKLISTS

1. Clearly state the problem the app is trying to solve (i.e. what is it doing and why) &check;
2. Give a high-level overview of how the app is organized &check;
3. Give start-to-finish instructions on how to run the app &check;
4. Include screenshots, gifs or videos of the app functioning &check;
5. Contain a link to a deployed version of the app &check;
6. Clearly list the technologies used in the app &check;
7. State your role in the app development &check;
