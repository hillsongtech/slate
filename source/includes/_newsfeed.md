## NewsFeed

![module](../images/newsfeed.png)

```json
{
	"id": 0,
	"type": "newsfeed",
	"date": "1997-07-16T19:20+01:00", // Need to come back and implement
	"share_content": "Share this with your friends", // Need to come back and implement
	"content": [
		{
			"id": 1,
			"type": "image",
			"title": "",
			"source_url": "http://www.latimes.com/resizer/EQ3qC0FZL73_8GGEwU9Frs5b2cI=/1400x0/arc-anglerfish-arc2-prod-tronc.s3.amazonaws.com/public/KGLW5PUC65HMZK3LHRCZ45IMWY.jpg",
			"links_to": null, 
			"theme": {
				"container": {
					"flexDirection": "row",
					"height": 300,
					"justifyContent": "center",
					"alignItems": "center"
				},
				"image": {
					"height": 300,
					"flex": 1,
					"width": null,
					"marginRight": 0,
					"marginLeft": 0,
					"marginTop": 0,
					"marginBottom": 0,
					"borderRadius": 0
				}
			}
		},
		{
			"id": 2,
			"type": "label",
			"content": "Welcome to Hillsong Conference 2018!",
			"theme": {
				"container": {
					"flex": 1,
					"backgroundColor": "#F6F6F6"
				},
				"text": {
					"fontWeight": "900",
					"color": "#191A1A",
					"fontSize": 24,
					"marginLeft": 20,
					"marginRight": 20,
					"paddingTop": 12
				}
			}
		}
	]
}
```

### Query Parameters

Parameter | Type | Description
--------- | ------- | -----------
id | Int | Id related to the module.
type | String | The type of module.
date | String | The date of the newsfeed post. So we can display "time ago"
share_content | String | The content you would like users to "share"
content | Array | An array of other modules that you would like inside the newsfeed module. Usually image + text, or just video.