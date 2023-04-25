# queryPublish

### Method description

```
queryPublish
```

> URL: http://localhost:8080/query/queryPublish?start=-1h&stop=0h
>
> Origin Url: http://localhost:8080/query//queryPublish
>
> Type: POST


### Request headers

|Header Name| Header Value|
|---------|------|
|Authorization|Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJqdGkiOiJkMDcwNjI2ZC0wZTM2LTQzZDctOWY0YS0xODM3MzA4Njg0M2QiLCJpc3MiOiIwYzU5OTg5ZDM5NzAzODBhZTE2ODg4MDY4NmM0YTA3MCIsInN1YiI6IjBjNTk5ODlkMzk3MDM4MGFlMTY4ODgwNjg2YzRhMDcwIiwiZXhwIjoxNjgyOTk3ODQ5LCJhdWQiOiJtZnMiLCJzY29wZSI6WyJ1c2VyTWFuIiwiZ2VuZXJhdGVKd3QiLCJzZWFyY2hPbmxpbmUiLCJyb2xlIiwiY29ubmVjdCIsInB1c2giLCJwdWJsaXNoIiwiY29uc3VtZSIsInF1ZXJ5Il19.c4kxRX2E9vgApGjTaEKzMcemlePZARVLAAdcemejQw4|

### Parameters

##### Path parameters

| Parameter | Type | Value | Description |
|---------|------|------|------------|


##### URL parameters

|Required| Parameter | Type | Value | Description |
|---------|---------|------|------|------------|


##### Body parameters

###### JSON

```

```

###### JSON document

```
null
```


##### Form URL-Encoded
|Required| Parameter | Type | Value | Description |
|---------|---------|------|------|------------|


##### Multipart
|Required | Parameter | Type | Value | Description |
|---------|---------|------|------|------------|


### Response

##### Response example

