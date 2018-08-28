{
  "info": {
    "name": "Rotten Tomatoes Get Lists Movies",
    "_postman_id": "a0f55c64-2267-44f9-9b2c-0b2db5345866",
    "description": "Get lists movies.json.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Lists",
      "item": [
        {
          "id": "5b0b20de-2786-41cc-9dd1-c7bae80de974",
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
              "id": "76016a20-a1f4-4f8d-9ecd-abbbd6bf28ce"
            }
          ]
        },
        {
          "id": "304dc026-5719-45bb-a139-746481045407",
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
              "id": "823aa939-2651-440e-9b92-e87ae735a810"
            }
          ]
        },
        {
          "id": "4bea8280-8c6f-4605-b6e2-1abde5ae9e49",
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
              "id": "c27f3761-51cd-42c6-a376-e76e0375ab55"
            }
          ]
        },
        {
          "id": "2c7f26c8-d32e-424a-9c14-4e3fd502618c",
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
              "id": "c5151647-d1c9-4fa0-a7bf-c664b87c37e2"
            }
          ]
        },
        {
          "id": "5ee91a9e-147e-4f40-92a5-a8660f3c21fb",
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
              "id": "73275a74-9b94-4b9b-ae51-9d28c2eff760"
            }
          ]
        },
        {
          "id": "83863b50-1690-499c-be87-a36670932c91",
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
              "id": "49bee07d-6710-4fe3-8a54-a4dd1ef45b92"
            }
          ]
        },
        {
          "id": "7d0abf15-02ba-4f52-acf1-8be40e09695e",
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
              "id": "615a517d-7f94-4f20-8b1a-5c3f2cf730ee"
            }
          ]
        }
      ]
    }
  ]
}