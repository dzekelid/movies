---
swagger: "2.0"
x-collection-name: The Open Movie Database
x-complete: 0
info:
  title: OMDb OMDb Search
  description: Find a movie, series or episode from the OMDb by title, IMDb-id or
    by free-text search
  termsOfService: http://www.omdbapi.com/legal.htm
  contact:
    name: Open Movie Database
    url: http://omdbapi.com
    email: bfritz@fadingsignal.com
  version: "1"
host: www.omdbapi.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /:
    get:
      summary: OMDb Search
      description: Find a movie, series or episode from the OMDb by title, IMDb-id
        or by free-text search
      operationId: getMovies
      x-api-path-slug: get
      parameters:
      - in: query
        name: callback
        description: JSONP callback name
      - in: query
        name: i
        description: A valid IMDb ID (e
      - in: query
        name: page
        description: Page number to return
      - in: query
        name: plot
        description: Return short or full plot
      - in: query
        name: r
        description: The data type to return
      - in: query
        name: s
        description: Movie title to search for
      - in: query
        name: t
        description: Movie title to search for
      - in: query
        name: tomatoes
        description: Include Rotten Tomatoes ratings
      - in: query
        name: type
        description: Type of result to return
      - in: query
        name: v
        description: API version (reserved for future use)
      - in: query
        name: "y"
        description: Year of release
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