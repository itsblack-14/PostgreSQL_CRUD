Post Request / Response
----------------------------------------
```json
{
  "name": "Zin Ko",
  "email": "zinko@gmail.com",
  "dateOfBirth": "2002-03-19T00:00:00Z"
}
```
```json
{
  "statusCode": 200,
  "message": "Success",
  "ref": "1"
}
```

Get Response
----------------------------------------
```json
{
  "students": [
    {
      "id": 1,
      "name": "Zin Ko",
      "email": "zinko@gmail.com",
      "dateOfBirth": "2002-03-19T00:00:00Z"
    }
  ],
  "totalItems": 1,
  "statusCode": 200,
  "message": "Success",
  "ref": null
}
```

Get{id} Response
----------------------------------------
```json
{
  "id": 1,
  "name": "Zin Ko",
  "email": null,
  "dateOfBirth": "2002-03-19T00:00:00Z",
  "statusCode": 200,
  "message": "Success",
  "ref": null
}
```

Put{id} Request / Response
----------------------------------------
```json
{
  "name": "Zin Ko Ko",
  "email": "zinkoko@gmail.com",
  "dateOfBirth": "2002-03-19T14:13:55.458Z"
}
```
```json
{
  "statusCode": 200,
  "message": "Success",
  "ref": "1"
}
```

Patch{id} Request / Response
----------------------------------------
```json
[
  {
    "path": "name",
    "op": "replace",
    "value": "Zin Ko"
  },
  {
    "path": "email",
    "op": "replace",
    "value": "zinko@gmail.com"
  }
]
```
```json
{
  "statusCode": 200,
  "message": "Success",
  "ref": "1"
}
```

Delete{id} Response
----------------------------------------
```json
{
  "statusCode": 200,
  "message": "Success",
  "ref": null
}
```


