# SENDING FORM DATA

![Image](https://res.cloudinary.com/practicaldev/image/fetch/s--T2rAtHXL--/c_imagga_scale,f_auto,fl_progressive,h_500,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/b7eo508eo6bq4mdf4xuw.png)


> - Once the form data has been validated on the client-side, it is okay to submit the form. And, since we covered validation in the previous article, we're ready to submit! This article looks at what happens when a user submits a form — where does the data go, and how do we handle it when it gets there? We also look at some of the security concerns associated with sending form data. Client/server architecture
> - An HTML form on a web page is nothing more than a convenient user-friendly way to configure an HTTP request to send data to a server.

> - The <form> element defines how the data will be sent. All of its attributes are designed to let you configure the request to be sent when a user hits a submit button.

> - The HTTP protocol provides several ways to perform a request; HTML form data can be transmitted via a number of different methods, the most common being the GET method and the POST method.

> - The GET method is the method used by the browser to ask the server to send back a given resource.

> - The POST method It’s the method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request.

> - Whichever HTTP method you choose, the server receives a string that will be parsed in order to get the data as a list of key/value pairs.
> - Sending files with HTML forms is a special case.

> - Files are binary data — or considered as such — whereas all other data is text data.

> - Because HTTP is a text protocol, there are special requirements for handling binary data.

> - This attribute lets you specify the value of the Content-Type HTTP header included in the request generated when the form is submitted.

> - This header is very important because it tells the server what kind of data is being sent. By default, its value is application/x-www-form-urlencoded.


