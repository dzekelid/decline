---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
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
  /users/{id | userPrincipalName}/calendars/{id}/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsiddecline-post
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
  /me/calendargroup/calendars/{id}/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: mecalendargroupcalendarsideventsiddecline-post
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
  /users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsiddecline-post
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
  /me/calendargroups/{id}/calendars/{id}/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: mecalendargroupsidcalendarsideventsiddecline-post
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
  /users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/decline:
    post:
      summary: Event Decline
      description: 'event: decline Decline invitation to the specified event.'
      operationId: Event:Decline
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsiddecline-post
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
---