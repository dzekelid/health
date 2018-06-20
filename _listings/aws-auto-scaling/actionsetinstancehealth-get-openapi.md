---
swagger: "2.0"
x-collection-name: AWS Auto Scaling
x-complete: 0
info:
  title: AWS Auto Scaling API Set Instance Health
  version: 1.0.0
  description: Sets the health status of the specified instance.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=SetInstanceHealth:
    get:
      summary: Set Instance Health
      description: Sets the health status of the specified instance.
      operationId: setInstanceHealth
      x-api-path-slug: actionsetinstancehealth-get
      parameters:
      - in: query
        name: HealthStatus
        description: The health status of the instance
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      - in: query
        name: ShouldRespectGracePeriod
        description: If the Auto Scaling group of the specified instance has a HealthCheckGracePeriod             specified
          for the group, by default, this call will respect the grace period
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instance Health
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