---
name: The Open Movie Database
x-slug: the-open-movie-database
description: The OMDb API is a free web service to obtain movie information, all content
  and images on the site are contributed and maintained by our users.
image: ""
x-kinRank: "8"
x-alexaRank: "0"
tags: Movies
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/the-open-movie-database/apis.md
specificationVersion: "0.14"
apis:
- name: OMDb - OMDb Search
  x-api-slug: get
  description: Find a movie, series or episode from the OMDb by title, IMDb-id or
    by free-text search
  image: ""
  humanURL: http://omdbapi.com
  baseURL: https://www.omdbapi.com//
  tags: Movie, Movies, Stack Network, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/the-open-movie-database/get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/the-open-movie-database/get-openapi.md
x-common:
- type: x-api-gallery
  url: http://the.new.york.times.api.gallery.streamdata.io
- type: x-api-stack
  url: http://the.open.movie.database.stack.network
- type: x-selfservice-registration
  url: http://beforethecode.com/projects/omdb/apikey.aspx
- type: x-website
  url: http://omdbapi.com
- type: x-website
  url: http://www.omdbapi.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---