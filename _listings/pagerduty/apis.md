---
name: PagerDuty
x-slug: pagerduty
description: See how PagerDuty Digital Operations Management Platform integrates machine
  data & human intelligence to improve visibility & agility across organizations.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
x-kinRank: "8"
x-alexaRank: "19574"
tags: PagerDuty
created: "2018-05-22"
modified: "2018-05-22"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/apis.md
specificationVersion: "0.14"
apis:
- name: PagerDuty Teams Resource
  x-api-slug: pagerduty
  description: List people and integrations associated with a given team.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///teams/{teamId}/people
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/teamsteamidpeople-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/teamsteamidpeople-get-openapi.md
- name: PagerDuty Users {user_guid}
  x-api-slug: pagerduty
  description: Returns customer's user by user GUID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: 'https://///users/{user_guid} '
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersuser-guid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersuser-guid-get-openapi.md
- name: PagerDuty Users
  x-api-slug: pagerduty
  description: Returns all customer's users.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: 'https://///users '
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/users-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/users-get-openapi.md
- name: PagerDuty Users
  x-api-slug: pagerduty
  description: Creates a new user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: 'https://///users '
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/users-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/users-post-openapi.md
- name: PagerDuty Users
  x-api-slug: pagerduty
  description: Updates a user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: 'https://///users '
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/users-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/users-put-openapi.md
- name: PagerDuty Users {user_guid}
  x-api-slug: pagerduty
  description: DELETE users user gu
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: 'https://///users/{user_guid} '
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersuser-guid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersuser-guid-delete-openapi.md
- name: PagerDuty REST API Reference
  x-api-slug: pagerduty
  description: REST API Reference.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///api_reference
  tags: APIs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/api-reference-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/api-reference-get-openapi.md
- name: PagerDuty List abilities
  x-api-slug: pagerduty
  description: List all of your account's abilities, by name.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///abilities
  tags: Abilities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/abilities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/abilities-get-openapi.md
- name: PagerDuty Test an ability
  x-api-slug: pagerduty
  description: Test whether your account has a given ability.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///abilities/{id}
  tags: Abilities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/abilitiesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/abilitiesid-get-openapi.md
- name: PagerDuty List installed add-ons
  x-api-slug: pagerduty
  description: List all of the add-ons installed on your account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///addons
  tags: AddOns
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/addons-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/addons-get-openapi.md
- name: PagerDuty Install an add-on
  x-api-slug: pagerduty
  description: Install an add-on for your account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///addons
  tags: AddOns
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/addons-post-openapi.md
- name: PagerDuty Get an add-on
  x-api-slug: pagerduty
  description: Get details about an existing add-on.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///addons/{id}
  tags: AddOns
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/addonsid-get-openapi.md
- name: PagerDuty Delete an add-on
  x-api-slug: pagerduty
  description: Remove an existing add-on.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///addons/{id}
  tags: AddOns
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/addonsid-delete-openapi.md
- name: PagerDuty Update an add-on
  x-api-slug: pagerduty
  description: Update an existing add-on.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///addons/{id}
  tags: AddOns
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/addonsid-put-openapi.md
- name: PagerDuty List escalation policies
  x-api-slug: pagerduty
  description: List all of the existing escalation policies.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///escalation_policies
  tags: Escalation Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/escalation-policies-get-openapi.md
- name: PagerDuty Create an escalation policy
  x-api-slug: pagerduty
  description: Creates a new escalation policy. There must be at least one existing
    escalation rule added to create a new escalation policy.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///escalation_policies
  tags: Escalation Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/escalation-policies-post-openapi.md
- name: PagerDuty Get an escalation policy
  x-api-slug: pagerduty
  description: Get information about an existing escalation policy and its rules.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///escalation_policies/{id}
  tags: Escalation Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/escalation-policiesid-get-openapi.md
- name: PagerDuty Delete an escalation policy
  x-api-slug: pagerduty
  description: Deletes an existing escalation policy and rules. The escalation policy
    must not be in use by any services.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///escalation_policies/{id}
  tags: Escalation Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/escalation-policiesid-delete-openapi.md
- name: PagerDuty Update an escalation policy
  x-api-slug: pagerduty
  description: Updates an existing escalation policy and rules.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///escalation_policies/{id}
  tags: Escalation Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/escalation-policiesid-put-openapi.md
