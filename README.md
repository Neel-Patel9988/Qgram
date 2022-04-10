# Qgram 
![image](https://user-images.githubusercontent.com/102377195/162349034-84225b27-9abd-45f1-b641-a22620b8a84b.png)

An App where each person can get a quote for every mood or even any random quote. As the craze of social media increasing, every every person seeks for a perfect quote for themselfs, rather it be for an instagram post or a tweet.
Qgram is here for the rescue !!!

The API has been Secured by Authentication. Qgram API users will also have the abiity to create, read, update and delete quotes in database.


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


