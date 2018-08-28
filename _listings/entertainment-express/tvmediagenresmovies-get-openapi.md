---
swagger: "2.0"
x-collection-name: Entertainment Express
x-complete: 0
info:
  title: 'Entertainment Express '
  description: Gets list of movie genres.
  version: "2.0"
host: ee.iva-api.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Changes/Movies/History/:
    get:
      summary: Returns list of unique MovieId changes greater than or equal to date
        (UTC).
      description: Use to get the ID's of the movies that have been added or changed
        and use /Movies/{ID} to get back the object with the updated data and replace
        in your database.
      operationId: GetMovieChangeHistory
      x-api-path-slug: changesmovieshistory-get
      parameters:
      - in: query
        name: Date
        description: Starting date
      - in: query
        name: Skip
        description: Offset for paging
      - in: query
        name: Take
        description: Maximum number of rows returned
      responses:
        200:
          description: OK
      tags:
      - Changes
      - Movies
      - History
  /Changes/Movies/HistoryWithEntity/:
    get:
      summary: Returns list of unique MovieId and Entity changes greater than or equal
        to date (UTC).
      description: Same as /Changes/Movies/History but with the specific entities
        that have changed inside the MovieResponse.
      operationId: GetMovieChangeHistoryWithEntity
      x-api-path-slug: changesmovieshistorywithentity-get
      parameters:
      - in: query
        name: Date
        description: Starting date
      - in: query
        name: Skip
        description: Offset for paging
      - in: query
        name: Take
        description: Maximum number of rows returned
      responses:
        200:
          description: OK
      tags:
      - Changes
      - Movies
      - HistoryWithEntity
  /Charts/Movies/Boxoffice:
    get:
      summary: Returns list of movies based on the weekend box office revenue.
      description: Returns top 10 box office movies.
      operationId: GetChartMoviesBoxoffice
      x-api-path-slug: chartsmoviesboxoffice-get
      parameters:
      - in: query
        name: Skip
        description: Determines where to start page
      - in: query
        name: Take
        description: Determines the page size
      responses:
        200:
          description: OK
      tags:
      - Charts
      - Movies
      - Boxoffice
  /Charts/Movies/MostAnticipated:
    get:
      summary: Returns list of Most Anticipated movies based on IVA data.
      description: Requires Skip and Take. Maximum page size is 100.
      operationId: GetChartMoviesMostAnticipated
      x-api-path-slug: chartsmoviesmostanticipated-get
      parameters:
      - in: query
        name: Skip
        description: Determines where to start page
      - in: query
        name: Take
        description: Determines the page size
      responses:
        200:
          description: OK
      tags:
      - Charts
      - Movies
      - MostAnticipated
  /Charts/Movies/Popular:
    get:
      summary: Returns list of popular movies.
      description: Requires Skip and Take. Maximum page size is 100.
      operationId: GetChartMoviesPopular
      x-api-path-slug: chartsmoviespopular-get
      parameters:
      - in: query
        name: Skip
        description: Determines where to start page
      - in: query
        name: Take
        description: Determines the page size
      responses:
        200:
          description: OK
      tags:
      - Charts
      - Movies
      - Popular
  /GoWatchIt/Movies/{Id}/Availabilities:
    get:
      summary: Get GoWatchIt Movie Availability.
      description: Returns GoWatchIt movie availability by Entertainment Movie ID.  Special
        permission is required to access this endpoint.  Contact [Sales](mailto:Sales@InternetVideoArchive.com)
        for more information.
      operationId: GetGoWatchItMovieAvailabilities
      x-api-path-slug: gowatchitmoviesidavailabilities-get
      parameters:
      - in: query
        name: ApiKey
        description: Required GoWatchIt API key
      - in: path
        name: Id
        description: Required ID of Entertainment Movie
      responses:
        200:
          description: OK
      tags:
      - GoWatchIt
      - Movies
      - Id
      - Availabilities
  /MovieTickets/Movies/ComingSoon:
    get:
      summary: Get MovieTickets Movies releasing soon.
      description: Returns MovieTickets Movies releasing soon.
      operationId: GetMovieTicketsMoviesComingSoon
      x-api-path-slug: movieticketsmoviescomingsoon-get
      parameters:
      - in: query
        name: Culture
        description: Culture to retrieve response
      - in: query
        name: PageNumber
        description: Page number for paging results
      - in: query
        name: PageSize
        description: Limits the total items returned
      responses:
        200:
          description: OK
      tags:
      - MovieTickets
      - Movies
      - ComingSoon
  /MovieTickets/Movies/NowPlaying:
    get:
      summary: Get MovieTickets Movies in theaters.
      description: Returns MovieTickets Movies currently in theaters.
      operationId: GetMovieTicketsMoviesNowPlaying
      x-api-path-slug: movieticketsmoviesnowplaying-get
      parameters:
      - in: query
        name: Culture
        description: Culture to retrieve response
      - in: query
        name: PageNumber
        description: Page number for paging results
      - in: query
        name: PageSize
        description: Limits the total items returned
      responses:
        200:
          description: OK
      tags:
      - MovieTickets
      - Movies
      - NowPlaying
  /Movies/All:
    get:
      summary: Returns a paged list of all movies.
      description: "By default the API will only return basic title information. Additional
        objects can be included by passing the object in the Includes parameter.   \n\n\n`Subscriptions
        with \"Limited\" data will only be able to include basic title information
        and Videos.`"
      operationId: GetAllMovies
      x-api-path-slug: moviesall-get
      parameters:
      - in: query
        name: Includes
        description: List of additional objects to include in the movie objectSearch
          movie by OriginalTitle
      - in: query
        name: Skip
        description: Skips records using for paging results
      - in: query
        name: Take
        description: Limits the total items returned
      responses:
        200:
          description: OK
      tags:
      - Movies
  /Movies/AlternateIdTypes:
    get:
      summary: Returns all MovieAlternateIdTypes.
      description: "Movie alternate ID types refer to 3rd party IDs that IVA matches
        its own movie IDs.  **EX: IMDB, TMDB**.  \n\n`Use to get the Id of the ID
        type to use with /Find/Movie.`"
      operationId: GetMovieAlternateIdTypes
      x-api-path-slug: moviesalternateidtypes-get
      responses:
        200:
          description: OK
      tags:
      - Movies
      - AlternateIdTypes
  /Movies/ComingSoon/:
    get:
      summary: Returns list of all Movies coming to US Theaters.
      description: |-
        Requires Skip and Take. Maximum page size is 10.

        By default the API will only return basic title information.
        Additional objects can be included by passing the object in the Includes parameter in a comma separated list.
      operationId: GetMoviesComingSoon
      x-api-path-slug: moviescomingsoon-get
      parameters:
      - in: query
        name: Includes
        description: List of additional objects to include in the movie response
      - in: query
        name: Skip
        description: Determines where to start page
      - in: query
        name: Take
        description: Determines the page size
      responses:
        200:
          description: OK
      tags:
      - Movies
      - ComingSoon
  /Movies/InTheaters/:
    get:
      summary: Returns list of all Movies currently in US Theaters.
      description: |-
        Requires Skip and Take. Maximum page size is 10.

        By default the API will only return basic title information.
        Additional objects can be included by passing the object in the Includes parameter in a comma separated list.
      operationId: GetMoviesInTheaters
      x-api-path-slug: moviesintheaters-get
      parameters:
      - in: query
        name: Includes
        description: List of additional objects to include in the movie response
      - in: query
        name: Skip
        description: Determines where to start page
      - in: query
        name: Take
        description: Determines the page size
      responses:
        200:
          description: OK
      tags:
      - Movies
      - InTheaters
  /Movies/Match/:
    get:
      summary: Perform a match to Entertainment using Title, Year, Cast and Director.
        Returns best match and score for the match.
      description: Use to match IVA movie data to another data source using title,
        year, cast etc.
      operationId: MatchToMovie
      x-api-path-slug: moviesmatch-get
      parameters:
      - in: query
        name: AlternateTitles
        description: Alternate Titles of movie to be matched
      - in: query
        name: Cast
        description: Cast members of movie to be matched
      - in: query
        name: Directors
        description: Directors of movie to be matched
      - in: query
        name: StringDistance
        description: For fuzzy title match, default is 4, set to 0 for no fuzzy match
      - in: query
        name: Title
        description: Title of movie to be matched
      - in: query
        name: Year
        description: Release Year of movie to be matched
      responses:
        200:
          description: OK
      tags:
      - Movies
      - Match
  /Movies/MovieCertifications:
    get:
      summary: Returns all Movie Certifications
      description: Returns all Movie Certifications used in a movie response with
        the Releases object.
      operationId: GetMovieCertifications
      x-api-path-slug: moviesmoviecertifications-get
      responses:
        200:
          description: OK
      tags:
      - Movies
      - MovieCertifications
  /Movies/MovieGenres:
    get:
      summary: Returns all Movie Genres.
      description: List of all movie genres used in the API.
      operationId: GetMovieGenres
      x-api-path-slug: moviesmoviegenres-get
      responses:
        200:
          description: OK
      tags:
      - Movies
      - MovieGenres
  /Movies/ReleaseTypes:
    get:
      summary: Returns all Movie ReleaseTypes
      description: 'Release type refers to the release. **EX: Theatrical, Home Video,
        etc.**'
      operationId: GetMovieReleaseTypes
      x-api-path-slug: moviesreleasetypes-get
      responses:
        200:
          description: OK
      tags:
      - Movies
      - ReleaseTypes
  /Movies/SearchAndDiscover:
    get:
      summary: Search and discover movies.
      description: |-
        Searchable Fields:
        Title, AlternateTitles, Genres, OriginalReleaseDate, UnitedStatesReleaseDate, GermanyReleaseDate, FranceReleaseDate, UnitedKingdomReleaseDate, ItalyReleaseDate, JapanReleaseDate, Tags, Cast, Directors, Descriptions, Ratings, OriginalLanguage.
        [Syntax Ref](https://docs.microsoft.com/en-us/rest/api/searchservice/simple-query-syntax-in-azure-search)

        Filterable Fields:
        ID, Title, AlternateTitles, Genres, OriginalReleaseDate, UnitedStatesReleaseDate, GermanyReleaseDate, FranceReleaseDate, UnitedKingdomReleaseDate, ItalyReleaseDate, JapanReleaseDate, Year, Tags, Cast, Directors, Descriptions, HasVideo, PosterFilePath, Ratings, OriginalLanguage, Runtime, Budget, Revenue, Created, Modified.
        [Syntax Ref](https://docs.microsoft.com/en-us/rest/api/searchservice/odata-expression-syntax-for-azure-search)
      operationId: SearchAndDiscoverMovie
      x-api-path-slug: moviessearchanddiscover-get
      parameters:
      - in: query
        name: Filter
        description: Expression to filter results
      - in: query
        name: IncludeTotalResultCount
        description: Includes total results in response
      - in: query
        name: OrderBy
        description: List of field names to sort results
      - in: query
        name: SearchFields
        description: List of field names to search using term
      - in: query
        name: SearchMode
        description: Specifies whether ANY or ALL of the search terms must be matched
          in order to count the item as a match
      - in: query
        name: SelectFields
        description: List of field names to be returned in the object
      - in: query
        name: Skip
        description: Skip number of results
      - in: query
        name: term
        description: Term to search for
      - in: query
        name: Top
        description: Limit results
      responses:
        200:
          description: OK
      tags:
      - Movies
      - SearchAndDiscover
  /Movies/{Id}:
    get:
      summary: Returns movie data for a specific IVA MovieId.
      description: "By default the API will only return basic title information. Additional
        objects can be included by passing the object in the Includes parameter.   \n\n\n`Subscriptions
        with \"Limited\" data will only be able to include basic title information
        and Videos.`"
      operationId: GetMovie
      x-api-path-slug: moviesid-get
      parameters:
      - in: path
        name: Id
        description: Required ID of Movie
      - in: query
        name: Includes
        description: List of additional objects to include in the movie response
      responses:
        200:
          description: OK
      tags:
      - Movies
      - Id
  /TvMedia/genres/movies:
    get:
      summary: ""
      description: Gets list of movie genres.
      operationId: GetTvMediaMovieGenres
      x-api-path-slug: tvmediagenresmovies-get
      parameters:
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Genres
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