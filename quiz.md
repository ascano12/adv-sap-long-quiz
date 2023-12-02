## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
each component in a service-oriented architecture (SOA): service providers develop web services and supply pertinent data to the service registry (or broker) so that they can be found and used again later on. Through the broker, the service requester finds the service it needs and binds with the service provider to trigger the necessary functionality.
SOA allow a single client to leverage several third-party services without having to create all the services from scratch. Let's say someone wants to make a website. A website needs payment gateways, web hosting, and products shipping services. As a result, that person will integrate any payment gateway, such PayPal, utilize any outside delivery providers, and hire a hosting company.
2. List and discuss the characteristics of SOA.
Standardized service contract: 
	•	One of the main principles of Service Oriented Architecture is standardized service contracts. They guarantee that services maintained in accordance with contract design requirements are those that are included in the same inventory of services. In a service-oriented architecture, the services can specify their functions and general goal in the form of a service contract. 
    Loose Coupling: 
	•	An strategy known as "loose coupling" involves linking the pieces, or components, of a system, network, or software program in a way that minimizes their practical dependence on one another. The degree to which one element directly knows another is referred to as coupling.
    Abstraction:
	•	The service abstraction layer is a key component of SOA that hides the implementation details and complexity of the underlying services from  consumers Provides a consistent and simplified interface for accessing service functionality and data.
    Service Reusability: 
	•	The help reusability standard is a plan guideline, applied inside the help direction plan worldview, to make benefits that can be reused across a business. These reusable administrations are planned with the goal that their answer rationale is autonomous of a specific business interaction or innovation.
    Autonomy: 
	•	Autonomy, as a design principle within the service-orientation design paradigm, enhances the independence of services from their execution environments. This increased autonomy fosters greater reliability, allowing services to function with reduced reliance on resources that are beyond one's control or influence.
    Statelessness: 
	•	Statelessness is a design principle employed in the service-orientation design paradigm, aiming to create scalable services by disconnecting them from their state data whenever feasible. This leads to a decrease in the resources utilized by a service, as the management of actual state data is outsourced to an external component or architectural extension. This reduction in resource consumption enables the service to efficiently handle a higher volume of requests in a reliable manner.
    Discoverability: 
	•	Discoverability refers to how easily something, particularly content or information, can be located in a search within a file, database, or other information system. This concept holds significance in library and information science, various facets of digital media, software and web development, as well as in marketing. This is because the utility of products and services is compromised if people struggle to locate them or lack an understanding of their purpose.
    Composability: 
	•	It refers to the development of new services by combining existing ones. Adhering to the design principles outlined in the preceding chapter enhances the capacity of services to be integrated into larger components, facilitating swift reuse of functionality.
    Interoperability: 
	•	Interoperability involves the exchange of data, and the higher the interoperability of software programs, the smoother their information exchange becomes. Software programs lacking interoperability require integration. Hence, SOA integration can be viewed as a procedure facilitating interoperability
3. Define Microservices.
Microservices  is a large application is constructed from modular components or services using the microservices architectural approach to corporate application design and deployment. Each module communicates with other modules and services via a clearly defined communications interface, such as an application programming interface (API), and supports a particular task or business objective. A microservices architecture is characterized by its efficient module creation, deployment, and scalability—features that are especially well-suited to application development for contemporary public clouds. It heavily leverages virtual containers and networking technologies.
4. List and discuss the benefits of using Microservices.
Micro services, which organize an application as a series of services, are sometimes referred to as micro service architecture. 
Large, sophisticated applications may be delivered quickly, often, and reliably thanks to the micro service design. It also makes it possible for a company to upgrade its technology stack. An application is organized as a group of loosely linked services using a micro service architecture, which is a variation of the service-oriented architecture structural style. Micro services architectures have lightweight protocols and fine-grained services. 
Highly maintainable and testable, Loosely coupled, Independently deployable Organized around business capabilities, Owned by a small team 

example-creating an online ordering system that accepts orders from clients, checks credit availability and inventories, and then ships the orders. The program is made up of multiple parts, such as the StoreFrontUI, which implements the user interface, and some
5. List and discuss the similarities and differences of SOA and Microservices.
Generally, core components of SOA are shared by various services. Conversely, microservices typically contain all the necessary components within the service, replicated in each microservice. As a result, microservices operate a little more slowly yet require fewer underlying services to function. The scope of the two techniques is the primary difference between them. In other words, microservices architecture has an application scope, whereas service-oriented architecture (SOA) has an enterprise scope. 

