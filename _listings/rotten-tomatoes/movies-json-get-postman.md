{
  "info": {
    "name": "Rotten Tomatoes Get Movies",
    "_postman_id": "d6b6d071-1de2-450c-970d-2b28b368a1e8",
    "description": "Get movies.json.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Lists",
      "item": [
        {
          "id": "1823d80e-9256-4218-a414-bc80cfa71874",
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
              "id": "53d062e0-3ff1-48a2-8c2e-d449a35df521"
            }
          ]
        },
        {
          "id": "030714ff-fd2b-4c22-97c6-87af52092353",
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
              "id": "2ace2c5f-b2a7-4793-b31d-03a1478a2589"
            }
          ]
        },
        {
          "id": "1fa7371a-239d-4e48-9721-a4a207639908",
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
              "id": "82172d8e-2eb7-49c4-b59c-7c03cff1bc5d"
            }
          ]
        },
        {
          "id": "66de17d3-c615-4541-82ed-767fc05203e0",
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
              "id": "e05579cd-a68b-4c11-8b00-20f2e6a56cf9"
            }
          ]
        },
        {
          "id": "ce93ea4e-b3c1-49c4-ae13-d88bbebef527",
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
              "id": "b762fb19-3c81-4b00-b79f-e5b98ad0b347"
            }
          ]
        },
        {
          "id": "585dca51-5671-40b2-b457-96662482f1c0",
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
              "id": "323329fe-817f-4ceb-887c-6fda5f60bbe6"
            }
          ]
        },
        {
          "id": "8531fb71-33c7-46f8-80b1-99586d4bf47f",
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
              "id": "17b9e49b-0ca6-4b66-b2a9-24b3cc9ed2de"
            }
          ]
        },
        {
          "id": "3eb464e4-4697-4261-8daf-f0fbacc064e0",
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
              "id": "f088b433-a410-4164-b295-ef8ffb7cfa99"
            }
          ]
        },
        {
          "id": "af900260-8e1c-4608-9bc6-bb9947862e4d",
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
              "id": "42194585-3884-4862-b635-bc86af613f76"
            }
          ]
        },
        {
          "id": "e779d220-1953-4e67-93e6-969cb63c888c",
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
              "id": "3448a81e-c513-4303-afba-98fe6090d618"
            }
          ]
        },
        {
          "id": "98ea29fb-725e-4b0a-94e0-c9331714a852",
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
              "id": "8db5eb86-b41e-4c2a-8238-e201705fa63e"
            }
          ]
        }
      ]
    },
    {
      "name": "Movie",
      "item": [
        {
          "id": "d288682f-cf7a-43b6-b255-7480caf3d8b9",
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
              "id": "08bfb1db-1ebe-413d-8865-4a39f6851bc4"
            }
          ]
        }
      ]
    },
    {
      "name": "Movies",
      "item": [
        {
          "id": "61d83e94-40fb-475b-98fe-78a9783250f3",
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
              "id": "c61e6df2-678e-4e79-997c-31d8a88a0873"
            }
          ]
        }
      ]
    }
  ]
}