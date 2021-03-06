---
swagger: "2.0"
x-collection-name: AT&T Dev Program
x-complete: 0
info:
  title: AT&T API Get Mms Messaging Outbox Messageid
  description: /mms/v3/messaging/outbox/{messageId}
  version: "1"
host: api.att.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /1/devicecapabilities/acr:authorization/capabilities:
    get:
      summary: Get Devicecapabilities Acr Authorization Capabilities
      description: /1/devicecapabilities/acr:authorization/capabilities
      operationId: 1devicecapabilitiesacrauthorizationcapabilities
      x-api-path-slug: 1devicecapabilitiesacrauthorizationcapabilities-get
      responses:
        200:
          description: OK
      tags:
      - Devicecapabilities
      - Acr:authorization
      - Capabilities
  /3/messaging/outbound/{senderAddress}/requests:
    post:
      summary: Post Messaging Outbound Senderaddress Requests
      description: /3/messaging/outbound/{senderAddress}/requests
      operationId: 3messagingoutboundsenderaddressrequests
      x-api-path-slug: 3messagingoutboundsenderaddressrequests-post
      parameters:
      - in: path
        name: senderAddress
      responses:
        200:
          description: OK
      tags:
      - Messaging
      - Outbound
      - Senderress
      - Requests
  /3/messaging/outbound/{senderAddress}/{requestId}/deliveryInfos:
    get:
      summary: Get Messaging Outbound Senderaddress Requestid Deliveryinfos
      description: /3/messaging/outbound/{senderAddress}/{requestId}/deliveryInfos
      operationId: 3messagingoutboundsenderaddressrequestiddeliveryinfos
      x-api-path-slug: 3messagingoutboundsenderaddressrequestiddeliveryinfos-get
      parameters:
      - in: path
        name: requestId
      - in: path
        name: senderAddress
      responses:
        200:
          description: OK
      tags:
      - Messaging
      - Outbound
      - Senderress
      - RequestId
      - DeliveryInfos
  /3/smsmessaging/inbound/registrations/{registrationId}/messages:
    get:
      summary: Get SMS Inbound Registrations Registrationid Messages
      description: /3/smsmessaging/inbound/registrations/{registrationId}/messages
      operationId: 3smsmessaginginboundregistrationsregistrationidmessages
      x-api-path-slug: 3smsmessaginginboundregistrationsregistrationidmessages-get
      parameters:
      - in: path
        name: registrationId
      responses:
        200:
          description: OK
      tags:
      - Smsmessaging
      - Inbound
      - Registrations
      - RegistrationId
      - Messages
  /3/smsmessaging/outbound/requests/{senderAddress}/{requestId}/deliveryInfos:
    get:
      summary: Get SMS Outbound Requests Senderaddress Requestid Deliveryinfos
      description: /3/smsmessaging/outbound/requests/{senderAddress}/{requestId}/deliveryInfos
      operationId: 3smsmessagingoutboundrequestssenderaddressrequestiddeliveryinfos
      x-api-path-slug: 3smsmessagingoutboundrequestssenderaddressrequestiddeliveryinfos-get
      parameters:
      - in: path
        name: requestId
      - in: path
        name: senderAddress
      responses:
        200:
          description: OK
      tags:
      - Smsmessaging
      - Outbound
      - Requests
      - Senderress
      - RequestId
      - DeliveryInfos
  /3/smsmessaging/outbound/{senderAddress}/requests:
    post:
      summary: Post SMS Outbound Senderaddress Requests
      description: /3/smsmessaging/outbound/{senderAddress}/requests
      operationId: 3smsmessagingoutboundsenderaddressrequests
      x-api-path-slug: 3smsmessagingoutboundsenderaddressrequests-post
      parameters:
      - in: path
        name: senderAddress
      responses:
        200:
          description: OK
      tags:
      - Smsmessaging
      - Outbound
      - Senderress
      - Requests
  /mms/v3/messaging/outbox:
    post:
      summary: Post Mms Messaging Outbox
      description: /mms/v3/messaging/outbox
      operationId: mmsv3messagingoutbox
      x-api-path-slug: mmsv3messagingoutbox-post
      responses:
        200:
          description: OK
      tags:
      - Mms
      - VMessaging
      - Outbox
  /mms/v3/messaging/outbox/{messageId}:
    get:
      summary: Get Mms Messaging Outbox Messageid
      description: /mms/v3/messaging/outbox/{messageId}
      operationId: mmsv3messagingoutboxmessageid
      x-api-path-slug: mmsv3messagingoutboxmessageid-get
      parameters:
      - in: path
        name: messageId
      responses:
        200:
          description: OK
      tags:
      - Mms
      - VMessaging
      - Outbox
      - MessageId
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