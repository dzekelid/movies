{
  "info": {
    "name": "Rotten Tomatoes Get Movies Reviews",
    "_postman_id": "c5451477-2101-41c5-9aca-23828a4e649c",
    "description": "Get movies reviews.json.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Movies",
      "item": [
        {
          "id": "00348e8d-f833-4856-b805-f7070a195eed",
          "name": "getMoviesReviews.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.rottentomatoes.com",
              "path": [
                "api",
                "public",
                "v1.0",
                "movies/:id/reviews.json"
              ],
              "query": [
                {
                  "key": "country",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page_limit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "review_type",
                  "value": "%7B%7D",
                  "disabled": false
                }
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
            "description": "Get movies reviews.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2ffae7b5-5703-497d-8e51-5ff561ec5c15"
            }
          ]
        }
      ]
    }
  ]
}