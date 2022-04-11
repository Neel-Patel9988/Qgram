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


A cloude application is internet-based software that processes or stores data online

There are three main kinds of application:

1. Software as a service
2. Platform as a service
3. Infrastructure as a service


**About Qgram**


Qgram is an api platform where every person can visit and search for a quote according to their moods or feelings. One can also search for their faviorite author. Registered users can also creat their own quotes and can also delete as well if they feel like it.


# System Architecture

![image](https://user-images.githubusercontent.com/102377195/162663991-f9a6677a-78ab-436b-a71d-5b9fc730a0e2.png)




# Backend

We will be using the Basic CRUD operations which are possible by accessing the API.

GET : method is for retrieving information. Our app simply returns the results of some simple data.

POST : allow our clients to remotely add/create new resources.

PUT : allows the user to update their quote data.

DELETE : enables the user to delete their quotes.


# Security

Authentication is ascertaining the identity of an entity. For Qgram we have implemented a simple but secure authentication System. A user simply provides a username and password directly in the HTTP header request: no need to handshakes or challenge/response.


Code example :
if request.authorization and request.authorization.username == 'username' and request.authorization.password == 'password'


where login id is - username

and password is - password
