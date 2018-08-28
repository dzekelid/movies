{
  "info": {
    "name": "Entertainment Express Returns list of Most Anticipated movies based on IVA data.",
    "_postman_id": "f27d2d87-d3fb-4de7-bfdc-b13584f2f2b9",
    "description": "Requires Skip and Take. Maximum page size is 100.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Charts",
      "item": [
        {
          "id": "e162eedd-7834-423f-884c-dc2c4fd1514a",
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
              "id": "a46771d9-7b90-41d9-8480-23aaebed12fa"
            }
          ]
        },
        {
          "id": "5b435bd4-c683-4867-b563-f608702a1f2e",
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
              "id": "bafd21ec-b4d2-438c-8c73-97d11a16df3d"
            }
          ]
        }
      ]
    }
  ]
}