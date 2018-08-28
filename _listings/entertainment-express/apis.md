---
name: Entertainment Express
x-slug: entertainment-express
description: Internet Video Archive (IVA) is a leading entertainment data company
  providing metadata, images and trailers/clips, for movie and TV content. With the
  launch of its award-winning Entertainment Express APIs, clients can easily access
  everything they need to create engaging content discovery experiences. By using
  Entertainment Express, clients can also connect to other services like movie showtimes
  and ticketing, content recommendations, content availability and TV channel line-ups.
  With over a million titles, episodes and over 150,000 videos available, IVA makes
  it easy for developers to integrate all the services they need at a very affordable
  price.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Movies
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/apis.md
specificationVersion: "0.14"
apis:
- name: Entertainment Express - Returns list of unique MovieId changes greater than
    or equal to date (UTC).
  x-api-slug: changesmovieshistory-get
  description: Use to get the ID's of the movies that have been added or changed and
    use /Movies/{ID} to get back the object with the updated data and replace in your
    database.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/changesmovieshistory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/changesmovieshistory-get-openapi.md
- name: Entertainment Express - Returns list of unique MovieId and Entity changes
    greater than or equal to date (UTC).
  x-api-slug: changesmovieshistorywithentity-get
  description: Same as /Changes/Movies/History but with the specific entities that
    have changed inside the MovieResponse.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/changesmovieshistorywithentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/changesmovieshistorywithentity-get-openapi.md
- name: Entertainment Express - Returns list of movies based on the weekend box office
    revenue.
  x-api-slug: chartsmoviesboxoffice-get
  description: Returns top 10 box office movies.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/chartsmoviesboxoffice-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/chartsmoviesboxoffice-get-openapi.md
- name: Entertainment Express - Returns list of Most Anticipated movies based on IVA
    data.
  x-api-slug: chartsmoviesmostanticipated-get
  description: Requires Skip and Take. Maximum page size is 100.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/chartsmoviesmostanticipated-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/chartsmoviesmostanticipated-get-openapi.md
- name: Entertainment Express - Returns list of popular movies.
  x-api-slug: chartsmoviespopular-get
  description: Requires Skip and Take. Maximum page size is 100.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/chartsmoviespopular-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/chartsmoviespopular-get-openapi.md
- name: Entertainment Express - Get GoWatchIt Movie Availability.
  x-api-slug: gowatchitmoviesidavailabilities-get
  description: Returns GoWatchIt movie availability by Entertainment Movie ID.  Special
    permission is required to access this endpoint.  Contact [Sales](mailto:Sales@InternetVideoArchive.com)
    for more information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/gowatchitmoviesidavailabilities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/gowatchitmoviesidavailabilities-get-openapi.md
- name: Entertainment Express - Get MovieTickets Movies releasing soon.
  x-api-slug: movieticketsmoviescomingsoon-get
  description: Returns MovieTickets Movies releasing soon.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/movieticketsmoviescomingsoon-get-openapi.md
- name: Entertainment Express - Get MovieTickets Movies in theaters.
  x-api-slug: movieticketsmoviesnowplaying-get
  description: Returns MovieTickets Movies currently in theaters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/movieticketsmoviesnowplaying-get-openapi.md
- name: Entertainment Express - Returns a paged list of all movies.
  x-api-slug: moviesall-get
  description: "By default the API will only return basic title information. Additional
    objects can be included by passing the object in the Includes parameter.   \n\n\n`Subscriptions
    with \"Limited\" data will only be able to include basic title information and
    Videos.`"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/moviesall-get-openapi.md
- name: Entertainment Express - Returns all MovieAlternateIdTypes.
  x-api-slug: moviesalternateidtypes-get
  description: "Movie alternate ID types refer to 3rd party IDs that IVA matches its
    own movie IDs.  **EX: IMDB, TMDB**.  \n\n`Use to get the Id of the ID type to
    use with /Find/Movie.`"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/moviesalternateidtypes-get-openapi.md
