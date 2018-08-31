---
swagger: "2.0"
x-collection-name: PagerDuty
x-complete: 0
info:
  title: PagerDuty Get a user's contact method
  version: 1.0.0
  description: Get details about a user's contact method.
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
  /escalation_policies:
    get:
      summary: List escalation policies
      description: List all of the existing escalation policies.
      operationId: list-all-of-the-existing-escalation-policies
      x-api-path-slug: escalation-policies-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: query
        description: Filters the results, showing only the escalation policies whose
          names contain the query
      - in: query
        name: user_ids[]
        description: Filters the results, showing only escalation policies on which
          any of the users is a target
      responses:
        200:
          description: OK
      tags:
      - Escalation Policies
    post:
      summary: Create an escalation policy
      description: Creates a new escalation policy. There must be at least one existing
        escalation rule added to create a new escalation policy.
      operationId: creates-a-new-escalation-policy-there-must-be-at-least-one-existing-escalation-rule-added-to-create-
      x-api-path-slug: escalation-policies-post
      parameters:
      - in: body
        name: escalation_policy
        description: The escalation policy to be created
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Escalation Policies
  /escalation_policies/{id}:
    get:
      summary: Get an escalation policy
      description: Get information about an existing escalation policy and its rules.
      operationId: get-information-about-an-existing-escalation-policy-and-its-rules
      x-api-path-slug: escalation-policiesid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Escalation Policies
    delete:
      summary: Delete an escalation policy
      description: Deletes an existing escalation policy and rules. The escalation
        policy must not be in use by any services.
      operationId: deletes-an-existing-escalation-policy-and-rules-the-escalation-policy-must-not-be-in-use-by-any-serv
      x-api-path-slug: escalation-policiesid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Escalation Policies
    put:
      summary: Update an escalation policy
      description: Updates an existing escalation policy and rules.
      operationId: updates-an-existing-escalation-policy-and-rules
      x-api-path-slug: escalation-policiesid-put
      parameters:
      - in: body
        name: escalation_policy
        description: The escalation policy to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Escalation Policies
  /incidents:
    get:
      summary: List incidents
      description: List existing incidents.
      operationId: list-existing-incidents
      x-api-path-slug: incidents-get
      parameters:
      - in: query
        name: include[]
        description: Array of additional details to include
      - in: query
        name: No Name
      - in: query
        name: sort_by
        description: Used to specify both the field you wish to sort the results on
          (incident_number/created_on/resolved_on/urgency), as well as the direction
          (asc/desc) of the results
      - in: query
        name: statuses[]
        description: Return only incidents with the given statuses
      responses:
        200:
          description: OK
      tags:
      - Incidents
    put:
      summary: Manage incidents
      description: Acknowledge, resolve, escalate or reassign one or more incidents.
      operationId: acknowledge-resolve-escalate-or-reassign-one-or-more-incidents
      x-api-path-slug: incidents-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: payload
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Incidents
  /incidents/{id}:
    get:
      summary: Get an incident
      description: Show detailed information about an incident. Accepts either an
        incident id, or an incident number.
      operationId: show-detailed-information-about-an-incident-accepts-either-an-incident-id-or-an-incident-number
      x-api-path-slug: incidentsid-get
      parameters:
      - in: path
        name: id
        description: Either the id or number of the incident to retrieve
      responses:
        200:
          description: OK
      tags:
      - Incidents
    put:
      summary: Update an incident
      description: Acknowledge, resolve, escalate or reassign an incident.
      operationId: acknowledge-resolve-escalate-or-reassign-an-incident
      x-api-path-slug: incidentsid-put
      parameters:
      - in: path
        name: id
        description: The id of the incident to update
      - in: query
        name: No Name
      - in: body
        name: payload
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Incidents
  /incidents/{id}/log_entries:
    get:
      summary: List log entries for the incident
      description: List log entries for the specified incident.
      operationId: list-log-entries-for-the-specified-incident
      x-api-path-slug: incidentsidlog-entries-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Incidents Log Entries
  /incidents/{id}/notes:
    get:
      summary: List existing notes for the specified incident
      description: List existing notes for the specified incident.
      operationId: list-existing-notes-for-the-specified-incident
      x-api-path-slug: incidentsidnotes-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Incident Notes
    post:
      summary: Create a new note for the specified incident
      description: Create a new note for the specified incident.
      operationId: create-a-new-note-for-the-specified-incident
      x-api-path-slug: incidentsidnotes-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: payload
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Incident Notes
  /incidents/{id}/snooze:
    post:
      summary: Snooze an incident
      description: Post incents  snooze
      operationId: snooze-an-incident
      x-api-path-slug: incidentsidsnooze-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: payload
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Incident Snooze
  /log_entries:
    get:
      summary: List log entries
      description: List all of the incident log entries across the entire account.
      operationId: list-all-of-the-incident-log-entries-across-the-entire-account
      x-api-path-slug: log-entries-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Log Entries
  /log_entries/{id}:
    get:
      summary: Get a log entry
      description: Get details for a specific incident log entry. This method provides
        additional information you can use to get at raw event data.
      operationId: get-details-for-a-specific-incident-log-entry-this-method-provides-additional-information-you-can-us
      x-api-path-slug: log-entriesid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Log Entries
  /maintenance_windows:
    get:
      summary: List maintenance windows
      description: List existing maintenance windows, optionally filtered by service
        and/or team, or whether they are from the past, present or future.
      operationId: list-existing-maintenance-windows-optionally-filtered-by-service-andor-team-or-whether-they-are-from
      x-api-path-slug: maintenance-windows-get
      parameters:
      - in: query
        name: filter
        description: Only return maintenance windows in a given state
      - in: query
        name: No Name
      - in: query
        name: query
        description: Filters the results, showing only the maintenance windows whose
          descriptions contain the query
      responses:
        200:
          description: OK
      tags:
      - Maintenance Windows
    post:
      summary: Create a maintenance window
      description: Create a new maintenance window for the specified services. No
        new incidents will be created for a service that is in maintenance.
      operationId: create-a-new-maintenance-window-for-the-specified-services-no-new-incidents-will-be-created-for-a-se
      x-api-path-slug: maintenance-windows-post
      parameters:
      - in: body
        name: maintenance_window
        description: The maintenance window object
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Maintenance Windows
  /maintenance_windows/{id}:
    get:
      summary: Get a maintenance window
      description: Get an existing maintenance window.
      operationId: get-an-existing-maintenance-window
      x-api-path-slug: maintenance-windowsid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Maintenance Windows
    delete:
      summary: Delete or end a maintenance window
      description: Delete an existing maintenance window if it's in the future, or
        end it if it's currently on-going. If the maintenance window has already ended
        it cannot be deleted.
      operationId: delete-an-existing-maintenance-window-if-its-in-the-future-or-end-it-if-its-currently-ongoing-if-the
      x-api-path-slug: maintenance-windowsid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Maintenance Windows
    put:
      summary: Update a maintenance window
      description: Update an existing maintenance window.
      operationId: update-an-existing-maintenance-window
      x-api-path-slug: maintenance-windowsid-put
      parameters:
      - in: body
        name: maintenance_window
        description: The maintenance window to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Maintenance Windows
  /notifications:
    get:
      summary: List notifications
      description: List notifications for a given time range, optionally filtered
        by type (sms_notification, email_notification, phone_notification, or push_notification).
      operationId: list-notifications-for-a-given-time-range-optionally-filtered-by-type-sms-notification-email-notific
      x-api-path-slug: notifications-get
      parameters:
      - in: query
        name: filter
        description: Return notification of this type only
      - in: query
        name: include[]
        description: Array of additional details to include
      - in: query
        name: No Name
      - in: query
        name: since
        description: The start of the date range over which you want to search
      - in: query
        name: until
        description: The end of the date range over which you want to search
      responses:
        200:
          description: OK
      tags:
      - Notifications
  /oncalls:
    get:
      summary: List all of the on-calls
      description: List the on-call entries during a given time range.
      operationId: list-the-oncall-entries-during-a-given-time-range
      x-api-path-slug: oncalls-get
      parameters:
      - in: query
        name: earliest
        description: This will filter on-calls such that only the earliest on-call
          for each combination of escalation policy, escalation level, and user is
          returned
      - in: query
        name: escalation_policy_ids[]
        description: Filters the results, showing only on-calls for the specified
          escalation policy IDs
      - in: query
        name: include[]
        description: Array of additional details to include
      - in: query
        name: No Name
      - in: query
        name: schedule_ids[]
        description: Filters the results, showing only on-calls for the specified
          schedule IDs
      - in: query
        name: since
        description: The start of the time range over which you want to search
      - in: query
        name: until
        description: The end of the time range over which you want to search
      - in: query
        name: user_ids[]
        description: Filters the results, showing only on-calls for the specified
          user IDs
      responses:
        200:
          description: OK
      tags:
      - Oncalls
  /services:
    get:
      summary: List services
      description: List existing services.
      operationId: list-existing-services
      x-api-path-slug: services-get
      parameters:
      - in: query
        name: include[]
        description: Array of additional details to include
      - in: query
        name: No Name
      - in: query
        name: query
        description: Filters the result, showing only the services whose name or service_key
          matches the query
      responses:
        200:
          description: OK
      tags:
      - Services
    post:
      summary: Create a service
      description: Create a new service.
      operationId: create-a-new-service
      x-api-path-slug: services-post
      parameters:
      - in: body
        name: service
        description: The service to be created
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Services
  /services/{id}:
    get:
      summary: Get a service
      description: Get details about an existing service.
      operationId: get-details-about-an-existing-service
      x-api-path-slug: servicesid-get
      parameters:
      - in: query
        name: include[]
        description: Array of additional details to include
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Services
    delete:
      summary: Delete a service
      description: Delete an existing service. Once the service is deleted, it will
        not be accessible from the web UI and new incidents won't be able to be created
        for this service.
      operationId: delete-an-existing-service-once-the-service-is-deleted-it-will-not-be-accessible-from-the-web-ui-and
      x-api-path-slug: servicesid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Services
    put:
      summary: Update a service
      description: Update an existing service.
      operationId: update-an-existing-service
      x-api-path-slug: servicesid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: service
        description: The service to be updated
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Services
  /services/{id}/integrations:
    post:
      summary: Create a new integration
      description: Create a new integration belonging to a service.
      operationId: create-a-new-integration-belonging-to-a-service
      x-api-path-slug: servicesidintegrations-post
      parameters:
      - in: body
        name: integration
        description: The integration to be created
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service Integrations
  /services/{id}/integrations/{integration_id}:
    put:
      summary: Update an existing integration
      description: Update an integration belonging to a service.
      operationId: update-an-integration-belonging-to-a-service
      x-api-path-slug: servicesidintegrationsintegration-id-put
      parameters:
      - in: body
        name: integration
        description: The integration to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service Integrations
    get:
      summary: View an integration
      description: Get details about an integration belonging to a service.
      operationId: get-details-about-an-integration-belonging-to-a-service
      x-api-path-slug: servicesidintegrationsintegration-id-get
      parameters:
      - in: query
        name: include[]
        description: Array of additional details to include
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service Integrations
  /teams:
    post:
      summary: Create a team
      description: Create a new team.
      operationId: create-a-new-team
      x-api-path-slug: teams-post
      parameters:
      - in: body
        name: team
        description: The team to be created
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Teams
    get:
      summary: List teams
      description: List teams of your PagerDuty account, optionally filtered by a
        search query.
      operationId: list-teams-of-your-pagerduty-account-optionally-filtered-by-a-search-query
      x-api-path-slug: teams-get
      parameters:
      - in: query
        name: query
        description: Filters the result, showing only the teams whose names or email
          addresses match the query
      responses:
        200:
          description: OK
      tags:
      - Teams
  /teams/{id}:
    get:
      summary: Get a team
      description: Get details about an existing team.
      operationId: get-details-about-an-existing-team
      x-api-path-slug: teamsid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Teams
    delete:
      summary: Delete a team
      description: Remove an existing team.
      operationId: remove-an-existing-team
      x-api-path-slug: teamsid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Teams
    put:
      summary: Update a team
      description: Update an existing team.
      operationId: update-an-existing-team
      x-api-path-slug: teamsid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: team
        description: The team to be updated
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Teams
  /teams/{id}/escalation_policies/{escalation_policy_id}:
    delete:
      summary: Remove an escalation policy from a team
      description: Delete teams  escalation policies escalation policy
      operationId: remove-an-escalation-policy-from-a-team
      x-api-path-slug: teamsidescalation-policiesescalation-policy-id-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Team Escalation Policies
    put:
      summary: Add an escalation policy to a team
      description: Put teams  escalation policies escalation policy
      operationId: add-an-escalation-policy-to-a-team
      x-api-path-slug: teamsidescalation-policiesescalation-policy-id-put
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Team Escalation Policies
  /teams/{id}/users/{user_id}:
    delete:
      summary: Remove a user from a team
      description: Remove a user from a team.
      operationId: remove-a-user-from-a-team
      x-api-path-slug: teamsidusersuser-id-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Team Users
    put:
      summary: Add a user to a team
      description: Add a user to a team.
      operationId: add-a-user-to-a-team
      x-api-path-slug: teamsidusersuser-id-put
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Team Users
  /users:
    get:
      summary: List users
      description: List users of your PagerDuty account, optionally filtered by a
        search query.
      operationId: list-users-of-your-pagerduty-account-optionally-filtered-by-a-search-query
      x-api-path-slug: users-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: query
        description: Filters the result, showing only the users whose names or email
          addresses match the query
      responses:
        200:
          description: OK
      tags:
      - Users
    post:
      summary: Create a user
      description: Create a new user. Note that you must also supply a `password`
        property to create a user--it will not be returned by any API.
      operationId: create-a-new-user-note-that-you-must-also-supply-a-password-property-to-create-a-userit-will-not-be-
      x-api-path-slug: users-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: user
        description: The user to be created
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Users
  /users/{id}:
    get:
      summary: Get a user
      description: Get details about an existing user.
      operationId: get-details-about-an-existing-user
      x-api-path-slug: usersid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
    delete:
      summary: Delete a user
      description: Remove an existing user.
      operationId: remove-an-existing-user
      x-api-path-slug: usersid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
    put:
      summary: Update a user
      description: Update an existing user. Note that you may also supply a `password`
        property--it will not be returned by any API.
      operationId: update-an-existing-user-note-that-you-may-also-supply-a-password-propertyit-will-not-be-returned-by-
      x-api-path-slug: usersid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: user
        description: The user to be updated
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Users
  /users/{id}/contact_methods:
    get:
      summary: List a user's contact methods
      description: List contact methods of your PagerDuty user.
      operationId: list-contact-methods-of-your-pagerduty-user
      x-api-path-slug: usersidcontact-methods-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - User Contact Methods
    post:
      summary: Create a user contact method
      description: Create a new contact method.
      operationId: create-a-new-contact-method
      x-api-path-slug: usersidcontact-methods-post
      parameters:
      - in: body
        name: contact_method
        description: The contact method to be created
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - User Contact Methods
  /users/{id}/contact_methods/{contact_method_id}:
    get:
      summary: Get a user's contact method
      description: Get details about a user's contact method.
      operationId: get-details-about-a-users-contact-method
      x-api-path-slug: usersidcontact-methodscontact-method-id-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - User Contact Methods
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