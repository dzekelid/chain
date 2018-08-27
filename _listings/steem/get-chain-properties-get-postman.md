{
  "info": {
    "name": "Steem get chain properties",
    "_postman_id": "db9099a0-3697-47ca-a1d5-a2a949242ba6",
    "description": "get chain properties",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Get",
      "item": [
        {
          "id": "cee6b60b-ec49-4679-8cea-3bb7c1766070",
          "name": "get-chain-properties",
          "request": {
            "url": "http://api.steemjs.com/get_chain_properties",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get chain properties"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1e80011c-e120-415c-9d7a-e1b41e7ac2e5"
            }
          ]
        }
      ]
    }
  ]
}