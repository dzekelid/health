{
  "info": {
    "name": "Google Compute Engine API Create HTTP Health Check",
    "_postman_id": "6a7b8c2f-ce92-425f-91eb-e3f92d1016e9",
    "description": "Returns the specified HttpHealthCheck resource. Get a list of available HTTP health checks by making a list() request.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "checks",
      "item": [
        {
          "id": "3a636eb1-bde5-493a-90ec-2de705a9348b",
          "name": "compute.httpHealthChecks.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "compute",
                "v1",
                "projects",
                ":project/global/httpHealthChecks/:httpHealthCheck"
              ],
              "variable": [
                {
                  "id": "httpHealthCheck",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Returns the specified HttpHealthCheck resource"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0529a38a-37c7-433f-8d7c-cc0e5276db71"
            }
          ]
        }
      ]
    }
  ]
}