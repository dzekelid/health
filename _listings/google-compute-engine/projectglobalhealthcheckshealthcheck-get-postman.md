{
  "info": {
    "name": "Google Compute Engine API Get Health Check",
    "_postman_id": "26a5378d-a1be-490e-a038-89e4cad16d1c",
    "description": "Returns the specified HealthCheck resource. Get a list of available health checks by making a list() request.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "checks",
      "item": [
        {
          "id": "0e33f4ba-6dbe-4938-b692-457910ce0ab5",
          "name": "compute.healthChecks.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "compute",
                "v1",
                "projects",
                ":project/global/healthChecks/:healthCheck"
              ],
              "variable": [
                {
                  "id": "healthCheck",
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
            "description": "Returns the specified HealthCheck resource"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2ed08d4f-a2c2-4727-8a21-2c4c8640b392"
            }
          ]
        }
      ]
    }
  ]
}