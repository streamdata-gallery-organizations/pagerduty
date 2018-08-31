---
swagger: "2.0"
x-collection-name: PagerDuty
x-complete: 0
info:
  title: PagerDuty Users {user_guid}
  version: 1.0.0
  description: Returns customer's user by user GUID.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /teams/{teamId}/people:
    get:
      summary: Teams Resource
      description: List people and integrations associated with a given team.
      operationId: list-people-and-integrations-associated-with-a-given-team
      x-api-path-slug: teamsteamidpeople-get
      parameters:
      - in: path
        name: teamId
        description: Unique identifier for team
      responses:
        200:
          description: OK
      tags:
      - ""
  '/users/{user_guid} ':
    ' get ':
      summary: Users {user_guid}
      description: Returns customer's user by user GUID.
      operationId: ""
      x-api-path-slug: usersuser-guid-get
      responses:
        200:
          description: OK
      tags:
      - Users
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