# search

### Method description

```
search
```

> URL: http://localhost:8080/query/search
>
> Origin Url: http://localhost:8080/query/search
>
> Type: POST


### Request headers

|Header Name| Header Value|
|---------|------|
|Authorization|Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJqdGkiOiI5MTUzYWMzMy1iYTk1LTQxMjktOTZlMy05NmJjNTEwMjJjZWYiLCJpc3MiOiIwYzU5OTg5ZDM5NzAzODBhZTE2ODg4MDY4NmM0YTA3MCIsInN1YiI6IjBjNTk5ODlkMzk3MDM4MGFlMTY4ODgwNjg2YzRhMDcwIiwiZXhwIjoxNjgzNjM5MzU4LCJhdWQiOiJtZnMiLCJzY29wZSI6WyJ1c2VyTWFuIiwiZ2VuZXJhdGVKd3QiLCJzZWFyY2hPbmxpbmUiLCJyb2xlIiwiY29ubmVjdCIsInB1c2giLCJwdWJsaXNoIiwiY29uc3VtZSIsInF1ZXJ5Il19.PeP-drer_ZZnAst-kv-mAi2FAa5oCf28QCHhv_DbPLU|

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
{
  "uid": "PublishRecord",
  "keyword": "foo",
  "offset": 1
}
```

###### JSON document

```
{
	"uid":"No comment,Value =uid_oap3o",
	"offset":"No comment,Value =1",
	"keyword":"No comment,Value =keyword_e9gst"
}
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
{
  "hits": [
    {
      "submit": null,
      "subject": "message",
      "_matchesPosition": {
        "source": [
          {
            "start": 18,
            "length": 3
          }
        ]
      },
      "messageId": "08663e3f-07ea-4a0e-991f-5525653acf16",
      "source": "https://spring.io/foos",
      "type": "io.spring.event.Foo",
      "priority": 0,
      "dataContentType": "application/cloudevents+json",
      "body": "\"newFo000000\"",
      "userId": "0c59989d3970380ae168880686c4a070",
      "delay": 0,
      "appId": null,
      "contentEncoding": "text/plain",
      "expiration": null,
      "publishingId": 1100419821687799808,
      "time": 1.6824021303021922E9
    },
    {
      "submit": null,
      "subject": "message",
      "_matchesPosition": {
        "source": [
          {
            "start": 18,
            "length": 3
          }
        ]
      },
      "messageId": "13396f7c-7edb-4448-9e24-118ff1db9cb8",
      "source": "https://spring.io/foos",
      "type": "io.spring.event.Foo",
      "priority": 0,
      "dataContentType": "application/cloudevents+json",
      "body": "\"newFo000000\"",
      "userId": "0c59989d3970380ae168880686c4a070",
      "delay": 0,
      "appId": null,
      "contentEncoding": "text/plain",
      "expiration": null,
      "publishingId": 1100419825169072128,
      "time": 1.6824021311327307E9
    },
    {
      "submit": null,
      "subject": "message",
      "_matchesPosition": {
        "source": [
          {
            "start": 18,
            "length": 3
          }
        ]
      },
      "messageId": "9c2f6a75-1cbf-418b-850c-2f3553d259b2",
      "source": "https://spring.io/foos",
      "type": "io.spring.event.Foo",
      "priority": 0,
      "dataContentType": "application/cloudevents+json",
      "body": "\"newFo000000\"",
      "userId": "0c59989d3970380ae168880686c4a070",
      "delay": 0,
      "appId": null,
      "contentEncoding": "text/plain",
      "expiration": null,
      "publishingId": 1100419825173266432,
      "time": 1.6824021311337194E9
    },
    {
      "submit": null,
      "subject": "message",
      "_matchesPosition": {
        "source": [
          {
            "start": 18,
            "length": 3
          }
        ]
      },
      "messageId": "80d4f8fe-a292-4fba-a20d-6070b3eace3c",
      "source": "https://spring.io/foos",
      "type": "io.spring.event.Foo",
      "priority": 0,
      "dataContentType": "application/cloudevents+json",
      "body": "\"newFo000000\"",
      "userId": "0c59989d3970380ae168880686c4a070",
      "delay": 0,
      "appId": null,
      "contentEncoding": "text/plain",
      "expiration": null,
      "publishingId": 1100419825194237952,
      "time": 1.682402131138492E9
    },
    {
      "submit": null,
      "subject": "message",
      "_matchesPosition": {
        "source": [
          {
            "start": 18,
            "length": 3
          }
        ]
      },
      "messageId": "dbd52ac4-1dc7-48b0-bafd-c55a291b7bbd",
      "source": "https://spring.io/foos",
      "type": "io.spring.event.Foo",
      "priority": 0,
      "dataContentType": "application/cloudevents+json",
      "body": "\"newFo000000\"",
      "userId": "0c59989d3970380ae168880686c4a070",
      "delay": 0,
      "appId": null,
      "contentEncoding": "text/plain",
      "expiration": null,
      "publishingId": 1100419825198432256,
      "time": 1.6824021311394627E9
    },
    {
      "submit": null,
      "subject": "message",
      "_matchesPosition": {
        "source": [
          {
            "start": 18,
            "length": 3
          }
        ]
      },
      "messageId": "53b4d06e-847a-4ac5-9296-eb9e74805d66",
      "source": "https://spring.io/foos",
      "type": "io.spring.event.Foo",
      "priority": 0,
      "dataContentType": "application/cloudevents+json",
      "body": "\"newFo000000\"",
      "userId": "0c59989d3970380ae168880686c4a070",
      "delay": 0,
      "appId": null,
      "contentEncoding": "text/plain",
      "expiration": null,
      "publishingId": 1100419825215209472,
      "time": 1.6824021311438146E9
    },
    {
      "submit": null,
      "subject": "message",
      "_matchesPosition": {
        "source": [
          {
            "start": 18,
            "length": 3
          }
        ]
      },
      "messageId": "f77f9b84-7fff-484f-90f1-2ee4914602aa",
      "source": "https://spring.io/foos",
      "type": "io.spring.event.Foo",
      "priority": 0,
      "dataContentType": "application/cloudevents+json",
      "body": "\"newFo000000\"",
      "userId": "0c59989d3970380ae168880686c4a070",
      "delay": 0,
      "appId": null,
      "contentEncoding": "text/plain",
      "expiration": null,
      "publishingId": 1100419825219403776,
      "time": 1.6824021311447566E9
    },
    {
      "submit": null,
      "subject": "message",
      "_matchesPosition": {
        "source": [
          {
            "start": 18,
            "length": 3
          }
        ]
      },
      "messageId": "4bb4a662-a939-4c8c-8ffa-85f4cac98a9d",
      "source": "https://spring.io/foos",
      "type": "io.spring.event.Foo",
      "priority": 0,
      "dataContentType": "application/cloudevents+json",
      "body": "\"newFo000000\"",
      "userId": "0c59989d3970380ae168880686c4a070",
      "delay": 0,
      "appId": null,
      "contentEncoding": "text/plain",
      "expiration": null,
      "publishingId": 1100419825236180992,
      "time": 1.6824021311487706E9
    },
    {
      "submit": null,
      "subject": "message",
      "_matchesPosition": {
        "source": [
          {
            "start": 18,
            "length": 3
          }
        ]
      },
      "messageId": "d4934cbf-e2f4-4a25-9346-629c5ae8a6d5",
      "source": "https://spring.io/foos",
      "type": "io.spring.event.Foo",
      "priority": 0,
      "dataContentType": "application/cloudevents+json",
      "body": "\"newFo000000\"",
      "userId": "0c59989d3970380ae168880686c4a070",
      "delay": 0,
      "appId": null,
      "contentEncoding": "text/plain",
      "expiration": null,
      "publishingId": 1100419825240375296,
      "time": 1.682402131149618E9
    }
  ],
  "facetDistribution": null,
  "processingTimeMs": 0,
  "query": "foo",
  "offset": 1,
  "limit": 100,
  "estimatedTotalHits": 10
}
```

##### Response document
```
null
```


