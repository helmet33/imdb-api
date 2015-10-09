###### Semantic Web and Linked Data - Exercise 4
# Internet Movie Database API
In this exercise we will build a HTTP API for an IMDB generated CSV file.

## Exercises
1. Run imdb.js and test out the API as it is.

1. Add a GET method at the route '/movie/year/:year' that responds with the JSON for the list of all moves from the year ':year'.

1. Add a GET method at the route '/movie/random' that will return a random movie from the list.

1. Add a query parameter called nomovies, so that when a user goes to the URL 'http://127.0.0.1/movie/random?nomovies=i', where i is an integer, the API will return a list of i random movies. That is, 'http://127.0.0.1/movie/random?nomovies=10' will return a list of ten random movies.

## Advanced exercises
1. Add a route that lets an API user search for movies with a given term in the movie title. For instance, a user could go to the route '/movie/search/the' and would be returned a list of movies with the word 'the' in the title.

## Note
- The dataset came from [this](http://had.co.nz/data/movies/) source. There is a description of the fields available there.

- You might need the [Express Routing Documentation](http://expressjs.com/guide/routing.html).

- You might also need the [Express req.query Documentation](http://expressjs.com/api.html#req.query).
