{
  "info": {
    "name": "PagerDuty List abilities",
    "_postman_id": "a89ad146-e0a3-44b3-bee5-fd529a016ad3",
    "description": "List all of your account's abilities, by name.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Folder",
      "item": [
        {
          "id": "4ef71c6c-81fc-488e-9371-04cfae54f44a",
          "name": "list-people-and-integrations-associated-with-a-given-team",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "api",
                "teams/:teamId/people"
              ],
              "variable": [
                {
                  "id": "teamId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List people and integrations associated with a given team."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3638f78c-836c-43d6-beb9-f692da98cf41"
            }
          ]
        }
      ]
    },
    {
      "name": "APIs",
      "item": [
        {
          "id": "e8929fce-5258-47e6-bf87-be9b152b566a",
          "name": "rest-api-reference",
          "request": {
            "url": "http://example.com/api/api_reference",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "REST API Reference."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4811ee89-9f93-40aa-b0b4-80c202ef691f"
            }
          ]
        }
      ]
    },
    {
      "name": "Abilities",
      "item": [
        {
          "id": "8ec1eac5-c2dc-4df5-8289-5e766c4e2904",
          "name": "list-all-of-your-accounts-abilities-by-name",
          "request": {
            "url": "http://example.com/api/abilities",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all of your account's abilities, by name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9692bc54-3953-4efd-9fed-245703a43b2d"
            }
          ]
        }
      ]
    }
  ]
}