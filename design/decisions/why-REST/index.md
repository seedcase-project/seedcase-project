## REST API for client-server communication

### Decision

We will use the REST (Representational State Transfer) architectural style for
implementing the communication protocol between our client and server
components, instead of SOAP (Simple Object Access Protocol).

### SOAP

SOAP is another widely used technology for implementing web services. SOAP is
based on the XML protocol and supports a wider range of messaging formats, such
as binary and MIME types, making it more flexible than REST in some cases.

However, SOAP is more complex and heavyweight than REST, which can make it more
difficult to implement and maintain. SOAP requires a lot of additional metadata
and processing overhead, which can result in slower performance and higher
resource consumption. Additionally, SOAP can be more difficult to debug and test
than REST, due to its complexity and lack of visibility into the underlying
messages.

REST, on the other hand, is lightweight and easy to implement, making it a
popular choice for web-based applications. REST uses a simple and intuitive set
of HTTP methods, which makes it easy for developers to understand and use. REST
also provides a clear separation of responsibilities between the client and
server components, making it easier to develop, test, and deploy each component
independently.

### GraphQL

GraphQL and REST API are both popular technologies used for building web APIs.
REST API follows a more traditional approach where the client sends a request to
the server, and the server responds with the requested data. GraphQL offers more
flexibility and allows the client to specify exactly what data they need.
However, GraphQL can be more complex to set up and maintain than REST API,
especially for simple use cases. REST API is often simpler to implement and
offers better caching mechanisms. Additionally, REST API has better tooling
support and is more widely adopted. That being said, Graph can be a useful
addition to a REST API, especially when handling large or complex and large
requests, as it allows for more fine-grained control over the data returned. 
In the future develop, GraphQL can be incorporated into an existing REST API. 

### Conclusion

we believe that the simplicity, flexibility, and scalability of REST
make it a better choice for our client-server communication needs, compared to
the more complex and heavyweight SOAP protocol.