- name: PagerDuty List incidents
  x-api-slug: pagerduty
  description: List existing incidents.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///incidents
  tags: Incidents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/incidents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/incidents-get-openapi.md
- name: PagerDuty Manage incidents
  x-api-slug: pagerduty
  description: Acknowledge, resolve, escalate or reassign one or more incidents.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///incidents
  tags: Incidents
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/incidents-put-openapi.md
- name: PagerDuty Get an incident
  x-api-slug: pagerduty
  description: Show detailed information about an incident. Accepts either an incident
    id, or an incident number.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///incidents/{id}
  tags: Incidents
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/incidentsid-get-openapi.md
- name: PagerDuty Update an incident
  x-api-slug: pagerduty
  description: Acknowledge, resolve, escalate or reassign an incident.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///incidents/{id}
  tags: Incidents
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/incidentsid-put-openapi.md
- name: PagerDuty List log entries for the incident
  x-api-slug: pagerduty
  description: List log entries for the specified incident.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///incidents/{id}/log_entries
  tags: Incidents Log Entries
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/incidentsidlog-entries-get-openapi.md
- name: PagerDuty List existing notes for the specified incident
  x-api-slug: pagerduty
  description: List existing notes for the specified incident.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///incidents/{id}/notes
  tags: Incident Notes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/incidentsidnotes-get-openapi.md
- name: PagerDuty Create a new note for the specified incident
  x-api-slug: pagerduty
  description: Create a new note for the specified incident.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///incidents/{id}/notes
  tags: Incident Notes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/incidentsidnotes-post-openapi.md
- name: PagerDuty Snooze an incident
  x-api-slug: pagerduty
  description: Post incents  snooze
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///incidents/{id}/snooze
  tags: Incident Snooze
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/incidentsidsnooze-post-openapi.md
- name: PagerDuty List log entries
  x-api-slug: pagerduty
  description: List all of the incident log entries across the entire account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///log_entries
  tags: Log Entries
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/log-entries-get-openapi.md
- name: PagerDuty Get a log entry
  x-api-slug: pagerduty
  description: Get details for a specific incident log entry. This method provides
    additional information you can use to get at raw event data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///log_entries/{id}
  tags: Log Entries
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/log-entriesid-get-openapi.md
- name: PagerDuty List maintenance windows
  x-api-slug: pagerduty
  description: List existing maintenance windows, optionally filtered by service and/or
    team, or whether they are from the past, present or future.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///maintenance_windows
  tags: Maintenance Windows
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/maintenance-windows-get-openapi.md
- name: PagerDuty Create a maintenance window
  x-api-slug: pagerduty
  description: Create a new maintenance window for the specified services. No new
    incidents will be created for a service that is in maintenance.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///maintenance_windows
  tags: Maintenance Windows
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/maintenance-windows-post-openapi.md
- name: PagerDuty Get a maintenance window
  x-api-slug: pagerduty
  description: Get an existing maintenance window.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///maintenance_windows/{id}
  tags: Maintenance Windows
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/maintenance-windowsid-get-openapi.md
- name: PagerDuty Delete or end a maintenance window
  x-api-slug: pagerduty
  description: Delete an existing maintenance window if it's in the future, or end
    it if it's currently on-going. If the maintenance window has already ended it
    cannot be deleted.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///maintenance_windows/{id}
  tags: Maintenance Windows
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/maintenance-windowsid-delete-openapi.md
- name: PagerDuty Update a maintenance window
  x-api-slug: pagerduty
  description: Update an existing maintenance window.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///maintenance_windows/{id}
  tags: Maintenance Windows
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/maintenance-windowsid-put-openapi.md
- name: PagerDuty List notifications
  x-api-slug: pagerduty
  description: List notifications for a given time range, optionally filtered by type
    (sms_notification, email_notification, phone_notification, or push_notification).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///notifications
  tags: Notifications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/notifications-get-openapi.md
