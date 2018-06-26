{
  "info": {
    "name": "One Note Get Notebooks",
    "_postman_id": "ff84a7a6-af5e-40fc-9022-c38972e658ba",
    "description": "Returns a collection of notebooks.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Notebooks",
      "item": [
        {
          "id": "736df0f5-af5f-4e6d-aec8-442d366f9cc9",
          "name": "getNotebooks",
          "request": {
            "url": "http://www.onenote.com/api/v1.0/me/notes/notebooks?count=%7B%7D&expand=%7B%7D&filter=%7B%7D&orderby=%7B%7D&select=%7B%7D&skip=%7B%7D&top=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of notebooks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0089c71-41bc-48bf-bd71-dac7922b78a1"
            }
          ]
        }
      ]
    }
  ]
}