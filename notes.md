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
