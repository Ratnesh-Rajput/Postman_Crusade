## Variables
Variables enable you to store and reuse values in Postman. By storing a value as a variable, you can reference it throughout your collections, environments, requests, and test scripts. - 

 1. Global variables enable you to access data between collections, requests, test scripts, and environments. Global variables are available throughout a workspace
 2. Collection variables are available throughout the requests in a collection and are independent of environments. Collection variables don't change based on the selected environment.
 3. Environment variables enable you to scope your work to different environments, for example local development versus testing or production.
 4. Data variables come from external CSV and JSON files to define data sets you can use when running collections with Newman or the Collection Runner.
 5. Local variables are temporary variables that are accessed in your request scripts.

 ### Variable Values:
 <strong >Initial Value </strong> - the value initially set when someone forks or imports your collection. Note that if you share your collection with others, they will see this value, so don't put any secrets here!

<strong> Current Value </strong>- Postman always resolves the variable to this value. This is local to your Postman account, and not public. It is good to keep secrets like API Keys ONLY in this column and not include them in the Initial Value column.
