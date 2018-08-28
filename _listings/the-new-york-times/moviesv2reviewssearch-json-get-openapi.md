---
swagger: "2.0"
x-collection-name: The New York Times
x-complete: 0
info:
  title: The New York Times Movie Review Search
  description: With the Movie Reviews API, you can search New York Times movie reviews
    by keyword and get lists of NYT Critics' Picks.
  termsOfService: https://developer.nytimes.com/tou
  version: 2.0.0
host: api.nytimes.com
basePath: /svc
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /movies/v2/reviews/search.json:
    get:
      summary: Movie Review Search
      description: With the Movie Reviews API, you can search New York Times movie
        reviews by keyword and get lists of NYT Critics' Picks.
      operationId: getMoveReviews
      x-api-path-slug: moviesv2reviewssearch-json-get
      parameters:
      - in: query
        name: critics-pick
        description: Set this parameter to Y to limit the results to NYT Critics Picks
      - in: query
        name: offset
        description: Positive integer, multiple of 20
      - in: query
        name: opening-date
        description: 'Single date: YYYY-MM-DDStart and end date: YYYY-MM-DD;YYYY-MM-DDThe
          opening-date is the date the movies opening date in the New York region'
      - in: query
        name: order
        description: Sets the sort order of the results
      - in: query
        name: publication-date
        description: 'Single date: YYYY-MM-DDStart and end date: YYYY-MM-DD;YYYY-MM-DDThe
          publication-date is the date the review was first published in The Times'
      - in: query
        name: query
        description: Search keywords; matches movie title and indexed termsTo limit
          your search to exact matches only, surround your search string with single
          quotation marks (e
      - in: query
        name: reviewer
        description: Include this parameter to limit your results to reviews by a
          specific critic
      responses:
        200:
          description: OK
      tags:
      - Movies
      - Reviews
x-streamrank:
  polling_total_time_average: "1.38"
  polling_size_download_average: "15532.82"
  streaming_total_time_average: "1.02"
  streaming_size_download_average: "7785.31"
  change_yes: "28"
  change_no: "2098"
  time_percentage: "26"
  size_percentage: "50"
  change_percentage: "1"
  last_run: "2018-05-12"
  days_run: "7"
  minute_run: "0"
---