- name: PagerDuty List all of the on-calls
  x-api-slug: pagerduty
  description: List the on-call entries during a given time range.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///oncalls
  tags: Oncalls
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/oncalls-get-openapi.md
- name: PagerDuty List services
  x-api-slug: pagerduty
  description: List existing services.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///services
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/services-get-openapi.md
- name: PagerDuty Create a service
  x-api-slug: pagerduty
  description: Create a new service.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///services
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/services-post-openapi.md
- name: PagerDuty Get a service
  x-api-slug: pagerduty
  description: Get details about an existing service.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///services/{id}
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/servicesid-get-openapi.md
- name: PagerDuty Delete a service
  x-api-slug: pagerduty
  description: Delete an existing service. Once the service is deleted, it will not
    be accessible from the web UI and new incidents won't be able to be created for
    this service.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///services/{id}
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/servicesid-delete-openapi.md
- name: PagerDuty Update a service
  x-api-slug: pagerduty
  description: Update an existing service.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///services/{id}
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/servicesid-put-openapi.md
- name: PagerDuty Create a new integration
  x-api-slug: pagerduty
  description: Create a new integration belonging to a service.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///services/{id}/integrations
  tags: Service Integrations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/servicesidintegrations-post-openapi.md
- name: PagerDuty Update an existing integration
  x-api-slug: pagerduty
  description: Update an integration belonging to a service.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///services/{id}/integrations/{integration_id}
  tags: Service Integrations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/servicesidintegrationsintegration-id-put-openapi.md
- name: PagerDuty View an integration
  x-api-slug: pagerduty
  description: Get details about an integration belonging to a service.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///services/{id}/integrations/{integration_id}
  tags: Service Integrations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/servicesidintegrationsintegration-id-get-openapi.md
- name: PagerDuty Create a team
  x-api-slug: pagerduty
  description: Create a new team.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///teams
  tags: Teams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/teams-post-openapi.md
- name: PagerDuty List teams
  x-api-slug: pagerduty
  description: List teams of your PagerDuty account, optionally filtered by a search
    query.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///teams
  tags: Teams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/teams-get-openapi.md
- name: PagerDuty Get a team
  x-api-slug: pagerduty
  description: Get details about an existing team.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///teams/{id}
  tags: Teams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/teamsid-get-openapi.md
- name: PagerDuty Delete a team
  x-api-slug: pagerduty
  description: Remove an existing team.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///teams/{id}
  tags: Teams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/teamsid-delete-openapi.md
- name: PagerDuty Update a team
  x-api-slug: pagerduty
  description: Update an existing team.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///teams/{id}
  tags: Teams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/teamsid-put-openapi.md
- name: PagerDuty Remove an escalation policy from a team
  x-api-slug: pagerduty
  description: Delete teams  escalation policies escalation policy
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///teams/{id}/escalation_policies/{escalation_policy_id}
  tags: Team Escalation Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/teamsidescalation-policiesescalation-policy-id-delete-openapi.md
- name: PagerDuty Add an escalation policy to a team
  x-api-slug: pagerduty
  description: Put teams  escalation policies escalation policy
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///teams/{id}/escalation_policies/{escalation_policy_id}
  tags: Team Escalation Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/teamsidescalation-policiesescalation-policy-id-put-openapi.md
- name: PagerDuty Remove a user from a team
  x-api-slug: pagerduty
  description: Remove a user from a team.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///teams/{id}/users/{user_id}
  tags: Team Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/teamsidusersuser-id-delete-openapi.md
- name: PagerDuty Add a user to a team
  x-api-slug: pagerduty
  description: Add a user to a team.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///teams/{id}/users/{user_id}
  tags: Team Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/teamsidusersuser-id-put-openapi.md
- name: PagerDuty List users
  x-api-slug: pagerduty
  description: List users of your PagerDuty account, optionally filtered by a search
    query.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/users-get-openapi.md
- name: PagerDuty Create a user
  x-api-slug: pagerduty
  description: Create a new user. Note that you must also supply a `password` property
    to create a user--it will not be returned by any API.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/users-post-openapi.md
- name: PagerDuty Get a user
  x-api-slug: pagerduty
  description: Get details about an existing user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersid-get-openapi.md
- name: PagerDuty Delete a user
  x-api-slug: pagerduty
  description: Remove an existing user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersid-delete-openapi.md
- name: PagerDuty Update a user
  x-api-slug: pagerduty
  description: Update an existing user. Note that you may also supply a `password`
    property--it will not be returned by any API.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersid-put-openapi.md
- name: PagerDuty List a user's contact methods
  x-api-slug: pagerduty
  description: List contact methods of your PagerDuty user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/contact_methods
  tags: User Contact Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersidcontact-methods-get-openapi.md
- name: PagerDuty Create a user contact method
  x-api-slug: pagerduty
  description: Create a new contact method.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/contact_methods
  tags: User Contact Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersidcontact-methods-post-openapi.md
