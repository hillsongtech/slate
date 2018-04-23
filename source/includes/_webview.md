## Webview

```json
{
	"id": 1,
	"type": "webview",
	"source_url": "https://github.com", 
	"theme": {
		"container": {
			"flex": 1,
			"height": 300
		},
		"webView": {

		}
	}
}
```

### Query Parameters

Parameter | Type | Description
--------- | ------- | -----------
id | Int | Id related to the module.
type | String | The type of module.
source_url | String | The url of the webpage you would like to display
theme | Object | The theme of the webview referenced below


![module](../images/webview.png)

### Theme Parameters

Parameter | Associated Color Area
--------- | -----------
container | null
webview | null

For this example we are providing a webview that takes up the full container.