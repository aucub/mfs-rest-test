# generateJwt

### Method description

```
generateJwt
```

> URL: http://localhost:8080/user/generateJwt?tokenValue=tokenValue_x7mni&issuedAt.seconds=1&issuedAt.nanos=1&expiresAt.seconds=1&expiresAt.nanos=1
>
> Origin Url: http://localhost:8080/user/generateJwt
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
|true|tokenValue|String|tokenValue_x7mni||
|true|issuedAt.seconds|Number|1||
|true|issuedAt.nanos|Number|1||
|true|expiresAt.seconds|Number|1||
|true|expiresAt.nanos|Number|1||


##### Body parameters

###### JSON

```
{
  "jwtId": "jwtId_z9l97",
  "issuer": "root",
  "subject": "test1",
  "expiresAt": 1,
  "audience": "mfs"
}
```

###### JSON document

```
{
	"audience":"No comment,Value =audience_y0bah",
	"subject":"No comment,Value =subject_w49oi",
	"issuer":"No comment,Value =issuer_3b3bp",
	"expiresAt":{
		"seconds":"No comment,Value =1",
		"nanos":"No comment,Value =1"
	},
	"authorities":[
		"No comment,Value =authorities_dr83y"
	],
	"jwtId":"No comment,Value =jwtId_z9l97"
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
  "data": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJqdGkiOiI2OWJiYmY3MS0zMmY2LTQ5YzAtYWZmOS00NjY2YzgzYmE0MWQiLCJpc3MiOiIwYzU5OTg5ZDM5NzAzODBhZTE2ODg4MDY4NmM0YTA3MCIsInN1YiI6InRlc3QxIiwiZXhwIjoxLCJhdWQiOiJtZnMiLCJzY29wZSI6WyJ1c2VyTWFuIiwiZ2V0Snd0IiwiZ2VuZXJhdGVKd3QiLCJzZWFyY2hTZXNzaW9uIiwicm9sZSIsImtpY2tvdXQiLCJkaXNhYmxlIiwiY29ubmVjdCIsInB1c2giLCJwdWJsaXNoIiwiY29uc3VtZSIsInF1ZXJ5Il19.8Af1ne_tRq5Ezf54XU1Bx1WUET1uV3bZkfoyo7WIzl0"
}
```

##### Response document
```
null
```


