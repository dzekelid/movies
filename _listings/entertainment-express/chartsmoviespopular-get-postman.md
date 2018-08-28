{
  "info": {
    "name": "Entertainment Express Returns list of popular movies.",
    "_postman_id": "25a87d80-a17c-41c9-8cf6-320b6d38bc9c",
    "description": "Requires Skip and Take. Maximum page size is 100.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Charts",
      "item": [
        {
          "id": "b5389ac1-48ee-4c65-9aac-7e6e379f00a6",
          "name": "GetChartMoviesBoxoffice",
          "request": {
            "url": "http://ee.iva-api.com/Charts/Movies/Boxoffice?Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns top 10 box office movies."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dab101e9-385b-4c2c-90b2-79aa5a4b0874"
            }
          ]
        },
        {
          "id": "95baed37-8563-488e-b143-cca324fb2f1e",
          "name": "GetChartMoviesMostAnticipated",
          "request": {
            "url": "http://ee.iva-api.com/Charts/Movies/MostAnticipated?Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Requires Skip and Take. Maximum page size is 100."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "10d29072-4836-4552-a126-7b0bb54db29c"
            }
          ]
        },
        {
          "id": "f01036d2-50a4-4a89-8a91-fa2c0d03aaf8",
          "name": "GetChartMoviesPopular",
          "request": {
            "url": "http://ee.iva-api.com/Charts/Movies/Popular?Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Requires Skip and Take. Maximum page size is 100."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "319c2aaf-aef6-4494-bcd0-d89560aaae93"
            }
          ]
        }
      ]
    }
  ]
}