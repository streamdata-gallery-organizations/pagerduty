{
  "info": {
    "name": "PagerDuty Test an ability",
    "_postman_id": "c4894510-f6c3-4b66-9536-65431d6d2c64",
    "description": "Test whether your account has a given ability.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Folder",
      "item": [
        {
          "id": "c89ece87-b9e5-4f51-a7a4-7f6402fd0f10",
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
              "id": "50dd5c26-5711-4271-a3a6-8f415f2d4b26"
            }
          ]
        }
      ]
    },
    {
      "name": "APIs",
      "item": [
        {
          "id": "c101efab-2d76-4a88-a7b9-5c6c17abc218",
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
              "id": "520447d5-b275-47fe-a730-006f81d162bd"
            }
          ]
        }
      ]
    },
    {
      "name": "Abilities",
      "item": [
        {
          "id": "6fa8096e-0a29-476e-8103-a2928e585f18",
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
              "id": "428eab10-3cd9-4015-af1b-ccffbf2d5f9b"
            }
          ]
        },
        {
          "id": "4b78c626-a747-4c5e-886c-38a21a6a13c3",
          "name": "test-whether-your-account-has-a-given-ability",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "api",
                "abilities/:id"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Test whether your account has a given ability."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "147e12bb-bd68-4ce4-bd1d-a1cb881bb22f"
            }
          ]
        }
      ]
    }
  ]
}