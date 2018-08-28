swagger: "2.0"
x-collection-name: Reverb
x-complete: 1
info:
  title: reverb
  description: reverb
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /my/negotiations/{id}/decline:
    post:
      summary: Post My Negotiations Decline
      description: Post my negotiations decline.
      operationId: postMyNegotiationsDecline
      x-api-path-slug: mynegotiationsiddecline-post
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - My
      - Negotiations
      - Id
      - Decline