{
  "info": {
    "name": "Rotten Tomatoes Get Movies Cast",
    "_postman_id": "b19136a7-5de6-4e98-b7a4-ebf9f28915f9",
    "description": "Get movies cast.json.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Lists",
      "item": [
        {
          "id": "e5f2dd26-a2f4-4406-80ff-52dce742aee1",
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
              "id": "afbdafbc-beba-4975-b19b-17941c40a4b3"
            }
          ]
        },
        {
          "id": "1a4b75ff-74ae-4b97-a535-92046401567c",
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
              "id": "2eb8b604-104a-43c6-8a73-b682592a414f"
            }
          ]
        },
        {
          "id": "a902eab6-348e-45b9-b6b4-040d7c72c209",
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
              "id": "ccc1b3ac-0630-4308-bdbf-798abb6b4ff3"
            }
          ]
        },
        {
          "id": "bdeece73-a5ff-4f15-b0f8-82de204a2074",
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
              "id": "32967ee6-5090-4fa5-bf36-25e3feea68ec"
            }
          ]
        },
        {
          "id": "90798545-c8ef-4509-812b-3b8af56bdb55",
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
              "id": "c362304a-6609-4325-9917-5865e3567f34"
            }
          ]
        },
        {
          "id": "ff551c3a-a0bf-48cc-b9ab-1d4687be89b7",
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
              "id": "b9aa6398-380e-41ed-810d-62a770eef97a"
            }
          ]
        },
        {
          "id": "30f511e1-8733-4b45-98c2-c7b64aeb81f8",
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
              "id": "b14a7e10-5885-46d8-a7c6-995cf66cdae4"
            }
          ]
        },
        {
          "id": "36e4dd63-b706-4b10-aef9-985e33db17e2",
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
              "id": "3d684f29-6bce-4184-83ca-653cc7b2c096"
            }
          ]
        },
        {
          "id": "a43d571f-ceff-4dbe-9b5d-1c44dd7747ed",
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
              "id": "e140fc86-d90a-4a29-b85e-b814025f2b7b"
            }
          ]
        },
        {
          "id": "69cf5cac-7892-41e5-8995-dd41393a1188",
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
              "id": "2e9c4b49-e4ce-4a7c-b8a9-22b448fcf434"
            }
          ]
        },
        {
          "id": "da29c959-efa8-408c-9af3-8b4d9a65c41a",
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
              "id": "3b5eaaa5-359b-4f2e-b2c2-33ef89a831b7"
            }
          ]
        }
      ]
    },
    {
      "name": "Movie",
      "item": [
        {
          "id": "c543600b-4340-4e5d-9d3d-bc022959e15b",
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
              "id": "3f648aa6-766e-4ddd-8abd-7b9f4ec4a54a"
            }
          ]
        }
      ]
    },
    {
      "name": "Movies",
      "item": [
        {
          "id": "fb0eba86-aab6-4ced-a931-0645b439e280",
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
              "id": "7520064f-41f7-4855-82cb-607f165434f5"
            }
          ]
        },
        {
          "id": "18c533c8-a4e2-41a4-b8bf-4ab56a726886",
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
              "id": "a41241b1-2ae4-4353-a155-634dbf8e8850"
            }
          ]
        },
        {
          "id": "4d42ca94-7741-46b8-b225-5929101d946d",
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
              "id": "f6748a61-88c0-417d-882d-5d6413e6ceaa"
            }
          ]
        }
      ]
    }
  ]
}