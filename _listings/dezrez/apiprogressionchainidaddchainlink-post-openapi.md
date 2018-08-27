---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Add node to progression chain
  version: 1.0.0
  description: Add node to progression chain.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/progressionchain/{id}/addchainnode:
    post:
      summary: Add node to progression chain
      description: Add node to progression chain.
      operationId: ProgressionChain_AddChainNodesBydataContractByid
      x-api-path-slug: apiprogressionchainidaddchainnode-post
      parameters:
      - in: body
        name: dataContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Node
      - To
      - Progression
      - Chain
  /api/progressionchain/{id}/addchainlink:
    post:
      summary: Add node to progression chain
      description: Add node to progression chain.
      operationId: ProgressionChain_AddChainLinkBydataContractByid
      x-api-path-slug: apiprogressionchainidaddchainlink-post
      parameters:
      - in: body
        name: dataContract
        description: The chain link information
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Node
      - To
      - Progression
      - Chain
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