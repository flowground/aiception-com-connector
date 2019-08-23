# ![LOGO](logo.png) AIception Interactive **flow**ground Connector

## Description

A generated **flow**ground connector for the AIception Interactive API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/aiception.com/1.0.0/swagger.json<br/>
Generated at: 2019-08-14T12:19:51+03:00

## API Description

Here you can play & test & prototype all the endpoints using just your browser! Go ahead!<br/>

## Authorization

Supported authorization schemes:
- Basic Authentication

## Actions

### Image contains nudity or sexually explicit content? [ image_url -> id ]
> Creates a new adult_content task that tells the if the image has nudity or sexual content.<br/>

*Tags:* `vision`

### Gets the adult_content task [ id -> adult content task ]
> Gets the adult_content task.<br/>

*Tags:* `vision`

#### Input Parameters
* `taskId` - _required_ - An internal id for the task<br/>

### Create an artistic image [ image_url, style_url -> id ]
> Given an image content and a style image create a new stylized image of the content.<br/>

*Tags:* `creative`

### Gets a artistic image by task id [ id -> artistic image task ]
> The artistic_image will have the urls of the stylized images.<br/>

*Tags:* `creative`

#### Input Parameters
* `taskId` - _required_ - An internal id for the task<br/>

### What is that object? [ image_url -> id ]
> Creates a new detect object task that recognizes the object in the image.<br/>

*Tags:* `vision`

### Gets the detect_object task [ id -> detect object task]
> Gets the detect_object task.<br/>

*Tags:* `vision`

#### Input Parameters
* `taskId` - _required_ - An internal id for the task<br/>

### Find all faces in the image [ image_url -> id ]
> Get a list of all the locations of the faces in the image.<br/>

*Tags:* `vision`

### Gets the face task [ id -> face task ]
> Gets the face task.<br/>

*Tags:* `vision`

#### Input Parameters
* `taskId` - _required_ - An internal id for the task<br/>

### How old is the person in the image? [ image_url -> id ]
> Creates a new face age task that approximates the age of the person in the image.<br/>

*Tags:* `vision`

### Gets the face_age task [ id -> face age task ]
> Gets the face_age task.<br/>

*Tags:* `vision`

#### Input Parameters
* `taskId` - _required_ - An internal id for the task<br/>

## License

**flow**ground :- Telekom iPaaS / aiception-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
