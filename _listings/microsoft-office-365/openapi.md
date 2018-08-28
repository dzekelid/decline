swagger: "2.0"
x-collection-name: Microsoft Office 365
x-complete: 1
info:
  title: Microsoft Office 365
  description: office-365-is-the-brand-name-used-by-microsoft-for-a-group-of-software-plus-services-subscriptions-that-provides-productivity-software-and-related-services-to-its-subscribers-
  version: 1.0.0
host: outlook.office365.com
basePath: /ews/odata/Me
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Events{event_id}/Decline:
    post:
      summary: Add Events Event Decline
      description: Post events event  decline
      operationId: postEventsEventDecline
      x-api-path-slug: eventsevent-iddecline-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Events
      - Event
      - ""
      - Decline
    parameters:
      summary: Parameters Events Event Decline
      description: Parameters events event  decline
      operationId: parametersEventsEventDecline
      x-api-path-slug: eventsevent-iddecline-parameters
      responses:
        200:
          description: OK
      tags:
      - Events
      - Event
      - ""
      - Decline