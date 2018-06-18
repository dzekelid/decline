---
swagger: "2.0"
x-collection-name: Facebook
x-complete: 1
info:
  title: Facebook
  description: connect-to-the-social-network-with-the-graph-api-
  version: 1.0.0
host: graph.facebook.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{event}/declined:
    get:
      summary: Get Event Declined
      description: All of the users who declined their invitation to this event
      operationId: getEventDeclined
      x-api-path-slug: eventdeclined-get
      parameters:
      - in: path
        name: event
        description: Represents the ID of the event object
      responses:
        200:
          description: OK
      tags:
      - Event
      - Declined
    post:
      summary: Post Event Declined
      description: RSVPs the user as 'declined' for the event
      operationId: postEventDeclined
      x-api-path-slug: eventdeclined-post
      parameters:
      - in: path
        name: event
        description: Represents the ID of the event object
      responses:
        200:
          description: OK
      tags:
      - Event
      - Declined
---