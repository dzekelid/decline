---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Event Decline
  description: 'event: decline Decline invitation to the specified event.'
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: meeventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Decline
  /users/{id | userPrincipalName}/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: usersid--userprincipalnameeventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Decline
  /groups/{id}/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: groupsideventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Decline
  /me/calendar/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: mecalendareventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Decline
  /users/{id | userPrincipalName}/calendar/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: usersid--userprincipalnamecalendareventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Decline
  /groups/{id}/calendar/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: groupsidcalendareventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Decline
  /me/calendars/{id}/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: mecalendarsideventsiddecline-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Decline
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