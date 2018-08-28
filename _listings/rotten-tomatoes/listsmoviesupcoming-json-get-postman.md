{
  "info": {
    "name": "Rotten Tomatoes Get Lists Movies Upcoming",
    "_postman_id": "0779a78e-e2d7-489e-b319-a8b0105e33b2",
    "description": "Get lists movies upcoming.json.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Lists",
      "item": [
        {
          "id": "197316df-dd6c-4542-afe7-da1190546fc9",
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
              "id": "2a2922a4-2b80-46c5-8a9f-00577cd93d94"
            }
          ]
        },
        {
          "id": "fcfee56f-fb15-4676-96f4-c360647fc49b",
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
              "id": "019ed1c1-b2ff-401f-a5c8-3238bb8b2434"
            }
          ]
        },
        {
          "id": "5ddc93ef-98e6-4ca4-96e4-babdd45d77eb",
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
              "id": "ce29665c-18d5-4be9-8915-8f13309925f2"
            }
          ]
        },
        {
          "id": "1c2d6bfb-006c-4f22-98c3-6d857983ac8b",
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
              "id": "e474585e-de7a-4e0b-bacc-81e92b012d42"
            }
          ]
        },
        {
          "id": "135da1aa-d399-430b-8881-dd6e5bf7e401",
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
              "id": "6baa3e51-a99c-4959-bd1c-c1b198c679f4"
            }
          ]
        },
        {
          "id": "e3fdcc4f-1d88-4d6d-ba9e-76d6aead8c8d",
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
              "id": "ff26e237-942d-45bb-a68a-8b74452d437c"
            }
          ]
        },
        {
          "id": "650f2725-8a0c-40df-934a-547c017c7d84",
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
              "id": "3ae13f65-c132-4496-bba2-8c5562ca4c3c"
            }
          ]
        },
        {
          "id": "ca9c32ec-1fa0-4985-8997-7f071ae36fa5",
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
              "id": "b73c4481-675d-42af-a8d1-d6cfdd54a2bf"
            }
          ]
        },
        {
          "id": "2f805963-049a-4c46-bbb6-a920e27f1ed3",
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
              "id": "b9672af3-e0d0-4518-8d9e-e3ddd9c2214d"
            }
          ]
        },
        {
          "id": "602d6476-ebae-4e9e-9c1f-b05b00048264",
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
              "id": "b6246944-fc50-4835-861a-c2fbe755a3ef"
            }
          ]
        },
        {
          "id": "9b44e255-8f80-4977-863d-98403fd4be99",
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
              "id": "0744c035-8ec3-4f93-866e-c5688c93b393"
            }
          ]
        }
      ]
    }
  ]
}