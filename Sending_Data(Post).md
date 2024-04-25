### Sending Data(Post):
You will need to send body data with requests whenever you need to add or update structured data.Typically, you will use body data with PUT, POST, and PATCH requests.
* Some APIs require Authorization (aka Auth) for certain endpoints in order to permit a request.

* There are multiple methods for authorizing a request. Some examples are Basic Auth (username and password), OAuth (delegated authorization), and API Keys (secret strings registered to a developer from an API portal). 

#### Headers
Headers are how we can add metadata about our requests, such as authorization information or specify the data type we want to receive in a response. This is different than the actual payload data we send in the body of a request, such as our new book information.

* The Postman Auth helper can help you add authorization at the request, folder or collection level, so api-key doesn't need to be specified in the header(hard coded).
