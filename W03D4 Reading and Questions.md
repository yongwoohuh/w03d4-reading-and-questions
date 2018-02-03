# W03D4 Reading and Questions

-core data
Q1.
You can recall the CRUD acronym from core data. What HTTP verbs or "methods" (get, post, delete, put) relate to which of the functions in CRUD (create, read, update, delete)
- create - post
- read - get
- update - put
- delete - delete
[www.restapitutorial.com/lessons/httpmethods.html]
Q2.
What do the following common HTTP status codes mean? How would you handle each result after receiving it from your webservice, ie, you made a request and received this status code. What do you do now? 
	a.200  OK: save data from request.
	b.403 Forbidden: check server account setting.
	c.401 Unauthorized: check credentials
	d.500 Internal Server Error: check web service status.
	e.404 Not Found: check web services URL
	 f.408  Request Timeout: check internet connectivity.

Q3.
What is an HTTP header field? Describe these commonly used fields and what data is passed in them.

	a. User-Agent : contains information about the user agent originating the request.(usually web browser version and OS version)
	b. Authorization : consists of credentials containing the authentication information of the user agent
	c. Accept : specify certain media types which are acceptable for the response
	d. Content-Type: the media type of the entity-body sent to the recipient

Q4.
What is an API and what does it stand for? What does RESTful mean as it relates to an API?
API :  Is the part of the server that receives requests and sends responses. (public methods of a server or web service.)
[What is an API? In English, please. – freeCodeCamp](https://medium.freecodecamp.org/what-is-an-api-in-english-please-b880a3214a82)
[What is an API? - Quora](https://www.quora.com/What-is-an-API-4?share=1)

What does RESTful mean as it relates to an API?
an API that has Clent-server, Stateless, Casheable features can be considered RESTful API.
www.restapitutorial.com/lessons/whatisrest.html
[Do you know what a REST API is? — SitePoint](https://www.sitepoint.com/developers-rest-api/)

Q5.
What is JSON? 
JSON is a simple, text-based way to store and transmit structured data. 
I am writing an API for my pizza company. In raw JSON data, a pizza is represented by JSON data similar to this:

{ "id": 1, "name": "Lighthouse Labs Special", “size”: “large”, “price”: “11.00”, ”toppings": ["mushrooms", "pepperoni"] }

But we forgotten to add some fields like the size of the pizza, price of the pizza, and crust type. What would the JSON data look like after adding these fields? What other fields might our pizza object have? How might we represent a customer object in our API? 
each customer can have an ID linked with them. have an entry for order completion.