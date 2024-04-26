### Scripting in Postman
Postman allows you to add automation and dynamic behaviors to your collections with scripting.

Postman will automatically execute any provided scripts during two events in the request flow:

* Immediately before a request is sent: pre-request script (Pre-request Script tab of request).
* Immediately after a response comes back: test script (Tests tab of request).

<strong>Postman has a helper object named pm that gives you access to data about your Postman environment, requests, responses, variables and testing utilities. </strong>

To set a collection variable, use the `.set()` method with two parameters: the variable name and the variable value:

` pm.collectionVariables.set("variableName", value) `

To get a collection variable use the `.get()` method and specify the name of the variable you want to retrieve:

`pm.collectionVariables.get("variableName")`
