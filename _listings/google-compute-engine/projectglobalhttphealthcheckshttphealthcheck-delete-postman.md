{
  "info": {
    "name": "Google Compute Engine API Delete HTTP Health Check",
    "_postman_id": "97ea60c3-4349-4314-8b85-6caec10b1b17",
    "description": "Deletes the specified HttpHealthCheck resource.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "checks",
      "item": [
        {
          "id": "1915c58c-b8f0-442a-bae3-13950e35eb37",
          "name": "compute.httpHealthChecks.delete",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified HttpHealthCheck resource"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd8005f9-96c3-46d0-9e97-f97588028756"
            }
          ]
        }
      ]
    }
  ]
}