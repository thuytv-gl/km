```bash
check each .md file
```

### Language

**Programming Languages (Java, Golang, PHP)**
- **Java**: Versatile, object-oriented, enterprise-scale applications.
- **Golang (Go)**: Statically typed, compiled, cloud services, microservices.
- **PHP**: Server-side scripting, web development, dynamic web pages.

### Framework

**Service-Oriented Architecture and Microservices**
- **Docker**: Platform for developing, shipping, and running applications in containers.
- **ECS (Elastic Container Service)**: Managed container orchestration service by AWS.
- **Lambda**: AWS service for running code without provisioning servers.
- **SQS (Simple Queue Service)**: Managed message queuing service by AWS.
- **Kinesis**: Platform for collecting, processing, and analyzing real-time streaming data.

### Technique

**Building Reliable, Scalable, and Resilient Systems**
- **Caching**: Storing copies of data to reduce access time.
- **Monitoring**: Observing system performance and health.
- **Tracing**: Tracking the flow of requests through a system.
- **Eventual Consistency**: Consistency model for high availability.
- **Queues**: Managing and processing tasks asynchronously.
- **Load Balancing**: Distributing network traffic across servers.
- **Circuit Breaking**: Preventing cascading failures by detecting and handling failures.


## JWT
### JSON Web Token (JWT)

A JSON Web Token (JWT) is an open standard (RFC 7519) for securely transmitting information between parties as a JSON object. It is compact, URL-safe, and can be verified and trusted because it is digitally signed. JWTs are commonly used for authentication and information exchange.

### Advantages
- **Compact:** JWTs are small in size and can be easily transmitted via URL, POST parameters, or inside HTTP headers.
- **Self-contained:** JWTs carry all the necessary information about the user, reducing the need for additional database lookups.
- **Scalability:** As the information is contained within the token itself, it simplifies horizontal scaling.
- **Stateless:** Server-side scalability is improved as JWTs are stateless; the server does not need to store session data.
- **Security:** JWTs are signed using a secret or public/private key pair, ensuring data integrity and authenticity.

### Drawbacks
- **Size:** Although compact, JWTs can become quite large if they carry extensive information, potentially impacting performance.
- **Stateless:** Being stateless can be a double-edged sword; revoking tokens can be complex without server-side session management.
- **Security:** If not implemented correctly, JWTs can be vulnerable to attacks such as token theft, replay attacks, and brute force.
- **Complexity:** Proper implementation and management of JWTs require a thorough understanding of security best practices.

Feel free to ask if you have any other questions!