-SOA communication, providing the a channel by which services "talk" to one another. But in SOA, employing an ESB can slow down service communication. Microservices rely on more straightforward messaging mechanisms, such as language-neutral APIs, which facilitate faster communication.
6. Define Web Services.
A web service is a software platform that facilitates networked, interoperable machine-to-machine communication. It features an interface (web Service Definition Language, or WSDL) that is described in a manner that can be processed by a machine. One or more specified tasks are completed by web services. A web service's service description is a standard, formal XML idea that includes all the information required to communicate with it, such as the location, transport protocols, and message formats that characterize its operations. Because of the nature of the interface, the implementation details of the service are hidden, allowing it to be used regardless of the hardware or software platform it is implemented on or the programming language used to write it.
7. List and discuss the benefits of using Web Services.
A web service is a code unit accessible through HTTP, allowing remote activation via HTTP requests. It exposes existing code functionalities over the network, enabling other applications to utilize your program's capabilities once exposed.
Web services promote interoperability by enabling different applications to communicate, share data, and access services. They facilitate cross-platform interaction, allowing applications, such as VB or .NET, to communicate with Java web services and vice versa. This promotes platform and technology independence in application development.
A standardized protocol is a set of rules governing data exchange between computer systems, providing a common language for seamless communication and ensuring consistency across diverse systems and devices. Examples include HTTP and SMTP.
Low-cost communication involves using affordable methods, such as messaging apps and VoIP services, to exchange information, minimizing financial expenses associated with staying connected.
8. List and discuss the characteristics of Web Services.
XML-based technologies use Extensible Markup Language (XML) as their foundation to structure and represent data. This versatile markup language is widely employed in applications like web services, data interchange, and configuration files, thanks to its flexibility and readability.
Loosely coupled systems have independent components with minimal dependencies, allowing for flexibility, scalability, and ease of maintenance. Changes to one component have little impact on others, enhancing adaptability in software architecture and system design.

Coarse-grained systems have larger components that encapsulate substantial functionality, focusing on higher-level tasks. This approach reduces operational overhead but may sacrifice fine-tuned control over individual elements in software architecture.

The ability to be synchronous or asynchronous refers to a system's capacity for real-time or delayed coordination of operations. Synchronous involves immediate response, while asynchronous allows for a time lag, offering flexibility and potential efficiency improvements, especially in distributed systems. The choice depends on specific system or application requirements.

Supporting remote procedure calls (RPC) enables the execution of functions on a remote system as if they were local. It facilitates communication between distributed systems, allowing programs to initiate processes on other machines over a network. RPC is crucial in enabling seamless interaction in distributed computing.

Supporting document exchange involves enabling seamless sharing and transfer of documents between systems or users, often facilitated by technologies like web services and APIs. It enhances collaboration and data sharing across different domains.
9. List and discuss the distinct roles in Web Services Architecture.
( 3 distinct role in web services architecture ) 

Provider 
- In web services architecture, a provider creates, hosts, and secures a web service, defining its functionality and making it accessible over the internet. They provide a standardized description, endpoint configuration, security measures, and documentation for users. The provider ensures the service's availability, reliability, and version management.

Requestor
- In web service architecture, a requestor initiates service consumption by discovering available services, composing and sending requests, handling responses, and ensuring security and version compatibility. The requestor integrates the web service into its application, playing a key role in utilizing the provided functionality.

Broker
- In web service architecture, a broker acts as an intermediary facilitating communication between providers and requestors. It handles mediation, discovery, translation, security, load balancing, logging, error handling, and scalability support to ensure effective and efficient interactions in a distributed environment.
10. List and discuss the Web Services Components.
Soap 
- SOAP in web service components provides a standardized XML-based message format, supporting various protocols for communication. It ensures security, error handling, and extensibility while enabling interoperability across different platforms and languages.

Wsdl
- WSDL (Web Services Description Language) describes the structure and operations of a web service, specifying the input/output messages, data types, and communication protocols. It establishes a clear contract for users, promotes interoperability, and allows for tool compatibility in integrating web services efficiently.

UDDI 
- UDDI (Universal Description, Discovery, and Integration) serves as a directory for web services. It enables service discovery, registration, and categorization, supporting dynamic binding and versioning. UDDI enhances interoperability by providing a standardized platform-independent interface for users to discover and connect with web services.
