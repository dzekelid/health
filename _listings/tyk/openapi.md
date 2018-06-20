---
swagger: "2.0"
x-collection-name: Tyk
x-complete: 1
info:
  title: Tyk Gateway REST API
  description: the-api-for-managing-the-tyk-api-management-gateway-allowing-api-control-over-the-operation-of-a-variety-of-apis-
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
---