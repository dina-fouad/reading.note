## APIs

- What does REST stand for?

Representational State Transfer and its designed to take advantage of existing protocols.

- REST APIs are designed around a ____.

API'S designed to take advantage of existing protocols but REST can be used over nearly any protocol.

- What is an identifer of a resource? Give an example.

ID resource is a simple resource defined in XML that provides a unique identifier for other project resources.


- What should the URIs be based on?

URI provides a method for resources to be accessed by other systems over the World Wide Web or across a network.

- Give an example of a good URI.

URIs should follow a predictable, hierarchical structure to enhance understandability .

- What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

All web requests impose a load on the web server. The more requests, the bigger the load. Therefore, try to avoid "chatty" web APIs that expose a large number of small resources. Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource.

- What status code does a successful GET request return?

A successful GET method typically returns HTTP status code 200 (OK). If the resource cannot be found, the method should return 404 (Not Found).

- What status code does an unsuccessful GET request return?

resource cannot be found, the method should return 404 (Not Found).

- What status code does a successful POST request return?

POST request the response will contain an entity describing or containing the result of the action, POST method creates a new resource, it returns HTTP status code 201 .

- What status code does a successful DELETE request return?

 there are several response status codes possible: A 202 ( Accepted) and not yet been enacted. A 204 ( No Content )