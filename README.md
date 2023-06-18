# APIs
## Restful Services
* Most of the applications follow these days client server architecture
* App itself is the client or front-end part.It needs to talk to the server or the backend to get or save the data. This communication happens using the HTTP Protocol.
* On the server you expose bunch of services that are accessible via the HTTP Protocol.The client can directly call these services by sending HTTP request.This is where REST comes into the picture.
* REST :- Reprsentational State Transfer---convention for building HTTP services
* We use simple HTTP principles to provide support to CRUD (Create, Read, Update, Delete) data
* for example: http://vidly.com/api/customers client can send http request to this end point to talk to the server.
*  NOTES:
*  http/https : The address can start with http or https depending on the security of the channel.
*  vidly.com  : Domain of the application.
*  api : not compulsory. Most companies follow this convention to expose their restful services.
*  customers : refers to the collecion of customers in the application. In the REST world we refer to this part as a resource.We can expose our resources such as customers, movies etc and various end points.So this is our endpoint.
*  All the operations around customers such as creating a customer or updating a customer will be done by sending a HTTP request to this end point.
*  A type of the HTTP request detrermines the kind of the operation.S o every HTTP request has a method that determines its type or intention.
*  HTTP METHODS:
*  GET : For grtting the data
*  POST: Creating the data
*  PUT : Updating the data
*  DELETE : Deleting the data
*  For example:
*  GET : get customers
*  ![image](https://github.com/Sinha321/APIs/assets/116704941/012f341a-1815-416a-9fbe-525badcb96ae)
*  GET : get a single customer
*  ![image](https://github.com/Sinha321/APIs/assets/116704941/de4c9652-ef61-4a38-9be8-3914ec75def2)
*  UPDATE : update a customer
*  ![image](https://github.com/Sinha321/APIs/assets/116704941/6f5b9d35-e02b-4ca7-b1f5-371b6a34a369)
*  DELETE : deleting a customer
*  ![image](https://github.com/Sinha321/APIs/assets/116704941/1ecdd2e3-2c85-4a74-b244-c8440dde19e2)
*  CREATE : creating a customer
*  ![image](https://github.com/Sinha321/APIs/assets/116704941/182efdf7-7e7d-40c2-9408-077b2e6f69b8)





   

