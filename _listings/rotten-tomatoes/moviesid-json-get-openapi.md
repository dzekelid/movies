---
swagger: "2.0"
x-collection-name: Rotten Tomatoes
x-complete: 0
info:
  title: Rotten Tomatoes Get Movies
  description: Get movies .json.
  contact:
    name: Mike Ralphson
    url: https://github.com/mermade/mashery2openapi
    email: mike.ralphson@gmail.com
  version: "1.0"
host: api.rottentomatoes.com
basePath: /api/public/v1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /lists/movies.json:
    get:
      summary: Get Lists Movies
      description: Get lists movies.json.
      operationId: getListsMovies.json
      x-api-path-slug: listsmovies-json-get
      responses:
        200:
          description: OK
      tags:
      - Lists
      - Movies
  /lists/movies/box_office.json:
    get:
      summary: Get Lists Movies Box Office
      description: Get lists movies box office.json.
      operationId: getListsMoviesBoxOffice.json
      x-api-path-slug: listsmoviesbox-office-json-get
      parameters:
      - in: query
        name: country
        description: Provides localized data for the selected country (ISO 3166-1
          alpha-2) if available
      - in: query
        name: limit
        description: Limits the number of movies returned
      responses:
        200:
          description: OK
      tags:
      - Lists
      - Movies
      - Box
      - Office
  /lists/movies/in_theaters.json:
    get:
      summary: Get Lists Movies In Theaters
      description: Get lists movies in theaters.json.
      operationId: getListsMoviesInTheaters.json
      x-api-path-slug: listsmoviesin-theaters-json-get
      parameters:
      - in: query
        name: country
        description: Provides localized data for the selected country (ISO 3166-1
          alpha-2) if available
      - in: query
        name: page
        description: The selected page of in theaters movies
      - in: query
        name: page_limit
        description: The amount of movies in theaters to show per page
      responses:
        200:
          description: OK
      tags:
      - Lists
      - Movies
      - In
      - Theaters
  /lists/movies/opening.json:
    get:
      summary: Get Lists Movies Opening
      description: Get lists movies opening.json.
      operationId: getListsMoviesOpening.json
      x-api-path-slug: listsmoviesopening-json-get
      parameters:
      - in: query
        name: country
        description: Provides localized data for the selected country (ISO 3166-1
          alpha-2) if available
      - in: query
        name: limit
        description: Limits the number of opening movies returned
      responses:
        200:
          description: OK
      tags:
      - Lists
      - Movies
      - Opening
  /lists/movies/upcoming.json:
    get:
      summary: Get Lists Movies Upcoming
      description: Get lists movies upcoming.json.
      operationId: getListsMoviesUpcoming.json
      x-api-path-slug: listsmoviesupcoming-json-get
      parameters:
      - in: query
        name: country
        description: Provides localized data for the selected country (ISO 3166-1
          alpha-2) if available
      - in: query
        name: page
        description: The selected page of upcoming movies
      - in: query
        name: page_limit
        description: The amount of upcoming movies to show per page
      responses:
        200:
          description: OK
      tags:
      - Lists
      - Movies
      - Upcoming
  /movies.json:
    get:
      summary: Get Movies
      description: Get movies.json.
      operationId: getMovies.json
      x-api-path-slug: movies-json-get
      parameters:
      - in: query
        name: page
        description: The selected page of movie search results
      - in: query
        name: page_limit
        description: The amount of movie search results to show per page
      - in: query
        name: q
        description: The plain text search query to search for a movie
      responses:
        200:
          description: OK
      tags:
      - Movies
  /movies/{id}.json:
    get:
      summary: Get Movies
      description: Get movies .json.
      operationId: getMovies.json
      x-api-path-slug: moviesid-json-get
      parameters:
      - in: path
        name: id
        description: Movie ID
      responses:
        200:
          description: OK
      tags:
      - Movies
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---