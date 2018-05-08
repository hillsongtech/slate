## BioMini

![module](../images/minibio.png)

```json
{
	"id": 1,
	"type": "bioMini",
	"name": "Brian Houston",
	"title": "Global Lead Pastor",
	"organization": "Hillsong Church",
	"description": "As a leader, Pastor Brian Houston is highly regarded for his boldness, innovation and vision. As a church pastor, he is well respected for his passion for the cause of Christ and the local church, and for preaching messages that change mindsets and..",
	"source_url": "https://www.premierproductions.com/sites/default/files/styles/500w/public/artists/brian_houston_-_cropped_2015_photo.jpg",
	"links_to": 3,
	"theme": {
		"container": {
			"paddingTop": 12
		},
		"contentContainer": {
			"marginLeft": 40,
			"marginRight": 40
		},
		"topContainer": {
			"justifyContent": "flex-start",
			"flexDirection": "row",
			"position": "relative",
			"paddingBottom": 10
		},
		"imageContainer": {
			"marginRight": 10
		},
		"image": {
			"width": 70,
			"height": 70,
			"borderRadius": 35
		},
		"titleContainer": {
			"flexDirection": "column",
			"justifyContent": "center"
		},
		"name": {
			"color": "white",
			"fontSize": 18,
			"fontWeight": "900"
		},
		"title": {
			"color": "white",
			"fontSize": 14,
			"fontWeight": "bold"
		},
		"organization": {
			"color": "white",
			"fontSize": 12
		},
		"descriptionContainer": {
		},
		"descriptionText": {
			"color": "white",
			"fontSize": 12Í
		},
		"readMoreContainer": {
			"flex": 1,
			"alignItems": "flex-end",
			"paddingTop": 10
		},
		"readMoreText": {
			"color": "white",
			"fontSize": 12,
			"alignSelf": "flex-end",
			"fontStyle": "italic",
			"fontWeight": "700"
		},
		"separator": {
			"paddingTop": 20,
  		"borderBottomWidth": 1,
    	"borderBottomColor": "white"
		}
	}
```

### Query Parameters

Parameter | Type | Description
--------- | ------- | -----------
id | Int | Id related to the module.
type | String | The type of module.
name | String | The top title string
title | String | The middle title string
organization | String | The last title string
description | String | The paragraph description
source_url | String | The url of the image you would like to display
links_to | Int | The "page" you would like the read more button to link to
theme | Object | The theme of the minibio referenced below

### Theme Parameters

Parameter | Associated Color Area
--------- | -----------
container | Blue
contentContainer | Green
topContainer | Red
imageContainer | Pink
image | null
titleContainer | Purple
name | null
title | null
organization | null
descriptionContainer | null
descriptionText | null
readMoreContainer | null
readMoreText | null
separator | White


### Default Theme

![module](../images/defaultthememinibio.png)
