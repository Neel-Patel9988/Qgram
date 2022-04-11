# Qgram 
![image](https://user-images.githubusercontent.com/102377195/162349034-84225b27-9abd-45f1-b641-a22620b8a84b.png)

An App where each person can get a quote for every mood or even any random quote. As the craze of social media increasing, every every person seeks for a perfect quote for themselfs, rather it be for an instagram post or a tweet.
Qgram is here for the rescue !!!

The API has been Secured by Authentication. Qgram API users will also have the ability to create, read and delete quotes in database.


# Table of Content


- About
- System Architecture
- Backend
  - CRUD Operations
    - Operation in Details
  - Cloud App
 - Front-end
 - Desclaimer
 
 
# About
**Introduction of cloud application**

Clouds are computing resources for rent. There are many cloud providers to choose from. Some of the main cloud providers are: (Amazon) AWS, (Microsoft) Azure, Google Cloud, IBM Cloud, Alibaba Cloud, Salesforce, Rackspace, Oracle Cloud.

A cloude application is internet-based software that processes or stores data online

There are three main kinds of application:

1. Software as a service
2. Platform as a service
3. Infrastructure as a service


**About Qgram**


Qgram is an api platform where every person can visit and search for a quote according to their moods or feelings. One can also search for their faviorite author. Registered users can also creat their own quotes and can also delete as well if they feel like it.


# System Architecture

![image](https://user-images.githubusercontent.com/102377195/162663991-f9a6677a-78ab-436b-a71d-5b9fc730a0e2.png)


The front-end serves as a seamless user interface for many devices such as smartphones, PCs or laptops. The backend uses REST-based services interface for CRUD operations, such as finding a quote by catagory, getting all quotes, names of author, user sign in and even deleting one with authority. This is deployed via Google cloud with quick response to any request. An attempt to connecting it to a external translating API is also made.

# Backend

Most of the CRUD operations are performed in terminals and browser. One can also make use of Postman for these API's operation.


**CRUD OPERATION

We will be using the Basic CRUD operations which are possible by accessing the API. One can access these operations via adding ```api/all_author``` and ```api/all_records``` at the end of the web address following the REST standards.

where one can get whole records of data or even a specific result such as,

```{"quote" = "One life, live it!"} ```

A basic overview of CRUD operations 

GET : method is for retrieving information. Our app simply returns the results of some simple data.

POST : allow our clients to remotely add/create new resources.

PUT : allows the user to update their quote data.

DELETE : enables the user to delete their quotes.


# Cloud

Our current backend is deployed on the google cloude. [Click Here](https://github.com/shivanshkaushik/QGram) for details on API and updates.


**Deploying Qgram to Cloud

First one have to create a Virtual instance, for which we will need an Google Cloude with proper configurations. 


For a google cloud service,

Sign in/up [here] (https://cloud.google.com).


After Creating an instance, Connect a terminal to it using Linux operating system. SSH (Secure Shell) Protocol will be used here. To do this one will need  public and private keys. We will put the Public Key in the GCP instance. And we will keep the private key on our own PC to connect to the instance in GCP. 

In the next step we will  
# Security

Authentication is ascertaining the identity of an entity. For Qgram we have implemented a simple but secure authentication System. A user simply provides a username and password directly in the HTTP header request: no need to handshakes or challenge/response.


Code example :
if request.authorization and request.authorization.username == 'username' and request.authorization.password == 'password'


where login id is - username

and password is - password
