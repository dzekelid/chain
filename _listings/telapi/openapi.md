swagger: "2.0"
x-collection-name: TelAPI
x-complete: 1
info:
  title: TelAPI
  description: telapi-is-a-rest-api--what-that-means-for-you-is-that-interacting-with-telapi-to-perform-all-of-your-telephony-needs-is-almost-as-simple-as-visiting-a-website--deeper-knowledge-regarding-rest-is-useful-when-developing-with-telapi-but-definitely-not-required--we-aim-to-provide-all-of-the-information-needed-for-working-with-our-rest-api-throughout-its-documentation-provided-here-so-even-if-you-are-new-to-rest-telapi-will-still-be-a-pleasure-to-use-
  termsOfService: http://www.telapi.com/legal/tos
  version: v2
host: api.telapi.com
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/hotel/v0/hotels:
    get:
      summary: Get a list of all the hotels of a chain your application has access
        to.
      description: Get a list of all the hotels of a chain your application has access
        to..
      operationId: Hotels_GetHotels
      x-api-path-slug: apihotelv0hotels-get
      parameters:
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      responses:
        200:
          description: OK
      tags:
      - ""
      - Hotels
      - Of
      - Chain
      - Your
      - Application
      - Has
      - Access
      - To