# App

## Get all App Information

```json
{
  "appName": "Example App",
  "appVersion": "1.0.0",
  "sideMenu": {},
  "tabBar": {},
  "mainTheme": {},
  "pages": []
}
```

This endpoint retrieves all of the app information.

### HTTP Request

`GET http://example.com/api/app/appid`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
include_cats | false | If set to true, the result will also include cats.
available | true | If set to false, the result will include kittens that have already been adopted.

<aside class="success">
Remember — a happy kitten is an authenticated kitten!
</aside>