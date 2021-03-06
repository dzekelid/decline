swagger: "2.0"
x-collection-name: Meetup
x-complete: 1
info:
  title: Meetup
  version: 1.0.0
host: api.meetup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /:urlname/member/approvals:
    delete:
      summary: Membership Decline
      description: Declines one or more requests for group membership
      operationId: profiles
      x-api-path-slug: urlnamememberapprovals-delete
      parameters:
      - in: query
        name: anon
        description: Optional Boolean value indicating whether the declining members
          email address should be hidden in the resulting response
        type: string
      - in: query
        name: ban
        description: Optional Boolean value indicating whether or not to ban the member
          in the future
        type: string
      - in: query
        name: explanation
        description: Optional explanation to send to the members being declined
        type: string
      - in: query
        name: member
        description: Comma-delimited numeric pending member IDs
        type: string
      - in: query
        name: send_copy
        description: Optional Boolean value indicating whether or not to send a copy
          to the member issuing the decline
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Members