```
[
  {
    "messageId": "2ea6b2da-0052-4600-a0c7-0260288fe13c",
    "source": "https://spring.io/foos",
    "type": "io.spring.event.Foo",
    "appId": null,
    "userId": "0c59989d3970380ae168880686c4a070",
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 1100419821390004224,
    "dataContentType": "application/cloudevents+json",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": "\"newFo000000\"",
    "submit": null,
    "time": "2023-04-25T05:55:30.233077477Z"
  },
  {
    "messageId": "08663e3f-07ea-4a0e-991f-5525653acf16",
    "source": "https://spring.io/foos",
    "type": "io.spring.event.Foo",
    "appId": null,
    "userId": "0c59989d3970380ae168880686c4a070",
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 1100419821687799808,
    "dataContentType": "application/cloudevents+json",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": "\"newFo000000\"",
    "submit": null,
    "time": "2023-04-25T05:55:30.302192025Z"
  },
  {
    "messageId": "13396f7c-7edb-4448-9e24-118ff1db9cb8",
    "source": "https://spring.io/foos",
    "type": "io.spring.event.Foo",
    "appId": null,
    "userId": "0c59989d3970380ae168880686c4a070",
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 1100419825169072128,
    "dataContentType": "application/cloudevents+json",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": "\"newFo000000\"",
    "submit": null,
    "time": "2023-04-25T05:55:31.132730690Z"
  },
  {
    "messageId": "9c2f6a75-1cbf-418b-850c-2f3553d259b2",
    "source": "https://spring.io/foos",
    "type": "io.spring.event.Foo",
    "appId": null,
    "userId": "0c59989d3970380ae168880686c4a070",
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 1100419825173266432,
    "dataContentType": "application/cloudevents+json",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": "\"newFo000000\"",
    "submit": null,
    "time": "2023-04-25T05:55:31.133719625Z"
  },
  {
    "messageId": "80d4f8fe-a292-4fba-a20d-6070b3eace3c",
    "source": "https://spring.io/foos",
    "type": "io.spring.event.Foo",
    "appId": null,
    "userId": "0c59989d3970380ae168880686c4a070",
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 1100419825194237952,
    "dataContentType": "application/cloudevents+json",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": "\"newFo000000\"",
    "submit": null,
    "time": "2023-04-25T05:55:31.138491935Z"
  },
  {
    "messageId": "dbd52ac4-1dc7-48b0-bafd-c55a291b7bbd",
    "source": "https://spring.io/foos",
    "type": "io.spring.event.Foo",
    "appId": null,
    "userId": "0c59989d3970380ae168880686c4a070",
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 1100419825198432256,
    "dataContentType": "application/cloudevents+json",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": "\"newFo000000\"",
    "submit": null,
    "time": "2023-04-25T05:55:31.139462712Z"
  },
  {
    "messageId": "53b4d06e-847a-4ac5-9296-eb9e74805d66",
    "source": "https://spring.io/foos",
    "type": "io.spring.event.Foo",
    "appId": null,
    "userId": "0c59989d3970380ae168880686c4a070",
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 1100419825215209472,
    "dataContentType": "application/cloudevents+json",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": "\"newFo000000\"",
    "submit": null,
    "time": "2023-04-25T05:55:31.143814585Z"
  },
  {
    "messageId": "f77f9b84-7fff-484f-90f1-2ee4914602aa",
    "source": "https://spring.io/foos",
    "type": "io.spring.event.Foo",
    "appId": null,
    "userId": "0c59989d3970380ae168880686c4a070",
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 1100419825219403776,
    "dataContentType": "application/cloudevents+json",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": "\"newFo000000\"",
    "submit": null,
    "time": "2023-04-25T05:55:31.144756588Z"
  },
  {
    "messageId": "4bb4a662-a939-4c8c-8ffa-85f4cac98a9d",
    "source": "https://spring.io/foos",
    "type": "io.spring.event.Foo",
    "appId": null,
    "userId": "0c59989d3970380ae168880686c4a070",
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 1100419825236180992,
    "dataContentType": "application/cloudevents+json",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": "\"newFo000000\"",
    "submit": null,
    "time": "2023-04-25T05:55:31.148770435Z"
  },
  {
    "messageId": "d4934cbf-e2f4-4a25-9346-629c5ae8a6d5",
    "source": "https://spring.io/foos",
    "type": "io.spring.event.Foo",
    "appId": null,
    "userId": "0c59989d3970380ae168880686c4a070",
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 1100419825240375296,
    "dataContentType": "application/cloudevents+json",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": "\"newFo000000\"",
    "submit": null,
    "time": "2023-04-25T05:55:31.149618293Z"
  },
  {
    "messageId": "2ea6b2da-0052-4600-a0c7-0260288fe13c",
    "source": null,
    "type": null,
    "appId": null,
    "userId": null,
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 0,
    "dataContentType": "application/octet-stream",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": null,
    "submit": true,
    "time": "2023-04-25T05:55:30.233Z"
  },
  {
    "messageId": "08663e3f-07ea-4a0e-991f-5525653acf16",
    "source": null,
    "type": null,
    "appId": null,
    "userId": null,
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 0,
    "dataContentType": "application/octet-stream",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": null,
    "submit": true,
    "time": "2023-04-25T05:55:30.302Z"
  },
  {
    "messageId": "13396f7c-7edb-4448-9e24-118ff1db9cb8",
    "source": null,
    "type": null,
    "appId": null,
    "userId": null,
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 0,
    "dataContentType": "application/octet-stream",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": null,
    "submit": true,
    "time": "2023-04-25T05:55:31.132Z"
  },
  {
    "messageId": "9c2f6a75-1cbf-418b-850c-2f3553d259b2",
    "source": null,
    "type": null,
    "appId": null,
    "userId": null,
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 0,
    "dataContentType": "application/octet-stream",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": null,
    "submit": true,
    "time": "2023-04-25T05:55:31.133Z"
  },
  {
    "messageId": "80d4f8fe-a292-4fba-a20d-6070b3eace3c",
    "source": null,
    "type": null,
    "appId": null,
    "userId": null,
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 0,
    "dataContentType": "application/octet-stream",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": null,
    "submit": true,
    "time": "2023-04-25T05:55:31.138Z"
  },
  {
    "messageId": "dbd52ac4-1dc7-48b0-bafd-c55a291b7bbd",
    "source": null,
    "type": null,
    "appId": null,
    "userId": null,
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 0,
    "dataContentType": "application/octet-stream",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": null,
    "submit": true,
    "time": "2023-04-25T05:55:31.139Z"
  },
  {
    "messageId": "53b4d06e-847a-4ac5-9296-eb9e74805d66",
    "source": null,
    "type": null,
    "appId": null,
    "userId": null,
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 0,
    "dataContentType": "application/octet-stream",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": null,
    "submit": true,
    "time": "2023-04-25T05:55:31.143Z"
  },
  {
    "messageId": "f77f9b84-7fff-484f-90f1-2ee4914602aa",
    "source": null,
    "type": null,
    "appId": null,
    "userId": null,
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 0,
    "dataContentType": "application/octet-stream",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": null,
    "submit": true,
    "time": "2023-04-25T05:55:31.144Z"
  },
  {
    "messageId": "4bb4a662-a939-4c8c-8ffa-85f4cac98a9d",
    "source": null,
    "type": null,
    "appId": null,
    "userId": null,
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 0,
    "dataContentType": "application/octet-stream",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": null,
    "submit": true,
    "time": "2023-04-25T05:55:31.148Z"
  },
  {
    "messageId": "d4934cbf-e2f4-4a25-9346-629c5ae8a6d5",
    "source": null,
    "type": null,
    "appId": null,
    "userId": null,
    "priority": 0,
    "expiration": null,
    "delay": 0,
    "publishingId": 0,
    "dataContentType": "application/octet-stream",
    "contentEncoding": "text/plain",
    "subject": "message",
    "body": null,
    "submit": true,
    "time": "2023-04-25T05:55:31.149Z"
  }
]
```

##### Response document
```
null
```


