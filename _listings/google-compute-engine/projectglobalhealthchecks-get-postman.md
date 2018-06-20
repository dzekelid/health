{
  "info": {
    "name": "Google Compute Engine API Get Health Checks",
    "_postman_id": "91dcc663-769d-4f7f-8af1-961c35f89c8e",
    "description": "Retrieves the list of HealthCheck resources available to the specified project.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "checks",
      "item": [
        {
          "id": "af469434-9949-42f5-9f97-0e0795f81187",
          "name": "compute.healthChecks.list",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "compute",
                "v1",
                "projects",
                ":project/global/healthChecks"
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
            "description": "Retrieves the list of HealthCheck resources available to the specified project"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e514f07d-9e52-4ecc-808b-8e0d1d778ae8"
            }
          ]
        }
      ]
    }
  ]
}