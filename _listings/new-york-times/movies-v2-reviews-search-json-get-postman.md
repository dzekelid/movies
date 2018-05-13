{
  "info": {
    "name": "New York Times Move Review Search",
    "_postman_id": "55fcb4f0-9939-4def-823d-99d4eb93f87a",
    "description": "With the Movie Reviews API, you can search New York Times movie reviews by keyword and get lists of NYT Critics' Picks.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "movies",
      "item": [
        {
          "id": "27e8aa78-f6db-432e-8f0d-57b6b1d26123",
          "name": "getMoveReviews",
          "request": {
            "url": "http://api.nytimes.com/svc/movies/v2/reviews/search.json?critics-pick=%7B%7D&offset=%7B%7D&opening-date=%7B%7D&order=%7B%7D&publication-date=%7B%7D&query=%7B%7D&reviewer=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "With the Movie Reviews API, you can search New York Times movie reviews by keyword and get lists of NYT Critics' Picks"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "08a8361e-6e9c-4f12-8157-4e457591301d"
            }
          ]
        }
      ]
    }
  ]
}