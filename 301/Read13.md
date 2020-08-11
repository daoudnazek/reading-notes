# 301 - Read13 

## Sending Form Data

Web uses a client/server architecture, where client is the web browser sends a request to a server(like Apache, Nginx, IIS, Tomcat, etc.) , and the server answer the request , both request and answer are using http protocol.


![server client](https://media.geeksforgeeks.org/wp-content/uploads/20191016114416/801.png)

### How to send Data 

The **form** element defines how the data will be sent. The two most important attributes are **action** and **method**.


#### The action attribute

Defines where the data will be sent. Value must be a valid relative or absolute URL. If this attribute isn't provided, the data will be sent to the URL of the page containing the form.


*Example* : 

- form action="https://example.com" 

- form action="/somewhere_else"


#### The Method attribute 

- **The get method:** is the method used by the browser to ask the server to send back a given resource.

- **The post method:** : t's the method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request.