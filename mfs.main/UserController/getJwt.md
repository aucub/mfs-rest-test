# getJwt

### Method description

```
得到Jwt
```

> URL: http://localhost:8080/user/getJwt
>
> Origin Url: http://localhost:8080/user/getJwt
>
> Type: POST


### Request headers

|Header Name| Header Value|
|---------|------|
|token|39908c5f-83cb-41db-8dd2-1eae7f90b8ad|

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
|true|jwtId|String|jwtId_94lr2||
|true|issuer|String|issuer_7hxab||
|true|subject|String|subject_3wpuw||
|true|expiresAt.seconds|Number|1||
|true|expiresAt.nanos|Number|1||
|true|audience|String|audience_kb11g||
|true|authorities[0]|String|authorities_92m0d||


##### Multipart
|Required | Parameter | Type | Value | Description |
|---------|---------|------|------|------------|


### Response

##### Response example

```

```

##### Response document
```
{
	"code":"No comment,Type =Number",
	"data":{
		"java.lang.String":"No comment,Type =String"
	},
	"message":"No comment,Type =String"
}
```


