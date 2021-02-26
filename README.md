MarsRealEstate
==============

Introduction
------------

MarsRealEstate is a demo app that shows available properties for sale and for rent on Mars.
The property data is stored on a Web server as a REST web service.  This app demonstrated
the use of
- [Retrofit](https://square.github.io/retrofit/) to make REST requests to the web service
- [Moshi](https://github.com/square/moshi) to handle the deserialization of the returned JSON to Kotlin data objects
- [Glide](https://bumptech.github.io/glide/) to load and cache images by URL.