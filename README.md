<h1 align="center">Markian Mumba</h1>
<h3 align="center">Backend Engineer · Java / Spring Boot · Distributed Systems</h3>

<p align="center">
  <a href="https://medium.com/@mumbamarkian"><img src="https://img.shields.io/badge/Blog-Over--Engineered_on_Purpose-00B86B?style=flat-square&logo=medium&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/markian-mumba-67231517a/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:mumbamarkian@gmail.com"><img src="https://img.shields.io/badge/Email-Reach_out-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
</p>

<p align="center">
  📍 Nairobi, Kenya 
</p>

---

### About

I'm a backend engineer working primarily in **Java / Spring Boot**, with a focus on microservices, distributed systems, and the messy operational realities behind them — service discovery, auth flows, inter-service communication, and the cross-cutting concerns nobody warns you about.

By day I build production systems at **Cloudit Africa** — Spring Boot microservices, Angular frontends, and Azure infrastructure. By night I build deliberately over-engineered side projects to learn the things production work doesn't expose me to: gRPC, OAuth2 authorization servers, service meshes, Spring auto-configuration internals.

I write about it as I go.

---

### 📝 Writing — *Over-Engineered on Purpose*

A series documenting the build of **RentItUp**, a microservice platform, from scratch. Not a tutorial — more like an engineering journal of the decisions, dead-ends, and small victories along the way.

- **Part 8 —** [A User Clicks 'Book Now' and Their JWT Travels Through Four Services. Here's How.](https://medium.com/@mumbamarkian/a-user-clicks-book-now-and-their-jwt-travels-through-four-services-here-s-how-f11af0832c6f) — gRPC interceptors, auto-configuration, and zero-trust between services
- **Part 7 —** [Half of My OAuth2 Login Flow is Code I Never Wrote](https://medium.com/@mumbamarkian/half-of-my-oauth2-login-flow-is-code-i-never-wrote-c5eb810874cf) — Spring Authorization Server and JWKS

Full series on [Medium →](https://medium.com/@mumbamarkian)

---

### 🛠 Stack

**Primary** &nbsp;&nbsp; Java 17+ · Spring Boot · Spring Security · Spring Cloud · gRPC · PostgreSQL · RabbitMQ · Docker · Gradle  
**Cloud / DevOps** &nbsp;&nbsp; Azure (App Service, Blob Storage, Front Door) · GitLab CI/CD · Eureka · Zipkin · Flyway  
**Also work with** &nbsp;&nbsp; Angular · Next.js · TypeScript · Go · Python (Django) · MongoDB

---

### 🚀 Selected Projects

**[RentItUp](https://github.com/markmumba/rentitup-microservice)** &nbsp; *Spring Boot · gRPC · OAuth2 · Eureka · PostgreSQL · RabbitMQ*  
A machinery rental marketplace built as a deliberately over-engineered microservices platform — four independently deployable services with real-time availability, booking, and payment flows. Spring Authorisation Server with JWKS for auth, gRPC for inter-service communication with a custom Eureka name resolver and round-robin load balancing, a PostgreSQL unlogged-tables caching layer for catalogue browsing, and a shared common module with custom Spring auto-configuration that standardises auth, error handling, and service comms across the platform. Documented in the blog series above.

**Foliocuts** &nbsp; *Spring Boot · PostgreSQL · M-Pesa Daraja*  
A backend-driven barbershop management system digitising payments, commissions, and operational reporting. RESTful APIs for transactions, staff commissions, customer loyalty, and role-based dashboards. Integrated **M-Pesa STK Push** with automated transaction recording, receipt generation, and reconciliation logic — handling the messy realities of payment confirmations and edge cases that come with mobile money in Kenya.

**BolloApp** &nbsp; *Spring Boot · Docker · MTN MoMo · VPS Deployment*  
Backend services for a smart waste management platform exposing real-time APIs for scheduling, billing, and collections. Integrated **MTN MoMo payments** for automated customer billing and transaction verification, containerised the services, and shipped them to a VPS via CI/CD pipelines. The project where I learned how much of "production" is actually deployment, secrets management, and not breaking things between releases.

**[Smart Garbage Collection Platform](https://app.blazor-movies.online/)** &nbsp; *Spring Boot · Next.js · REST*  
End-to-end platform connecting collection requests to provider routing.

---

### 🎯 What I'm Into Right Now

- Kubernetes — so the next iteration of RentItUp can move to a real service mesh
- Spring Boot internals — auto-configuration, bean post-processors, the bits people treat as magic

---

### 📫 Reach Out

Open to  backend roles — Spring Boot, microservices, distributed systems.

- ✉️ mumbamarkian@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/markian-mumba-67231517a/)
- ✍️ [Medium](https://medium.com/@mumbamarkian)
