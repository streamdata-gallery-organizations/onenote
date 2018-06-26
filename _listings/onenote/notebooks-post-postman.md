{
  "info": {
    "name": "One Note Post Notebooks",
    "_postman_id": "c21e0e2b-7316-4b0d-91f3-4a80dbca0e00",
    "description": "Creates a new notebook.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Notebooks",
      "item": [
        {
          "id": "d032ca8d-c088-416e-bb7b-32ebad3118b7",
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
              "id": "f810d184-e665-4efb-a601-009350d4e9ae"
            }
          ]
        },
        {
          "id": "ce364a94-de2d-4964-92e2-93ab22b2c1c7",
          "name": "postNotebooks",
          "request": {
            "url": "http://www.onenote.com/api/v1.0/me/notes/notebooks",
            "method": "POST",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "Required: indicates type of content being sent",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new notebook."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77b617c9-58d5-4594-b94a-cb091f783e2c"
            }
          ]
        }
      ]
    }
  ]
}