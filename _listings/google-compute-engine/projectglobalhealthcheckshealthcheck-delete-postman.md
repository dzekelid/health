{
  "info": {
    "name": "Google Compute Engine API Delete Health Check",
    "_postman_id": "4761c2a0-2805-4c0f-82ac-f013ac251abb",
    "description": "Deletes the specified HealthCheck resource.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "checks",
      "item": [
        {
          "id": "9e3b24ca-4a84-4ed8-9134-6d00a113f520",
          "name": "compute.healthChecks.delete",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified HealthCheck resource"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f51e874-e497-4013-85f9-1b4eabff06b0"
            }
          ]
        }
      ]
    }
  ]
}