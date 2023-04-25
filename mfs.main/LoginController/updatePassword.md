# updatePassword

### Method description

```
updatePassword
```

> URL: http://localhost:8080/login/updatePassword
>
> Origin Url: http://localhost:8080/login/updatePassword
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
{
  "username": "root",
  "oldPassword": "root",
  "newPassword": "root1"
}
```

###### JSON document

```
{
	"oldPassword":"No comment,Value =oldPassword_utije",
	"newPassword":"No comment,Value =newPassword_bw8wq",
	"username":"No comment,Value =username_utr63"
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


