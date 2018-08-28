{
  "info": {
    "name": "Entertainment Express Returns list of movies based on the weekend box office revenue.",
    "_postman_id": "77cafacd-506e-40ad-9b14-fe553485d8d7",
    "description": "Returns top 10 box office movies.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Charts",
      "item": [
        {
          "id": "35a54de2-e407-40e6-9cfc-5ec43d4eeb37",
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
              "id": "f3160c95-098d-4578-b459-78ebe4b0c3e5"
            }
          ]
        }
      ]
    }
  ]
}