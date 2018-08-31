---
swagger: "2.0"
x-collection-name: PagerDuty
x-complete: 0
info:
  title: PagerDuty Update an add-on
  version: 1.0.0
  description: Update an existing add-on.
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
    ' delete ':
      summary: Users {user_guid}
      description: DELETE users user gu
      operationId: ""
      x-api-path-slug: usersuser-guid-delete
      responses:
        200:
          description: OK
      tags:
      - Users
  '/users ':
    ' get ':
      summary: Users
      description: Returns all customer's users.
      operationId: ""
      x-api-path-slug: users-get
      responses:
        200:
          description: OK
      tags:
      - Users
    ' post ':
      summary: Users
      description: Creates a new user.
      operationId: ""
      x-api-path-slug: users-post
      responses:
        200:
          description: OK
      tags:
      - Users
    ' put ':
      summary: Users
      description: Updates a user.
      operationId: ""
      x-api-path-slug: users-put
      responses:
        200:
          description: OK
      tags:
      - Users
  /api_reference:
    get:
      summary: REST API Reference
      description: REST API Reference.
      operationId: rest-api-reference
      x-api-path-slug: api-reference-get
      responses:
        200:
          description: OK
      tags:
      - APIs
  /abilities:
    get:
      summary: List abilities
      description: List all of your account's abilities, by name.
      operationId: list-all-of-your-accounts-abilities-by-name
      x-api-path-slug: abilities-get
      responses:
        200:
          description: OK
      tags:
      - Abilities
  /abilities/{id}:
    get:
      summary: Test an ability
      description: Test whether your account has a given ability.
      operationId: test-whether-your-account-has-a-given-ability
      x-api-path-slug: abilitiesid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Abilities
  /addons:
    get:
      summary: List installed add-ons
      description: List all of the add-ons installed on your account.
      operationId: list-all-of-the-addons-installed-on-your-account
      x-api-path-slug: addons-get
      parameters:
      - in: query
        name: filter
        description: Filters the results, showing only add-ons of the given type
      - in: query
        name: No Name
      - in: query
        name: service_ids[]
        description: Filters the results, showing only add-ons for the given services
      responses:
        200:
          description: OK
      tags:
      - AddOns
    post:
      summary: Install an add-on
      description: Install an add-on for your account.
      operationId: install-an-addon-for-your-account
      x-api-path-slug: addons-post
      parameters:
      - in: body
        name: addon
        description: The add-on to be installed
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - AddOns
  /addons/{id}:
    get:
      summary: Get an add-on
      description: Get details about an existing add-on.
      operationId: get-details-about-an-existing-addon
      x-api-path-slug: addonsid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - AddOns
    delete:
      summary: Delete an add-on
      description: Remove an existing add-on.
      operationId: remove-an-existing-addon
      x-api-path-slug: addonsid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - AddOns
    put:
      summary: Update an add-on
      description: Update an existing add-on.
      operationId: update-an-existing-addon
      x-api-path-slug: addonsid-put
      parameters:
      - in: body
        name: addon
        description: The add-on to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - AddOns
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