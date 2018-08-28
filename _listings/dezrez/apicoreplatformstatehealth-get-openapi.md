---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Gets core platform master health status
  version: 1.0.0
  description: Gets core platform master health status.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/coreplatformstate/health:
    get:
      summary: Gets core platform master health status
      description: Gets core platform master health status.
      operationId: CorePlatformState_GetPlatformHealth
      x-api-path-slug: apicoreplatformstatehealth-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Core
      - Platform
      - Master
      - Health
      - Status
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