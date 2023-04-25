# update

### Method description

```
update
```

> URL: http://localhost:8080/user/update
>
> Origin Url: http://localhost:8080/user/update
>
> Type: POST


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
{
  "id": "0a30044edb19099f6e00e4593ed3fb42",
  "username": "test1",
  "nickname": "test1",
  "createTime": "2023-04-25 10:49:50",
  "lastUpdateTime": "2023-04-25 10:49:50",
  "note": "test1"
}
```

###### JSON document

```
{
	"note":"No comment,Value =note_l7iws",
	"creator":"No comment,Value =creator_gtlqr",
	"loginTime":"No comment,Value =2023-04-25 10:53:06",
	"deleted":"No comment,Value =true",
	"createTime":"No comment,Value =2023-04-25 10:53:06",
	"nickname":"用户昵称",
	"id":"ID",
	"type":"No comment,Value =true",
	"username":"用户名",
	"updater":"No comment,Value =updater_q3469",
	"lastUpdateTime":"No comment,Value =2023-04-25 10:53:06"
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
  "code": 200,
  "message": "操作成功",
  "data": "修改成功"
}
```

##### Response document
```
null
```


