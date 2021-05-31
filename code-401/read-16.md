# AWS - Cloud Servers

## Questions

**Describe the Web-Request-Response-Cycle?**
1. A user opens his browser, types in a URL, and presses Enter.
2. When a user presses Enter, the browser makes a request for that URL.
3. The request hits the Rails router (config/routes.rb). The router maps the URL to the correct controller and action to handle the request.
4. The action receives the request and passes it on to the view.
5. The view renders the page as HTML.
6. The controller sends the HTML back to the browser. The page loads and the user sees it.  

**Explain what a “server” is, as it relates to the WRRC?**
A server is a computer that provides data to other computers. It may serve data to systems on a local area network (LAN) or a wide area network (WAN) over the Internet.
Many types of servers exist, including web servers, mail servers, and file servers. Each type runs software specific to the purpose of the server.  

**What does it mean to “deploy” an application?**
Deploying your application means putting it on a Web server so that it can be used either through the Internet or an intranet.  

## Terms
**Serevr**:is a computer that provides data to other computers. It may serve data to systems on a local area network (LAN) or a wide area network (WAN) over the Internet.  
**Pub/Sub**:
**WRRC**: Web-Request-Response-Cycle)

## AWS

**Virtual Machine**
a virtual machine (VM) is the virtualization/emulation of a computer system. Virtual machines are based on computer architectures and provide functionality of a physical computer. Their implementations may involve specialized hardware, software, or a combination.  

**AWS EC2**
Amazon Elastic Compute Cloud (EC2) is a part of Amazon.com's cloud-computing platform, Amazon Web Services (AWS), that allows users to rent virtual computers on which to run their own computer applications. EC2 encourages scalable deployment of applications by providing a web service through which a user can boot an Amazon Machine Image (AMI) to configure a virtual machine, which Amazon calls an "instance", containing any software desired.  

**AWS Elastic Beanstalk**
AWS Elastic Beanstalk is an orchestration service offered by Amazon Web Services for deploying applications which orchestrates various AWS services, including EC2, S3, Simple Notification Service (SNS), CloudWatch, autoscaling, and Elastic Load Balancers