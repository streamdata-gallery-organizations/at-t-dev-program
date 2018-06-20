{
  "info": {
    "name": "AT&T API Post Speech Speechtotext",
    "_postman_id": "770fd3f9-0bd8-4a97-9e1c-9f489619e48a",
    "description": "/speech/v3/speechToText",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Devicecapabilities",
      "item": [
        {
          "id": "b07cc0b6-4f39-4d16-93a3-965ff025d915",
          "name": "1devicecapabilitiesacrauthorizationcapabilities",
          "request": {
            "url": "http://api.att.com/1/devicecapabilities/acr:authorization/capabilities",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/1/devicecapabilities/acr:authorization/capabilities"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2017ae34-c530-49fd-8463-026bf716f999"
            }
          ]
        }
      ]
    },
    {
      "name": "Messaging",
      "item": [
        {
          "id": "fd19db5c-5b3d-45fb-b6cc-d7c670cb6aab",
          "name": "3messagingoutboundsenderaddressrequests",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/messaging/outbound/:senderAddress/requests"
              ],
              "variable": [
                {
                  "id": "senderAddress",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/3/messaging/outbound/{senderAddress}/requests"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a7534131-4eff-4dae-bbbe-5a390853b1f7"
            }
          ]
        },
        {
          "id": "4e25df43-8a37-4219-9a4b-da1cd3aba9d3",
          "name": "3messagingoutboundsenderaddressrequestiddeliveryinfos",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/messaging/outbound/:senderAddress/:requestId/deliveryInfos"
              ],
              "variable": [
                {
                  "id": "requestId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "senderAddress",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/3/messaging/outbound/{senderAddress}/{requestId}/deliveryInfos"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f75058c1-a317-41e3-80cc-38f602bf12ae"
            }
          ]
        }
      ]
    },
    {
      "name": "Smsmessaging",
      "item": [
        {
          "id": "50cb304f-862d-46e4-aabc-873a49e5a4c3",
          "name": "3smsmessaginginboundregistrationsregistrationidmessages",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/smsmessaging/inbound/registrations/:registrationId/messages"
              ],
              "variable": [
                {
                  "id": "registrationId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/3/smsmessaging/inbound/registrations/{registrationId}/messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9bcaa983-bb23-49b5-a780-18b73707bd44"
            }
          ]
        },
        {
          "id": "d16ece10-bf39-4d34-9611-20861f3e4df4",
          "name": "3smsmessagingoutboundrequestssenderaddressrequestiddeliveryinfos",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/smsmessaging/outbound/requests/:senderAddress/:requestId/deliveryInfos"
              ],
              "variable": [
                {
                  "id": "requestId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "senderAddress",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/3/smsmessaging/outbound/requests/{senderAddress}/{requestId}/deliveryInfos"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1cc6976-63eb-492a-81d4-1f81c0d12ca1"
            }
          ]
        },
        {
          "id": "80659408-19eb-41a7-81a6-63ec088780a1",
          "name": "3smsmessagingoutboundsenderaddressrequests",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/smsmessaging/outbound/:senderAddress/requests"
              ],
              "variable": [
                {
                  "id": "senderAddress",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/3/smsmessaging/outbound/{senderAddress}/requests"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "72188691-00c3-49c4-b07c-ee6df06ba30a"
            }
          ]
        }
      ]
    },
    {
      "name": "Mms",
      "item": [
        {
          "id": "14e36ef9-c95d-4d47-aeea-36953f1bb141",
          "name": "mmsv3messagingoutbox",
          "request": {
            "url": "http://api.att.com/mms/v3/messaging/outbox",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/mms/v3/messaging/outbox"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "367d13e4-872e-4bde-b94b-9c443dfaaf6d"
            }
          ]
        },
        {
          "id": "0c069425-e6df-4385-9220-7882517b9e0a",
          "name": "mmsv3messagingoutboxmessageid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "mms/v3/messaging/outbox/:messageId"
              ],
              "variable": [
                {
                  "id": "messageId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/mms/v3/messaging/outbox/{messageId}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f71ae173-5386-4ccd-b794-aeb12d15c671"
            }
          ]
        }
      ]
    },
    {
      "name": "MyMessages",
      "item": [
        {
          "id": "25923504-185c-4bce-b200-f99642c5bf4e",
          "name": "mymessagesv2delta",
          "request": {
            "url": "http://api.att.com/myMessages/v2/delta",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/delta"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5a9bccd0-b251-4bfa-a1a6-3835d9ae52b3"
            }
          ]
        },
        {
          "id": "21f2a31a-1b81-44cb-851d-425ca702fe8a",
          "name": "mymessagesv2messages",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "61de2d30-0f60-439a-b03b-2a235fd7ba36"
            }
          ]
        },
        {
          "id": "de950f21-11aa-464f-aa69-be326c4895de",
          "name": "mymessagesv2messages",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4512b394-2cb1-4aa4-afe1-af51dc156d6e"
            }
          ]
        },
        {
          "id": "2e49c791-cb4f-448a-9ff0-18a15d892822",
          "name": "mymessagesv2messages",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "883dcb34-acb4-435d-9a61-72a6a889759e"
            }
          ]
        },
        {
          "id": "f58e4404-e16a-4445-a9ad-da452592867a",
          "name": "mymessagesv2messagesindex",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages/index",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/index"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3e21d258-8ea4-44c6-9dd2-92cbe1d9ce17"
            }
          ]
        },
        {
          "id": "47c03266-aeab-4618-90eb-8d448d893534",
          "name": "mymessagesv2messagesindexinfo",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages/index/info",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/index/info"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7aacca06-0311-4227-8727-e264e55b6d9a"
            }
          ]
        },
        {
          "id": "52bc8852-a7fa-4db4-804c-642768e3f6e5",
          "name": "mymessagesv2messagesmessageid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "myMessages/v2/messages/:messageId"
              ],
              "variable": [
                {
                  "id": "messageId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/{messageId}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "64a0524a-a9f7-4276-be0a-fb9dbe9b10d6"
            }
          ]
        },
        {
          "id": "35d3ba63-0386-48fc-990d-bc25ac6bd940",
          "name": "mymessagesv2messagesmessageid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "myMessages/v2/messages/:messageId"
              ],
              "variable": [
                {
                  "id": "messageId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/{messageId}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f99230d-1ecd-4f11-883d-344f2562883d"
            }
          ]
        },
        {
          "id": "18bb2671-caa6-4b0c-9151-2c54720da688",
          "name": "mymessagesv2messagesmessageidpartspartid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "myMessages/v2/messages/:messageId/parts/:partId"
              ],
              "variable": [
                {
                  "id": "messageId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "partId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/{messageId}/parts/{partId}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5c589f50-44d8-4e57-8fb0-2b596e199b30"
            }
          ]
        },
        {
          "id": "52d91e52-11d3-4a28-9727-114b4885e70b",
          "name": "mymessagesv2notificationconnectiondetails",
          "request": {
            "url": "http://api.att.com/myMessages/v2/notificationConnectionDetails",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/notificationConnectionDetails"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1e6d08db-3efc-4ce5-a3cf-f8d87d484eb0"
            }
          ]
        }
      ]
    },
    {
      "name": "Rest",
      "item": [
        {
          "id": "22a6a11e-43b3-437f-85e8-46c8212f1d8f",
          "name": "rest1ads",
          "request": {
            "url": "http://api.att.com/rest/1/ads",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/rest/1/ads"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "683e0b6d-19e9-4cc4-8123-5d43538b4663"
            }
          ]
        },
        {
          "id": "0d94c986-72e3-43ef-8be6-1134b0a33272",
          "name": "rest2devicesinfo",
          "request": {
            "url": "http://api.att.com/rest/2/Devices/Info",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/rest/2/Devices/Info"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cc85ca39-f709-4253-a220-97f70e626372"
            }
          ]
        }
      ]
    },
    {
      "name": "Sms",
      "item": [
        {
          "id": "1d82174d-c84a-4fdc-9a4f-24f4a5023f12",
          "name": "smsv3messaginginboxregistrationid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "sms/v3/messaging/inbox/:RegistrationID"
              ],
              "variable": [
                {
                  "id": "RegistrationID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/sms/v3/messaging/inbox/{RegistrationID}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ec404538-d15c-4cd7-a338-c71818a850bc"
            }
          ]
        },
        {
          "id": "3c0bdaae-6a0d-461a-810c-b36f49a178f7",
          "name": "smsv3messagingoutbox",
          "request": {
            "url": "http://api.att.com/sms/v3/messaging/outbox",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/sms/v3/messaging/outbox"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a11cfd83-7eb1-426f-8704-c634b2d03484"
            }
          ]
        },
        {
          "id": "511ac2f4-d675-430d-971b-6148a7bf4e53",
          "name": "smsv3messagingoutboxmessageid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "sms/v3/messaging/outbox/:messageId"
              ],
              "variable": [
                {
                  "id": "messageId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/sms/v3/messaging/outbox/{messageId}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "07d37fb0-d034-421d-a93b-6638c290a5bb"
            }
          ]
        }
      ]
    },
    {
      "name": "Speech",
      "item": [
        {
          "id": "15ee93aa-6b57-4c24-8a19-7c57746b55f0",
          "name": "speechv3speechtotext",
          "request": {
            "url": "http://api.att.com/speech/v3/speechToText",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/speech/v3/speechToText"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a2bb4701-a8fe-4bba-95d6-b264f7c19dcb"
            }
          ]
        }
      ]
    }
  ]
}