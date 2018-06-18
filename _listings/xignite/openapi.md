---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite Historical
  description: this-web-service-provides-historical-security-pricing-for-us-equities-
  version: 1.0.0
host: www.xignite.com
basePath: xHistorical.json/XigniteHistorical
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetAdvancesAndDeclines:
    get:
      summary: Get Advances And Declines
      description: Returns numbers of advancing and declining stocks by price and
        volume across exchanges. For more information, go to http://www.xignite.com/
      operationId: postGetadvancesanddeclines
      x-api-path-slug: getadvancesanddeclines-get
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
      - Advances
      - Declines
---