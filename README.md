## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
    A design pattern used in business software development, where it focuses in using software components called services. Services are a unit of software designed to perform a specific task, SOA makes these services independent and reusable, which means these services can be used to other business processes, platforms, and systems. Furthermore, the independent services can be combined to create a larger and more complex applications. Service example: Authentication Functionality
        
    Aside from creation and organizing of independent services, SOA is also a middleware for different systems or applications which means it is efficient as it handles necessary functionalities to let these services connect and communicate with each other across multiple platfroms and different languages. 
2. List and discuss the characteristics of SOA.
    a. Standardization
      SOA uses the RPC model commonly from structured programming. It standardizes how business processes are automated and used in a way that maintains security and governance.
    b. Reusability
      SOA services are held in a repository and linked on demand, making each service a resource available to all, subject to governance constraints. Reusing services saves organizations time and lowers development costs associated.
    c. Ease of maintenance
      Since all services are independent, they can be easily modified and updated without affecting other services. This lowers an organization's operating costs and speeds time to market for applications being developed.
    d. Interoperability
      allows different distributed web services to run on a variety of software platforms and hardware architectures.
    e. Increased reliability
      SOA generates more reliable applications because it's easier to debug small services than large code.
    f. Scalability
      SOA lets service run on different servers, increasing scalability. In addition, using a standard communication protocol allows organizations to reduce the level of interaction between clients and services. With a lower level of interaction, applications can be scaled without adding extra pressure.
3. Define Microservices.
    Microservices is an architecture used in developing an application that consists of collection of independent services. From monolothic approach of creating systems where everything is centralized to multi-tier application where the creation of business software are separated into layers to implementing Microservices where services are independent and have only one business function for the purpose of improving maintenance, reusability, complexity, and scalability of a business software.
    
    Mircroservices provides an architecture where teams with different functionalities to develop can work separately and independently of each other, this lowers the risk of damaging or impacting other teams through the devleopment process. This can also mean that different services can be developed using different programming languages and can be deployed to different platforms. These microservices grow along with the growth of an enterprise, since these microservices are highly distributed, if a microservice instance fails it could cascade outages to other microservices and finding the root cause would become difficult and fixing it immediately will be also hard.  
4. List and discuss the benefits of using Microservices.
    a. Organized around Business Capabilities 
      The microservice approach to division is splitting up into services organized by business capability.
    b. Smart endpoints and dumb pipes
      Microservices aim to be as decoupled and as cohesive as possible, so they own their own domain logic and receiving a request, applying logic and producing a response with using Restful APIs.
    c. Decentralized Governance
      Sharing useful and all tested code as libraries, encourages other developers to solve similar problems in similar ways.
    d. Decentralized Data Management
      Microservices prefer letting each service manage its own database, either different instances of the same database technology, or entirely different database systems. 
    e. Scalable
       Each service operates independently, it is possible to scale individual services up or down as needed, without affecting the rest of the application. This allows teams to allocate resources more efficiently and ensure that the application can handle increased traffic or usage.
    f. Resilience
       a fault in one service doesn't disable the entire application.
    g. Agility
       A microservice architecture offers faster development and greater agility compared to a      monolith.
5. List and discuss the similarities and differences of SOA and Microservices.
     In terms of principles and characteristics SOA and microservices are similar in being Scalable, Reliable and Resilient. Both have independent services within a system which are focused only on one function or business process,service or capabilities which makes the three characteristics possible with these architectures. Furthermore the services in both SOA and microservices can be deployed to different application and can run on different programming languages. The difference between the two is that Microservices are structures independent of each other in a way that these services can have and handle their own databases and APIs, the services in this architecture focuses on a single task only and a lot more smaller than SOA, while SOA is an architecture that has indpendent services but these services are shared and reused to perform multiple business tasks.Furthermore, these services in SOA communicates with each other and can be combined to create a more complex application. 

    Microservices addresses the shortcomings of the SOA, it is because while SOA  work well for building large enterprise applications, it needs more flexibility to scale smaller business-specific applications. This is where Microserrvices come in where it divides SOA service into smaller services or a more fine-grained approach to building applications.  
