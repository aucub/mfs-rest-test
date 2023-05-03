# updatePassword

### Method description

```
updatePassword
```

> URL: http://localhost:8080/login/updatePassword?tokenValue=tokenValue_k1ntk&issuedAt.seconds=1&issuedAt.nanos=1&expiresAt.seconds=1&expiresAt.nanos=1
>
> Origin Url: http://localhost:8080/login/updatePassword
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
|true|tokenValue|String|tokenValue_k1ntk||
|true|issuedAt.seconds|Number|1||
|true|issuedAt.nanos|Number|1||
|true|expiresAt.seconds|Number|1||
|true|expiresAt.nanos|Number|1||


##### Body parameters

###### JSON

```
{
  "oldPassword": "root",
  "newPassword": "rootroot"
}
```

###### JSON document

```
{
	"oldPassword":"No comment,Value =oldPassword_6zkhf",
	"newPassword":"No comment,Value =newPassword_73nor",
	"id":"No comment,Value =id_zk73p"
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
  "data": "修改密码成功"
}
```

##### Response document
```
null
```


