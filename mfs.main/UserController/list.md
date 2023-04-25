# list

### Method description

```
list
```

> URL: http://localhost:8080/user/list
>
> Origin Url: http://localhost:8080/user/list
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
  "keyword": "",
  "roleId": "",
  "pageSize": 10,
  "pageNum": 1
}
```

###### JSON document

```
{
	"roleId":"No comment,Value =roleId_s46zi",
	"pageSize":"No comment,Value =1",
	"keyword":"No comment,Value =keyword_ec6tt",
	"pageNum":"No comment,Value =1"
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
  "data": {
    "records": [
      {
        "id": "0c59989d3970380ae168880686c4a070",
        "username": "root",
        "nickname": "root",
        "creator": null,
        "createTime": "2023-04-02 17:40:20",
        "updater": null,
        "lastUpdateTime": "2023-04-02 17:43:33",
        "loginTime": "2023-04-02 17:43:33",
        "type": false,
        "note": null,
        "deleted": false
      }
    ],
    "total": 1,
    "size": 10,
    "current": 1,
    "orders": [],
    "optimizeCountSql": true,
    "searchCount": true,
    "maxLimit": null,
    "countId": null,
    "pages": 1
  }
}
```

##### Response document
```
{
	"code":"No comment,Type =Number",
	"data":{
		"total":"No comment,Type =Number",
		"current":"No comment,Type =Number",
		"size":"No comment,Type =Number",
		"optimizeCountSql":"No comment,Type =Boolean",
		"records":[
			{
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
			}
		],
		"maxLimit":"No comment,Type =Number",
		"searchCount":"No comment,Type =Boolean",
		"optimizeJoinOfCountSql":"No comment,Type =Boolean",
		"orders":[
			{
				"asc":"No comment,Type =Boolean",
				"column":"No comment,Type =String"
			}
		],
		"countId":"No comment,Type =String"
	},
	"message":"No comment,Type =String"
}
```


