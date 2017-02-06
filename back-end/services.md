# Services {#services}

Services are the heart of every Feathers application. They perform the application-level i/o, helping you get data into and out of your app.

A service is simply a JavaScript object that offers one or more of the available service methods:

* `find`
* `get`
* `create`
* `update`
* `patch`
* `remove`
* `setup`

Services can be used just like an [Express middleware](http://expressjs.com/en/guide/using-middleware.html):

There are three common uses for services:

1. Facilitating Data Storage
2. Communicating with an External API
3. Real-time proxying a legacy server.

  


