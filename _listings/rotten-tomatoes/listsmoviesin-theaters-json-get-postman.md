{
  "info": {
    "name": "Rotten Tomatoes Get Lists Movies In Theaters",
    "_postman_id": "b03f5322-0131-4d90-8493-8c152e18d171",
    "description": "Get lists movies in theaters.json.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Lists",
      "item": [
        {
          "id": "ab71cca9-0cb8-4ae1-96f2-823fb98f61bc",
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
              "id": "05c5a8aa-6f62-4ae9-925d-373bce730b1d"
            }
          ]
        },
        {
          "id": "d8a5fddb-d2f3-4069-80a3-0f6b9466ae34",
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
              "id": "81741a82-7353-4ff4-98fe-db8d82cd3c7d"
            }
          ]
        },
        {
          "id": "bae997a5-6686-4ed4-be37-8f2ce4071e86",
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
              "id": "36706e70-fc2e-46c1-b522-361be019a435"
            }
          ]
        },
        {
          "id": "0690c922-490a-42c2-91e6-f9088830af93",
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
              "id": "6fdb6d92-bcb2-4f65-a9a4-b8910cbd1c76"
            }
          ]
        },
        {
          "id": "4e912d76-44bf-4f48-b100-a7c2531ef78a",
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
              "id": "8540f8c0-2b2a-48c3-bb89-a711d643cdb6"
            }
          ]
        },
        {
          "id": "0ce3e699-ed93-4dd6-86ac-ab0e947df923",
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
              "id": "ee574360-718c-4b9f-a418-a872d5f4ae01"
            }
          ]
        },
        {
          "id": "104acfa6-41a5-4765-8e6a-257dfb85cab7",
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
              "id": "80e6b019-4c51-44d3-bf48-d87f3fc7103f"
            }
          ]
        },
        {
          "id": "e12f9c2d-d216-426c-ae06-7f851406e673",
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
              "id": "c1800bf8-dbb7-4614-b264-961f0ec2f66c"
            }
          ]
        },
        {
          "id": "03d1cbf6-24e5-46b8-a8cb-8ec76934eebe",
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
              "id": "d0169ecf-5569-4f15-a576-a8ad6a115289"
            }
          ]
        }
      ]
    }
  ]
}