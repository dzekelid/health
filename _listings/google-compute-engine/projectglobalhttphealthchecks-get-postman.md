{
  "info": {
    "name": "Google Compute Engine API Get HTTP Health Checks",
    "_postman_id": "eda19029-7195-4978-8736-69b6cad1bc34",
    "description": "Retrieves the list of HttpHealthCheck resources available to the specified project.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "checks",
      "item": [
        {
          "id": "7fb9e13f-1b88-40d3-92a6-4da1d6a4a05a",
          "name": "compute.httpHealthChecks.list",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "compute",
                "v1",
                "projects",
                ":project/global/httpHealthChecks"
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
            "description": "Retrieves the list of HttpHealthCheck resources available to the specified project"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "48d5eb85-68a8-423c-a236-162584096569"
            }
          ]
        }
      ]
    }
  ]
}