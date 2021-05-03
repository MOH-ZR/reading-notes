# Express

**What’s the difference between PUT and PATCH in REST API?**  
In RESTful APIs, both PUT and PATCH calls are intended to updated information on an object. The differences are:
* PUT requires that all properties of the object be provided in the call. If you’re updating a user’s profile via API, each property of the profile needs to be provided in the PUT call.
* Patch allows you to specify only the properties that are being updated. If you’re just changing a profile’s address, you can issue a PATCH request that only contains the new address, and don’t need to provide all other information such as birth date or phone number.

**mocking servers**
1. Postman
2. Stoplight
3. Mocky.io
4. Killgrave 

**Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?**  
apiDocjs: Inline Documentation for RESTful web APIs. It creates a documentation from API annotations in your source code. It includes a default template which uses handlebars, Bootstrap, RequireJS and jQuery for the output of the generated apidata.js and apiproject.js as a html-page; Swagger Inspector: Test and Document Your APIs With Ease. It is a free cloud-based API testing and documentation tool to simplify the validation of any API and generate its corresponding OpenAPI documentation.
apiDocjs and Swagger Inspector can be primarily classified as "API" tools.  

**Compare and contrast SOAP and ReST**
* SOAP stands for Simple Object Access Protocol whereas REST stands for Representational State * Transfer.
* SOAP is a protocol whereas REST is an architectural pattern.
* SOAP uses service interfaces to expose its functionality to client applications while REST uses Uniform Service locators to access to the components on the hardware device.
* SOAP needs more bandwidth for its usage whereas REST doesn’t need much bandwidth.
* SOAP only works with XML formats whereas REST work with plain text, XML, HTML and JSON.
* SOAP cannot make use of REST whereas REST can make use of SOAP.

**Document the following Vocabulary Terms**  

**Web Server:** is computer software and underlying hardware that accepts requests via HTTP, the network protocol created to distribute web pages, or its secure variant HTTPS.  
**Express:** is a back end web application framework for Node.js, released as free and open-source software under the MIT License. It is designed for building web applications and APIs. It has been called the de facto standard server framework for Node.js  
**Routing:** refers to how an application’s endpoints (URIs) respond to client requests.  
**WRRC:** web request/response cycle traces how a user's request flows through the app.  

## Q&A
**Which 3 things had you heard about previously and now have better clarity on?**
REST API, CRUD, and HTTP request.  
**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
mock API server, Swagger, and SOAP 
**What are you most excited about trying to implement or see how it works?**
testing units
