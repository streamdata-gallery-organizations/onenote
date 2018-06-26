{
  "info": {
    "name": "One Note Get Notebooks Notebookid",
    "_postman_id": "1e5553b0-d42b-422e-b736-e890d20ad2e8",
    "description": "Returns a specific notebook object.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Notebooks",
      "item": [
        {
          "id": "4a2dbd2b-ca27-4a66-afdc-aedacd2cfc8f",
          "name": "getNotebooksNotebook",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.onenote.com",
              "path": [
                "api",
                "v1.0",
                "me",
                "notes",
                "notebooks/:notebookId"
              ],
              "query": [
                {
                  "key": "expand",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "select",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "notebookId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a specific notebook object."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "63afeb5b-29aa-48c7-9bbd-e6d7987f3756"
            }
          ]
        }
      ]
    }
  ]
}