{
  "info": {
    "name": "Rotten Tomatoes Get Lists Movies Opening",
    "_postman_id": "629a4b19-5989-4c39-8de7-bb6f3b2f7702",
    "description": "Get lists movies opening.json.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Lists",
      "item": [
        {
          "id": "b4ef8ee5-34c3-4b4f-bf04-7a60dace419d",
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
              "id": "49d23025-c9d2-4c68-91ef-5e7bdd630810"
            }
          ]
        },
        {
          "id": "6f732830-33fd-454e-b1eb-768a185224d1",
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
              "id": "c67bc652-c72d-4c4b-a44a-1afff7b3b563"
            }
          ]
        },
        {
          "id": "57c31bed-392a-4db8-b8e4-ae28c1b1020b",
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
              "id": "cdd01adf-9d87-400c-808f-71ba0c2bb225"
            }
          ]
        },
        {
          "id": "5e042362-9a74-4f14-a8f3-14929b650320",
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
              "id": "6cbd8449-3ff8-49b2-a51c-79aba180fff5"
            }
          ]
        },
        {
          "id": "dab1c42c-7e00-4997-8056-0c750523c01a",
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
              "id": "d64409c1-620d-4a6a-a9be-3d09b1e02b15"
            }
          ]
        },
        {
          "id": "6f73a419-fefe-4244-8c99-77cd6f67f5b0",
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
              "id": "6db89c75-0e55-4018-a69b-619991876c01"
            }
          ]
        },
        {
          "id": "970ece57-3beb-479b-a9cc-81626f254fd4",
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
              "id": "5bb786d6-1ffd-4745-bdd9-4f08e9e75646"
            }
          ]
        },
        {
          "id": "b1440b9b-48a1-4ced-b2a4-b8be08541c12",
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
              "id": "e5a74a9c-a784-4130-a180-35109feebfa8"
            }
          ]
        },
        {
          "id": "d3c7a8d3-f553-42e1-bfb6-97ed39770769",
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
              "id": "d43b5677-706f-4eab-b76c-60e0d07ebb57"
            }
          ]
        },
        {
          "id": "bf453259-af1b-4bce-ad2e-57c932812c75",
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
              "id": "ca469ae7-800d-4f28-a59b-087efbd5431b"
            }
          ]
        }
      ]
    }
  ]
}