---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
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
---