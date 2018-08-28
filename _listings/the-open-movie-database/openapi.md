swagger: "2.0"
x-collection-name: The Open Movie Database
x-complete: 1
info:
  title: The Open Movie Database
  version: 1.0.0
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