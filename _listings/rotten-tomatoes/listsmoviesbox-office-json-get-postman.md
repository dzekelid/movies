{
  "info": {
    "name": "Rotten Tomatoes Get Lists Movies Box Office",
    "_postman_id": "25f90d9e-ccee-4da4-b5dc-b9269a5501cf",
    "description": "Get lists movies box office.json.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Lists",
      "item": [
        {
          "id": "af1b7a23-a3cd-4a75-bf8e-146fa1a7579d",
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
              "id": "71c3cb20-58f6-47ae-bca0-2adfc42d7412"
            }
          ]
        },
        {
          "id": "e013831d-4212-4e41-83ca-a6aa5ea3feef",
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
              "id": "20c2c4af-0224-4e07-83c7-b6d4221ae41b"
            }
          ]
        },
        {
          "id": "75ea1c12-5245-4b2c-b5bb-200ac4dcd2ae",
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
              "id": "d6ead071-ce51-4378-b2dd-e107412a3ae5"
            }
          ]
        },
        {
          "id": "a179dd8a-10cd-4f9c-9706-db91246021c4",
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
              "id": "5e0dd90e-4dbc-4104-972d-90eb4c5d4a81"
            }
          ]
        },
        {
          "id": "6602a153-e2a4-49d4-9807-2d281a5fa612",
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
              "id": "733e0a3d-26a8-4651-a4bd-ddeebd8837c9"
            }
          ]
        },
        {
          "id": "410f4e58-22f4-4c89-9550-a76653faa549",
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
              "id": "bb468ccc-a79b-47d6-b399-0af1c3bf33a6"
            }
          ]
        },
        {
          "id": "2e3c7015-b21b-4318-a437-c9d22e4264f2",
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
              "id": "d0b55e3b-7490-4d33-a2e7-98d5a4bf033c"
            }
          ]
        },
        {
          "id": "a8efd449-7b91-4ad9-b654-f33beda2aafa",
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
              "id": "491ec97c-a872-4bb6-87b8-7c809aa3d36e"
            }
          ]
        }
      ]
    }
  ]
}