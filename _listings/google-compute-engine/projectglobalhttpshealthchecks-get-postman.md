{
  "info": {
    "name": "Google Compute Engine API Get HTTPS Health Checks",
    "_postman_id": "aabfb537-c271-43b7-91ff-ce4bdd5ead98",
    "description": "Retrieves the list of HttpsHealthCheck resources available to the specified project.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "checks",
      "item": [
        {
          "id": "9605c1fc-0dd3-405d-bfad-920ee2991297",
          "name": "compute.httpsHealthChecks.list",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "compute",
                "v1",
                "projects",
                ":project/global/httpsHealthChecks"
              ],
              "query": [
                {
                  "key": "filter",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "maxResults",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "orderBy",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pageToken",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "project",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the list of HttpsHealthCheck resources available to the specified project"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fcd86546-29c3-42b9-82d7-1482f4a72070"
            }
          ]
        }
      ]
    }
  ]
}