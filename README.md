# ToDoList API
## May 16, 2018

# Intro
REST is an acronym for Representational State Transfer. It is web standards architecture and HTTP Protocol. The REST architectural style describes six constraints that were originally communicated by Roy Fielding in his doctoral dissertation and defines the basis of RESTful-style as:

 - Uniform Interface
 - Stateless
 - Cacheable
 - Client-Server
 - Layered System
 - Code on Demand (optional)
 
RESTful applications use HTTP requests to perform four operations termed as CRUD (C: create, R: read, U: update, and D: delete). Create and/or update is used to post data, get for reading/listing data, and delete to remove data.

Upon an **HTTP request** (clicking a link, submitting a form, runing a search for example) from the client to the server, The request includes a URL identifying the affected resource, an action method (for example to get, delete, or post the resource), and may include additional information encoded in URL parameters (the field-value pairs sent via a query string), as POST data (data sent by the HTTP POST method), or in associated cookies.

Web servers wait for client request messages, process them when they arrive, and reply to the web browser with an **HTTP response** message. The response contains a status line indicating whether or not the request succeeded (ex: 200 OK), as well as body with the requested content.

RESTful is composed of methods such as; base URL, URL, media types, etc.

## Project Scope and Objectives
This repo will create a RESTful API using Node.js, using MongoDB

### Resources
[tutorial](https://www.codementor.io/olatundegaruba/nodejs-restful-apis-in-10-minutes-q0sgsfhbd)