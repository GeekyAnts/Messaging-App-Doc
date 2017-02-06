# Middleware {#express-middleware}

In [middleware functions](http://expressjs.com/en/guide/writing-middleware.html) are functions that have access to the request object \(`req`\), the response object \(`res`\), and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named`next`. How this middleware plays with Feathers [services](https://docs.feathersjs.com/services/readme.html) is outlined below.

### Rendering views

While services primarily provide APIs for a client side application to use, they also play well with [rendering views on the server with Express](http://expressjs.com/en/guide/using-template-engines.html). For more details, please refer to the [Using a View Engine](https://docs.feathersjs.com/guides/using-a-view-engine.html) guide.

### Routing & versioning

 In general, Feathers does not know about associations between your services. Services are usually connected by their ids so any nested route can also be expressed by query parameters. For example if you have a user service and would like to get all todos \(assuming the associated user id is stored in each todo\), for that user the url would be

`/todos?user_id= < userid >`

. This approach also makes it easier to use by non REST providers like websockets and any other protocols Feathers might support in the future.

