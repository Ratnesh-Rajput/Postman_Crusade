# API and Postman:
--An Application Programming Interface (API) is a contract that allows code to talk/interact with other code. 
--"API" can apply to a broad range of interfaces.

    Hardware APIs
    Interface for software to talk to hardware.
    Example: How your phone's camera talks to the operating system. 

    Software Library APIs
    Interface for directly consuming code from another code base.
    
    Web APIs
    Interface for communicating across code bases over a network.

-- There is more than one way to build and consume APIs. Some architecture types you may come across are:

    REST (Representational State Transfer):
        REST APIs are designed to make server-side data readily available by representing it in simple formats such as JSON and XML. The acronym stands for   REpresentational State Transfer.Some traits of REST APIs include not storing session state between requests, the ability to cache, and the ability to send and receive various data types.
    GraphQL
    WebSockets
    webhooks
    SOAP (Simple Object Access Protocol)
    gRPC (Google Remote Procedure Call)
    MQTT (MQ Telemetry Transport)


    <!-- https://voyager.postman.com/illustration/what-is-postman-illustration-4.svg -->

   --Before Postman, it was common practice to poke at APIs with a command line tool for making HTTP requests called cURL. Eg: curl https://api.github.com/users/postmanlabs

<p> =>It works great, but once you make the call, the API response data is lost in the river of the terminal. You also don't have visibility of the metadata of the response without adding more details to the command. </p>
    
 ### Postman agent
   <p> The Postman agent is a micro-application that runs locally on your desktop and acts as your agent for making API calls on your behalf. To overcome limits in the browser, the Postman web interface will now route  API calls to the local agent, and the agent will make API requests locally on your behalf, using your local profile, configuration, and network to make each request and pass the response back to the web interface. </p>

-----------------------------------------------------------------------------------------------
Notes Flow:
1. Introduction(Readme.md)
2. Request_Response.md
3. Variables.md
4. Query-and-Path-parameters
5. Sending_Data.md
