---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Global Option Master Get Option Chain
  description: Get the option chain for the underlying instrument.
  version: 1.0.0
host: globaloptionmaster.xignite.com
basePath: xGlobalOptionMaster.json/XigniteGlobalOptionMaster
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetFutureOptionChain:
    get:
      summary: Get Future Option Chain
      description: Returns an option chain for a future contract.
      operationId: postGetfutureoptionchain
      x-api-path-slug: getfutureoptionchain-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Future
      - Option
      - Chain
  /ListFutureChain:
    get:
      summary: List Future Chain
      description: Returns a list of future contracts on a base future symbol
      operationId: ListFutureChain
      x-api-path-slug: listfuturechain-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - List
      - Future
      - Chain
  /ListOptionChain:
    get:
      summary: List Option Chain
      description: Returns a list of options on a future contract
      operationId: ListOptionChain
      x-api-path-slug: listoptionchain-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - List
      - Option
      - Chain
  /GetOptionChain:
    get:
      summary: Get Option Chain
      description: Get the option chain for the underlying instrument.
      operationId: GetOptionChain
      x-api-path-slug: getoptionchain-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Option
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