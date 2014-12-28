jsonschema-TwitterCard
======================

Twitter Card meta data in JSON Schema v4

```json
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "id": "https://dev.twitter.com/cards/overview",
    "title": "TwitterCards",
    "name": "TwitterCards",
    "description": "With Twitter Cards, you can attach rich photos, videos and media experience to Tweets that drive traffic to your website. Simply add a few lines of HTML to your webpage, and users who Tweet links to your content will have a “Card” added to the Tweet that’s visible to all of their followers.",
    "properties": {
        "twitter:card": {
            "title": "twitter:card",
            "description": "The card type",
            "type": "string"
        },
        "twitter:site": {
            "title": "twitter:site",
            "description": "@username of website",
            "type": "string"
        },
        "twitter:site:id": {
            "title": "twitter:site:id",
            "description": "Same as twitter:site, but the user’s Twitter ID",
            "type": "string"
        },
        "twitter:creator": {
            "title": "twitter:creator",
            "description": "@username of content creator",
            "type": "string"
        },
        "twitter:creator:id": {
            "title": "twitter:creator:id",
            "description": "Twitter user ID of content creator",
            "type": "string"
        },
        "twitter:description": {
            "title": "twitter:description",
            "description": "Description of content (maximum 200 characters)",
            "type": "string"
        },
        "twitter:title": {
            "title": "twitter:title",
            "description": "Title of content (max 70 characters)",
            "type": "string"
        },
        "twitter:image:src": {
            "title": "twitter:image:src",
            "description": "URL of image to use in the card. Image must be less than 1MB in size",
            "type": "string",
            "format": "uri"
        },
        "twitter:image:width": {
            "title": "twitter:image:width",
            "description": "Width of image in pixels",
            "type": "number"
        },
        "twitter:image:height": {
            "title": "twitter:image:height",
            "description": "Height of image in pixels",
            "type": "number"
        },
        "twitter:image0": {
            "title": "twitter:image0",
            "description": "1st, 2nd, 3rd, and 4th image in the gallery, respectively. Images must be less than 1MB in size",
            "type": "string",
            "format": "uri"
        },
        "twitter:image1": {
            "title": "twitter:image1",
            "description": "1st, 2nd, 3rd, and 4th image in the gallery, respectively. Images must be less than 1MB in size",
            "type": "string",
            "format": "uri"
        },
        "twitter:image2": {
            "title": "twitter:image2",
            "description": "1st, 2nd, 3rd, and 4th image in the gallery, respectively. Images must be less than 1MB in size",
            "type": "string",
            "format": "uri"
        },
        "twitter:image3": {
            "title": "twitter:image3",
            "description": "1st, 2nd, 3rd, and 4th image in the gallery, respectively. Images must be less than 1MB in size",
            "type": "string",
            "format": "uri"
        },
        "twitter:player": {
            "title": "twitter:player",
            "description": "HTTPS URL of player iframe",
            "type": "string",
            "format": "uri"
        },
        "twitter:player:width": {
            "title": "twitter:player:width",
            "description": "Width of iframe in pixels",
            "type": "number"
        },
        "twitter:player:height": {
            "title": "twitter:player:height",
            "description": "Height of iframe in pixels",
            "type": "number"
        },
        "twitter:player:stream": {
            "title": "twitter:player:stream",
            "description": "URL to raw video or audio stream",
            "type": "string",
            "format": "uri"
        },
        "twitter:data1": {
            "title": "twitter:data1",
            "description": "Top customizable data field, can be a relatively short string (ie “$3.99”)",
            "type": "string"
        },
        "twitter:label1": {
            "title": "twitter:label1",
            "description": "Customizable label or units for the information in twitter:data1 (best practice: use all caps)",
            "type": "string"
        },
        "twitter:data2": {
            "title": "twitter:data2",
            "description": "Bottom customizable data field, can be a relatively short string (ie “Seattle, WA”)",
            "type": "string"
        },
        "twitter:label2": {
            "title": "twitter:label2",
            "description": "Customizable label or units for the information in twitter:data1 (best practice: use all caps)",
            "type": "string"
        },
        "twitter:app:name:iphone": {
            "title": "twitter:app:name:iphone",
            "description": "Name of your iPhone app",
            "type": "string"
        },
        "twitter:app:id:iphone": {
            "title": "twitter:app:id:iphone",
            "description": "Your app ID in the iTunes App Store (Note: NOT your bundle ID)",
            "type": "string"
        },
        "twitter:app:url:iphone": {
            "title": "twitter:app:url:iphone",
            "description": "Your app’s custom URL scheme (you must include “://” after your scheme name)",
            "type": "string"
        },
        "twitter:app:name:ipad": {
            "title": "twitter:app:name:ipad",
            "description": "Name of your iPad optimized app",
            "type": "string"
        },
        "twitter:app:id:ipad": {
            "title": "twitter:app:id:ipad",
            "description": "Your app ID in the iTunes App Store",
            "type": "string"
        },
        "twitter:app:url:ipad": {
            "title": "twitter:app:url:ipad",
            "description": "Your app’s custom URL scheme",
            "type": "string"
        },
        "twitter:app:name:googleplay": {
            "title": "twitter:app:name:googleplay",
            "description": "Name of your Android app",
            "type": "string"
        },
        "twitter:app:id:googleplay": {
            "title": "twitter:app:id:googleplay",
            "description": "Your app ID in the Google Play Store",
            "type": "string"
        },
        "twitter:app:url:googleplay": {
            "title": "twitter:app:url:googleplay",
            "description": "Your app’s custom URL scheme",
            "type": "string"
        }
    }
}
```

Reference
---

- http://json-schema.org/
- https://dev.twitter.com/cards/types/app
