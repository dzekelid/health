---
swagger: "2.0"
x-collection-name: Tyk
x-complete: 0
info:
  title: Tyk API Management Check Health
  description: Gets the health check values for an API if it is being recorded
  termsOfService: https://tyk.io/terms-and-conditions/
  version: "1.9"
host: '{baseURL}'
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tyk/health/:
    get:
      summary: Check Health
      description: Gets the health check values for an API if it is being recorded
      operationId: gets-the-health-check-values-for-an-api-if-it-is-being-recorded
      x-api-path-slug: tykhealth-get
      parameters:
      - in: query
        name: api_id
        description: API ID to query
      - in: header
        name: x-tyk-authorization
        description: tyk gateway shared secret
      responses:
        200:
          description: OK
      tags:
      - API Health
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---