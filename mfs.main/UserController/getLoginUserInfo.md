# getLoginUserInfo

### Method description

```
getLoginUserInfo
```

> URL: http://localhost:8080/user/getLoginUserInfo
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
{
	"code":"No comment,Type =Number",
	"data":{
		"note":"No comment,Type =String",
		"creator":"No comment,Type =String",
		"loginTime":"No comment,Type =String",
		"deleted":"No comment,Type =Boolean",
		"createTime":"No comment,Type =String",
		"nickname":"用户昵称",
		"id":"ID",
		"type":"No comment,Type =Boolean",
		"username":"用户名",
		"updater":"No comment,Type =String",
		"lastUpdateTime":"No comment,Type =String"
	},
	"message":"No comment,Type =String"
}
```


