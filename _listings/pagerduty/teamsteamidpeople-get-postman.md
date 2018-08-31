{
  "info": {
    "name": "PagerDuty Teams Resource",
    "_postman_id": "41ab6144-c3a2-4a91-adf6-59ac444a6b14",
    "description": "List people and integrations associated with a given team.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "30e53c2d-d623-400e-9bf3-b0651f0ec850",
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
          "id": "efa2a480-cd5c-480c-a25c-d5439364bc06"
        }
      ]
    }
  ]
}