- name: PagerDuty Get a user's contact method
  x-api-slug: pagerduty
  description: Get details about a user's contact method.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/contact_methods/{contact_method_id}
  tags: User Contact Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersidcontact-methodscontact-method-id-get-openapi.md
- name: PagerDuty Delete a user's contact method
  x-api-slug: pagerduty
  description: Delete users  contact methods contact method
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/contact_methods/{contact_method_id}
  tags: User Contact Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersidcontact-methodscontact-method-id-delete-openapi.md
- name: PagerDuty Update a user's contact method
  x-api-slug: pagerduty
  description: Put users  contact methods contact method
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/contact_methods/{contact_method_id}
  tags: User Contact Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersidcontact-methodscontact-method-id-put-openapi.md
- name: PagerDuty List a user's notification rules
  x-api-slug: pagerduty
  description: List notification rules of your PagerDuty user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/notification_rules
  tags: User Notification Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersidnotification-rules-get-openapi.md
- name: PagerDuty Create a user notification rule
  x-api-slug: pagerduty
  description: Create a new notification rule.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/notification_rules
  tags: User Notification Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersidnotification-rules-post-openapi.md
- name: PagerDuty Get a user's notification rule
  x-api-slug: pagerduty
  description: Get users  notification rules notification rule
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/notification_rules/{notification_rule_id}
  tags: User Notification Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersidnotification-rulesnotification-rule-id-get-openapi.md
- name: PagerDuty Delete a user's notification rule
  x-api-slug: pagerduty
  description: Delete users  notification rules notification rule
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/notification_rules/{notification_rule_id}
  tags: User Notification Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersidnotification-rulesnotification-rule-id-delete-openapi.md
- name: PagerDuty Update a user's notification rule
  x-api-slug: pagerduty
  description: Put users  notification rules notification rule
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/notification_rules/{notification_rule_id}
  tags: User Notification Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersidnotification-rulesnotification-rule-id-put-openapi.md
- name: PagerDuty List vendors
  x-api-slug: pagerduty
  description: List all vendors.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///vendors
  tags: Vendors
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/vendors-get-openapi.md
- name: PagerDuty Get a vendor
  x-api-slug: pagerduty
  description: Get details about one specific vendor.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///vendors/{id}
  tags: Vendors
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/vendorsid-get-openapi.md
- name: PagerDuty Creating a service
  x-api-slug: pagerduty
  description: inventory services
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///inventory/services
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/inventoryservices--openapi.md
- name: PagerDuty Updating a service
  x-api-slug: pagerduty
  description: inventory services service
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///inventory/services/serviceId
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/inventoryservicesserviceid--openapi.md
- name: PagerDuty Listing service groups
  x-api-slug: pagerduty
  description: inventory services groups token token
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///inventory/services/groups/?token=token
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/inventoryservicesgroupstokentoken--openapi.md
- name: PagerDuty Creating a recipient
  x-api-slug: pagerduty
  description: Create recipients for your alert notifications
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///notifications/recipients
  tags: Metrics
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/notificationsrecipients-get-openapi.md
- name: PagerDuty Deleting a user
  x-api-slug: pagerduty
  description: users users user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/users/userId
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/usersusersuserid--openapi.md
- name: PagerDuty
  x-api-slug: pagerduty
  description: See how PagerDuty Digital Operations Management Platform integrates
    machine data & human intelligence to improve visibility & agility across organizations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https:///
  tags: PagerDuty
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pagerduty/master/_listings/pagerduty/openapi.md
x-common:
- type: x-base
  url: https://acme.pagerduty.com/api/
- type: x-blog
  url: http://blog.pagerduty.com/
- type: x-blog-rss
  url: http://blog.pagerduty.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/pagerduty
- type: x-crunchbase
  url: https://crunchbase.com/organization/pagerduty
- type: x-developer
  url: http://developer.pagerduty.com/
- type: x-email
  url: info@pagerduty.com
- type: x-email
  url: sales@pagerduty.com
- type: x-email
  url: support@pagerduty.com
- type: x-email
  url: legal@pagerduty.com
- type: x-github
  url: https://github.com/PagerDuty
- type: x-openapi-spec--authoritative
  url: https://api-reference.pagerduty.com/output.json
- type: x-pricing
  url: https://www.pagerduty.com/pricing/
- type: x-twitter
  url: https://twitter.com/pagerduty
- type: x-website
  url: http://www.pagerduty.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---