- name: Entertainment Express - Returns list of all Movies coming to US Theaters.
  x-api-slug: moviescomingsoon-get
  description: |-
    Requires Skip and Take. Maximum page size is 10.

    By default the API will only return basic title information.
    Additional objects can be included by passing the object in the Includes parameter in a comma separated list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/moviescomingsoon-get-openapi.md
- name: Entertainment Express - Returns list of all Movies currently in US Theaters.
  x-api-slug: moviesintheaters-get
  description: |-
    Requires Skip and Take. Maximum page size is 10.

    By default the API will only return basic title information.
    Additional objects can be included by passing the object in the Includes parameter in a comma separated list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/moviesintheaters-get-openapi.md
- name: Entertainment Express - Perform a match to Entertainment using Title, Year,
    Cast and Director. Returns best match and score for the match.
  x-api-slug: moviesmatch-get
  description: Use to match IVA movie data to another data source using title, year,
    cast etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/moviesmatch-get-openapi.md
- name: Entertainment Express - Returns all Movie Certifications
  x-api-slug: moviesmoviecertifications-get
  description: Returns all Movie Certifications used in a movie response with the
    Releases object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/moviesmoviecertifications-get-openapi.md
- name: Entertainment Express - Returns all Movie Genres.
  x-api-slug: moviesmoviegenres-get
  description: List of all movie genres used in the API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/moviesmoviegenres-get-openapi.md
- name: Entertainment Express - Returns all Movie ReleaseTypes
  x-api-slug: moviesreleasetypes-get
  description: 'Release type refers to the release. **EX: Theatrical, Home Video,
    etc.**'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/moviesreleasetypes-get-openapi.md
- name: Entertainment Express - Search and discover movies.
  x-api-slug: moviessearchanddiscover-get
  description: |-
    Searchable Fields:
    Title, AlternateTitles, Genres, OriginalReleaseDate, UnitedStatesReleaseDate, GermanyReleaseDate, FranceReleaseDate, UnitedKingdomReleaseDate, ItalyReleaseDate, JapanReleaseDate, Tags, Cast, Directors, Descriptions, Ratings, OriginalLanguage.
    [Syntax Ref](https://docs.microsoft.com/en-us/rest/api/searchservice/simple-query-syntax-in-azure-search)

    Filterable Fields:
    ID, Title, AlternateTitles, Genres, OriginalReleaseDate, UnitedStatesReleaseDate, GermanyReleaseDate, FranceReleaseDate, UnitedKingdomReleaseDate, ItalyReleaseDate, JapanReleaseDate, Year, Tags, Cast, Directors, Descriptions, HasVideo, PosterFilePath, Ratings, OriginalLanguage, Runtime, Budget, Revenue, Created, Modified.
    [Syntax Ref](https://docs.microsoft.com/en-us/rest/api/searchservice/odata-expression-syntax-for-azure-search)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/moviessearchanddiscover-get-openapi.md
- name: Entertainment Express - Returns movie data for a specific IVA MovieId.
  x-api-slug: moviesid-get
  description: "By default the API will only return basic title information. Additional
    objects can be included by passing the object in the Includes parameter.   \n\n\n`Subscriptions
    with \"Limited\" data will only be able to include basic title information and
    Videos.`"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/moviesid-get-openapi.md
- name: 'Entertainment Express - '
  x-api-slug: tvmediagenresmovies-get
  description: Gets list of movie genres.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/tvmediagenresmovies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/movies/master/_listings/entertainment-express/tvmediagenresmovies-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://emuseum.api.docs.api.gallery.streamdata.io
- type: x-api-stack
  url: http://entertainment.express.stack.network
- type: x-blog
  url: https://www.internetvideoarchive.com/blog/
- type: x-developer
  url: https://developer.iva-api.com/
- type: x-pricing
  url: https://www.internetvideoarchive.com/pricing/
- type: x-website
  url: https://www.internetvideoarchive.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---