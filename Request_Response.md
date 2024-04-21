## Request methods
When we make an HTTP call to a server, we specify a request method that indicates the type of operation we are about to perform. These are also called HTTP verbs.

| Method name |	Operation |
| ------------- | -----------|
| GET	| Retrieve data (Read)|
|POST	|Send data (Create)
|PUT/PATCH|	Update data (Update)
 DELETE| 	Delete data (Delete)

* PUT usually replaces an entire resource, whereas PATCH usually is for partial updates


## Request URL
In addition to a request method, a request must include a request URL that indicates where to make the API call. A request URL has three parts: a protocol (such as http:// or https://), host (location of the server), and path (route on the server).

## Response status codes

|Code range|	Meaning	|Example|
|-----|------|--------|
|2xx	|Success|	200 - OK
|||201 - Created
|||204 - No content (silent OK)
|3xx|	Redirection|	301 - Moved (path changed)|
| 4xx	|Client error	|400 - Bad request
|||401 - Unauthorized
|||403 - Not Permitted
|||404 - Not Found
|5xx|	Server error|	500 - Internal server error
|||502 - Bad gateway
|||504 - Gateway timeout
