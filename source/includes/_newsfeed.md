## NewsFeed

![module](../images/newsfeed.png)

```json

{
	"id": 0,
	"type": "newsfeed",
	"date": "1997-07-16T19:20+01:00",
	"shareMessage": "Share this with your friends",
	"shareUrl": "https://google.com",
	"shareTitle": "Hello World",
	"theme": {
		"container": {

		},
		"shareContainer": {
			"backgroundColor": "#F6F6F6",
			"paddingBottom": 0,
			"paddingTop": 20
		},
		"shareContentContainer": {
			"flex": 2,
			"justifyContent": "flex-start",
			"flexDirection": "row"
		},
		"shareImageContainer": {
			"flex": 1,
			"marginLeft": 20
		},
		"shareImage": {
			"height": 22,
			"width": 16
		},
		"timeAgoContainer": {
			"flex": 1,
			"marginRight": 20
		},
		"timeAgoLabel": {
			"textAlign": "right",
			"color": "#706F70",
			"fontSize": 12
		},
		"separator": {
			"paddingTop": 20,
			"borderBottomColor": "#DFDFDF",
			"borderBottomWidth": 1,
			"marginRight": 20,
			"marginLeft": 20
		},
		"image": {

		},
		"video": {

		},
		"text": {

		}
	},
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
					"flex": 1
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
