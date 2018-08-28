{
  "info": {
    "name": "Rotten Tomatoes Get Movies",
    "_postman_id": "949dcae6-5881-4575-b9bc-db4c68abaa38",
    "description": "Get movies .json.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Lists",
      "item": [
        {
          "id": "2bb9e579-4cb4-48e6-94a2-89ed41d5d83a",
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
              "id": "3dcc861a-6259-4b3f-8831-c76cb217aaf7"
            }
          ]
        },
        {
          "id": "f94eec9f-0632-415a-8572-8c190fdf034e",
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
              "id": "c51357db-018e-406d-a3ca-9160b39b1cab"
            }
          ]
        },
        {
          "id": "6bce9430-a753-42bb-87c9-35f08d699986",
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
              "id": "901bbf7b-9329-4480-a216-70d53861da47"
            }
          ]
        },
        {
          "id": "9850d42a-099c-4b4a-b6f8-5acd9b4a1bf3",
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
              "id": "1ea9a648-6680-4bc5-8197-167fd264e455"
            }
          ]
        },
        {
          "id": "7219b1d4-3add-4f43-965e-5a3c8cb689bf",
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
              "id": "fce82a0e-2ea4-4cd5-9b54-e2db23d99d1b"
            }
          ]
        },
        {
          "id": "d21b543f-1eb3-402e-9dfe-11b920bef66c",
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
              "id": "f36816e5-2a71-49aa-bcba-f4682cd02fe9"
            }
          ]
        },
        {
          "id": "61c3dd77-ef82-4d50-b758-d3dfbc58fe50",
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
              "id": "fc270e7a-8dc4-42e9-908a-6c052bb01cb3"
            }
          ]
        },
        {
          "id": "4c0bcf72-8381-498a-bd1e-5ddc0631c639",
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
              "id": "fba2fd93-b56f-4033-a3f3-bd5040a2b431"
            }
          ]
        },
        {
          "id": "2ae7246c-ca8b-4f66-901c-a085d40f50af",
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
              "id": "55ddd0aa-0ad3-47cc-93f5-9182b9ed4031"
            }
          ]
        },
        {
          "id": "413122cd-682d-48bb-b506-3f95b5b0c0d7",
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
              "id": "ed872cf2-ebd0-47fa-9a1d-4aeca4343300"
            }
          ]
        },
        {
          "id": "35eb9ee4-48fe-417c-b4e8-e1f45f61faf4",
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
              "id": "db68e704-7737-4d1d-840e-a78506d9bd84"
            }
          ]
        }
      ]
    },
    {
      "name": "Movie",
      "item": [
        {
          "id": "6c6e57e9-efc2-4b41-b9be-b01dc1d34c22",
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
              "id": "a6f90b2c-6716-47eb-8f17-d485ec15f555"
            }
          ]
        }
      ]
    },
    {
      "name": "Movies",
      "item": [
        {
          "id": "dc4b5f3f-11c5-4ac7-ae12-693f79cd539e",
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
              "id": "43b04b47-9568-428f-bec1-c080dcf0ac5f"
            }
          ]
        },
        {
          "id": "79fba7e6-f4cf-4bca-b827-8e7179fb990c",
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
              "id": "ef6265f4-63d4-4be6-88d4-70a6332e368b"
            }
          ]
        }
      ]
    }
  ]
}