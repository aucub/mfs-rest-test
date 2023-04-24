# getLoginUserInfo

### Method description

```
getLoginUserInfo
```

> URL: http://localhost:8080/user/getLoginUserInfo?tokenValue=tokenValue_a9ed4&issuedAt.seconds=1&issuedAt.nanos=1&expiresAt.seconds=1&expiresAt.nanos=1
>
> Origin Url: http://localhost:8080/user/getLoginUserInfo
>
> Type: GET


### Request headers

|Header Name| Header Value|
|---------|------|
|Authorization|Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJqdGkiOiI2ODA1OTA1Yi1kZTk5LTQzMDQtOTI2OC04YTQzYjM1YzI2YmQiLCJpc3MiOiIwYzU5OTg5ZDM5NzAzODBhZTE2ODg4MDY4NmM0YTA3MCIsInN1YiI6IjBjNTk5ODlkMzk3MDM4MGFlMTY4ODgwNjg2YzRhMDcwIiwiZXhwIjoxNjgyOTU4NjMxLCJhdWQiOiJtZnMiLCJzY29wZSI6WyJ1c2VyTWFuIiwiZ2V0Snd0IiwiZ2VuZXJhdGVKd3QiLCJzZWFyY2hTZXNzaW9uIiwicm9sZSIsImtpY2tvdXQiLCJkaXNhYmxlIiwiY29ubmVjdCIsInB1c2giLCJwdWJsaXNoIiwiY29uc3VtZSIsInF1ZXJ5Il19.b12uFC0KnAoNCtcgJknhoxJoQ8RxJHexMyLBRoFHroo|

### Parameters

##### Path parameters

| Parameter | Type | Value | Description |
|---------|------|------|------------|


##### URL parameters

|Required| Parameter | Type | Value | Description |
|---------|---------|------|------|------------|
|true|tokenValue|String|tokenValue_a9ed4||
|true|issuedAt.seconds|Number|1||
|true|issuedAt.nanos|Number|1||
|true|expiresAt.seconds|Number|1||
|true|expiresAt.nanos|Number|1||


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
{
  "code": 200,
  "message": "操作成功",
  "data": {
    "id": null,
    "username": null,
    "nickname": null,
    "creator": null,
    "createTime": null,
    "updater": null,
    "lastUpdateTime": null,
    "loginTime": null,
    "type": null,
    "note": null,
    "deleted": null
  }
}
```

##### Response document
```
null
```


