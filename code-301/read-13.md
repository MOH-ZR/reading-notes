# Sending Form Data
## What happens to the data when a form is submitted?
## On the client side   
The `<form>` element defines how the data will be sent. All of its attributes are designed to let you configure the request to be sent when a user hits a submit button. The two most important attributes are:
* action
    * The action attribute defines where the data gets sent.
    * Its value must be a valid relative or absolute URL. 
    * If this attribute isn't provided, the data will be sent to the URL of the page containing the form — the current page.
    * When specified with no attributes, the <form> data is sent to the same page that the form is present on.

* method
    * The method attribute defines how data is sent.
    * the most common are the GET method and the POST method.
    * In GET method The data is appended to the URL as a series of name/value pairs.
    * In POST method the data is appended to the body of the HTTP request.
## On the server side
Whichever HTTP method you choose, the server receives a string that will be parsed in order to get the data as a list of key/value pairs. The way you access this list depends on the development platform you use and on any specific frameworks you may be using with it.
It's more common to use one of the many high quality frameworks that make handling forms easier, such as:

* Express for Node.js
* Django for Python
* Laravel for PHP
* Ruby On Rails for Ruby


