{
  "info": {
    "name": "Rotten Tomatoes Get Movies Clips",
    "_postman_id": "259b7c6b-59fa-462c-a183-c65e92390b0d",
    "description": "Get movies clips.json.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Lists",
      "item": [
        {
          "id": "77b29b2a-80a6-4c8a-9b74-4044ed1defca",
          "name": "getLists.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/lists.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get lists.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b0faee8-7608-4c57-9b4f-17db60bd6d66"
            }
          ]
        },
        {
          "id": "36ef1d5f-4351-4665-9926-eb9712a88330",
          "name": "getListsDvds.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/lists/dvds.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get lists dvds.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d49a770b-5203-48cd-a121-ae935ce840ac"
            }
          ]
        },
        {
          "id": "3fbf3fa1-e9be-4f55-914a-0f391b97eb5f",
          "name": "getListsDvdsCurrentReleases.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/lists/dvds/current_releases.json?country=%7B%7D&page=%7B%7D&page_limit=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get lists dvds current releases.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "557c8865-645e-4aca-b51e-447b41d83c85"
            }
          ]
        },
        {
          "id": "f29ee3d4-19a2-4d91-ae70-bd4c50147b63",
          "name": "getListsDvdsNewReleases.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/lists/dvds/new_releases.json?country=%7B%7D&page=%7B%7D&page_limit=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get lists dvds new releases.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f27ce058-74e3-4e4b-9416-a02bb722340b"
            }
          ]
        },
        {
          "id": "4cf92561-afd9-42fe-9c07-a74195db4371",
          "name": "getListsDvdsTopRentals.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/lists/dvds/top_rentals.json?country=%7B%7D&limit=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get lists dvds top rentals.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "73c6b7f1-a1ed-4444-8d99-d11ad9bfedf4"
            }
          ]
        },
        {
          "id": "505eb822-9ef8-4a73-b326-56964f64dd09",
          "name": "getListsDvdsUpcoming.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/lists/dvds/upcoming.json?country=%7B%7D&page=%7B%7D&page_limit=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get lists dvds upcoming.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7e192f8c-fd23-4c07-bf31-7b326a309105"
            }
          ]
        },
        {
          "id": "7790b45c-95f4-4f78-a1c8-a4021eb9e271",
          "name": "getListsMovies.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/lists/movies.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get lists movies.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a3ba6f6f-ee9f-4fbb-be3b-52cf7857228a"
            }
          ]
        },
        {
          "id": "3ee2a210-ee42-423b-ad9a-ec5162c46aa4",
          "name": "getListsMoviesBoxOffice.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/lists/movies/box_office.json?country=%7B%7D&limit=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get lists movies box office.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4d4acf1a-f1f1-4713-86f7-a3ca057869de"
            }
          ]
        },
        {
          "id": "34ac9cc1-dd01-40b1-940b-2661cebe7cc3",
          "name": "getListsMoviesInTheaters.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/lists/movies/in_theaters.json?country=%7B%7D&page=%7B%7D&page_limit=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get lists movies in theaters.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0bb957a-fa1b-48fc-8ac9-790b5c775d98"
            }
          ]
        },
        {
          "id": "75352a43-2c23-44f0-81a4-4e3d6978881f",
          "name": "getListsMoviesOpening.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/lists/movies/opening.json?country=%7B%7D&limit=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get lists movies opening.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9c0dc53d-b883-4f7b-8d81-e17fe4b1820a"
            }
          ]
        },
        {
          "id": "70705a16-877f-4cc5-983e-2be7fe5d7539",
          "name": "getListsMoviesUpcoming.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/lists/movies/upcoming.json?country=%7B%7D&page=%7B%7D&page_limit=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get lists movies upcoming.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c0bfd03-e0fe-494e-83a6-60f01e73b692"
            }
          ]
        }
      ]
    },
    {
      "name": "Movie",
      "item": [
        {
          "id": "fa399ea8-db30-4cc8-9065-c3defccdf208",
          "name": "getMovieAlias.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/movie_alias.json?id=%7B%7D&type=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get movie alias.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d930f32-3cd8-484b-9463-a55d0e34a1f5"
            }
          ]
        }
      ]
    },
    {
      "name": "Movies",
      "item": [
        {
          "id": "a82c4b5e-7b09-4686-9497-95dded4be83c",
          "name": "getMovies.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/movies.json?page=%7B%7D&page_limit=%7B%7D&q=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get movies.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "48bd9348-1112-4d4f-bd7d-985c393904c2"
            }
          ]
        },
        {
          "id": "7a3a3bc0-62ed-4558-80d7-c63ac5504432",
          "name": "getMovies.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.rottentomatoes.com",
              "path": [
                "api",
                "public",
                "v1.0",
                "movies/:id.json"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get movies .json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a5a10778-f7ce-412f-8b27-41978f311144"
            }
          ]
        },
        {
          "id": "13a3e33f-841f-4d86-9268-1c58a48976d2",
          "name": "getMoviesCast.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.rottentomatoes.com",
              "path": [
                "api",
                "public",
                "v1.0",
                "movies/:id/cast.json"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get movies cast.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "689b41dd-048f-4427-84a2-e3447758fdc4"
            }
          ]
        },
        {
          "id": "5ca81e5f-c41e-4995-a036-5fd07239086e",
          "name": "getMoviesClips.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.rottentomatoes.com",
              "path": [
                "api",
                "public",
                "v1.0",
                "movies/:id/clips.json"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get movies clips.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bf852b7d-a2cf-4cb8-a1f3-109ac626f2a7"
            }
          ]
        }
      ]
    }
  ]
}