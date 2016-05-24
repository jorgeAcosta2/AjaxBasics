# Notes
### Here are some notes that I have taken throughout my Ajax Journey.

* **Ajax**: Asynchronous JavaScript and XML.
* Request: Asking server for information.
* Response: Server sends information/response back.
* XMLHttpRequestObject(XHR): Basically, Ajax.
* Use JavaScript to send Request to web server, receive a Response back, and do something with that Response.
* How Ajax works
 1. Create an XMLHTTP Request Object: To send an AJAX request, the web browser needs to create an object that has all the methods you'll need to send and receive data.
 2. Define a callback function: Code to run when server returns it's response.
 3. Open a Request(GET/POST).
 4. Send the Request.
* Callback function gets triggered by an event 
* onreadystatechange: triggered when there is a change in a Ajax request
* .responseText: information that the web server sends back
* callback doesn't run until response comes back from the server
* .open(): prepares browser for sending a/the request. Takes two arguments(Http Method, URL)
* .open() only prepares the broswer for sending the request but does not actually send it
* Most common Http Methods: (GET/POST) (Of course there are others.)
* GET: Send request for data
* POST: Sending data for server to save in a database
* .send() sends the request
* Query String: information at the end of a URL
* GET uses Query Strings
* POST sends data seperate from the url in the body of the request
 * POST needs a header for the request, the header contains instructions sent to the server telling the server what type of data to expect.
* After sending an Ajax request, callback function waits for a response.
* Server usually replies to Ajax request with a text response.
* Same Origin Policy: Controls how javascript can access content from a web server. Using Ajax on same web server is ok, using Ajax for communicating with another server causes problems. Here are some issues.
 * requesting data from another server
 * switching protocols 
 * switching port numbers
 * switching hosts
* Ways to get around the Same Origin Policy.
 * Web proxy
 * JSONP: JSON with Padding
 * CORS: Cross-Origin Resource Sharing
* Ajax only works in a web server
* Valid JSON requires double quotes 
* Parsing: Converting JSON data to JavaScript
* "type of" operator determines what type of JavaScript Element something is
* JSON.parse() attempts to convert JSON string into a JavaScript Object
* Arrays are considered a type of object in JavaScript
 
 
 
 
 
 
 
 