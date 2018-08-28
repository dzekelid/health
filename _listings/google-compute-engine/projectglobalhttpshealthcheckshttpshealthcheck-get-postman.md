{
  "info": {
    "name": "Google Compute Engine API Get HTTPS Health Check",
    "_postman_id": "3f33e6be-e1d4-4c53-b0a7-22c124d6699f",
    "description": "Returns the specified HttpsHealthCheck resource. Get a list of available HTTPS health checks by making a list() request.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "checks",
      "item": [
        {
          "id": "dcc847fa-d1e3-4af1-a4ea-8724afd11ee6",
          "name": "compute.httpsHealthChecks.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "compute",
                "v1",
                "projects",
                ":project/global/httpsHealthChecks/:httpsHealthCheck"
              ],
              "variable": [
                {
                  "id": "httpsHealthCheck",
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
            "description": "Returns the specified HttpsHealthCheck resource"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "26aca611-31cd-4ade-a5b6-fc13276d28c5"
            }
          ]
        }
      ]
    }
  ]
}