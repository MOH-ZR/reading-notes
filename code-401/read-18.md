# AWS: API, Dynamo and Lambda

## Questions
**If you were to create a system that emulated Lambda functions, how would you do it?**
First I should write the serverless function then I need a platform that allow this service for example I can use AWS Lambda, then I need to add a trigger into another service that will invoke this function upon certain event.  
**Describe how a CDN works?**
A CDN is an interconnected network of servers that share a common goal to deliver content—such as software downloads, OS updates, data records, cloud-based services, and 4K video streaming—quickly, cheaply, efficiently, and securely. When they work together, the servers in a CDN reduce the time it takes to load a web page on your device.

A CDN will store cached versions of your website content in several different locations around the world. Also known as points of presence (PoP), these servers each handle user requests based on proximity, thereby reducing costs and transit times to provide faster data delivery. The caveat is that it’s the second person and onwards who will benefit from improved speed, as the CDN will cache what the first person loads.  

## Terms
**Serverless Functions**: serverless functions are single-purpose, programmatic functions that are hosted on managed infrastructure. These functions, which are invoked through the Internet, are hosted and maintained by cloud computing companies. The engineering teams within those companies ensure that the serverless functions have near-perfect uptime, redundant instances around the world, and scale to any incoming network request volume.  

**Cloud Storage**: it is a cloud computing model that stores data on the Internet through a cloud computing provider who manages and operates data storage as a service. It’s delivered on demand with just-in-time capacity and costs, and eliminates buying and managing your own data storage infrastructure. This gives you agility, global scale and durability, with “anytime, anywhere” data access.  
**CDN**: refers to a geographically distributed group of servers which work together to provide fast delivery of Internet content.  

## AWS API Gateway
Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests.

Many Serverless applications use Amazon API Gateway, which conveniently replaces the API servers with a managed serverless solution.  
## AWS DynamoDB
DynamoDB is a hosted NoSQL database offered by Amazon Web Services (AWS). It offers:

reliable performance even as it scales;
a managed experience, so you won't be SSH-ing into servers to upgrade the crypto libraries;
a small, simple API allowing for simple key-value access as well as more advanced query patterns.  
## Dynamoose
Dynamoose is a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose, which means if you are coming from Mongoose the syntax will be very familar.  