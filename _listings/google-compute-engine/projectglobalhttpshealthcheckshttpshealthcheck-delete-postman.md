{
  "info": {
    "name": "Google Compute Engine API Delete HTTPS Health Check",
    "_postman_id": "b2ba17e4-4d84-4d32-bbc6-8485f057e7ff",
    "description": "Deletes the specified HttpsHealthCheck resource.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "checks",
      "item": [
        {
          "id": "60026bb6-7226-44f1-b523-830a0dcd432c",
          "name": "compute.httpsHealthChecks.delete",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified HttpsHealthCheck resource"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7bfa1b86-6cd8-46e0-95a4-590c75257158"
            }
          ]
        }
      ]
    }
  ]
}