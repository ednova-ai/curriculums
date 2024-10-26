---
# **Ednova Backend Engineering Curriculum**

### **Duration:** 3 Months (12 Weeks)  
### **Commitment:** 12 Hours per Week  
### **Total Hours:** 144 Hours

---

## **Welcome to Ednova's Backend Engineering Program**

At Ednova, we are dedicated to providing a comprehensive and immersive learning experience for aspiring backend engineers. Our curriculum is meticulously crafted to equip you with the essential skills and knowledge required to excel in the dynamic field of backend development. Leveraging Python and Java—two of the most powerful programming languages—and incorporating cutting-edge frameworks like Spring Boot and FastAPI, we prepare you to tackle real-world challenges and advance your career.

---

## **Program Structure**

Our program begins with a solid foundation in programming concepts and progressively branches into specialized tracks. Students can personalize their learning journey by choosing **any two tracks** after completing the common foundational modules.

---

## **Weeks 1-4: Foundational Modules**

### **Objective:**  
Build a strong base in programming, data structures, algorithms, and object-oriented principles using both Python and Java.

### **Modules Covered:**

- **Programming Fundamentals**
  - Syntax and Semantics of Python and Java
  - Variables, Data Types, and Operators
  - Control Structures: Conditional Statements and Loops
  - Functions and Methods

- **Data Structures and Algorithms**
  - Arrays, Lists, Stacks, Queues, Linked Lists
  - Trees and Graphs Basics
  - Sorting and Searching Algorithms
  - Big O Notation and Complexity Analysis

- **Object-Oriented Programming (OOP)**
  - Classes and Objects
  - Encapsulation, Inheritance, Polymorphism, Abstraction
  - Interfaces (Java) and Protocols (Python)

- **Problem-Solving Techniques**
  - Recursion and Iteration
  - Debugging and Testing Strategies
  - Problem-Solving Patterns

### **Weekly Time Allocation:**

- **Lectures and Reading:** 6 Hours
- **Hands-On Coding Exercises:** 6 Hours

---

## **Specialized Tracks (Choose Any Two)**

After completing the foundational modules, personalize your learning by selecting **two** of the following specialized tracks:

1. **Java Backend Development with Spring Boot**
2. **Python Backend Development with FastAPI**
3. **Databases, SQL, NoSQL, and DevOps**
4. **System Design and Scalability**

---

### **Track 1: Java Backend Development with Spring Boot**

#### **Objective:** 
Master backend development using Java and Spring Boot, culminating in deploying applications on Azure.

#### **Weeks 5-6: Introduction to Spring Boot**

- **Setting Up the Environment**
  - Install JDK and IntelliJ IDEA/Eclipse
  - Introduction to Maven and Gradle

- **Spring Boot Fundamentals**
  - Creating Spring Boot Projects
  - Dependency Injection and Inversion of Control (IoC)
  - RESTful API Development

- **Data Access with Spring Data JPA**
  - Hibernate ORM
  - CRUD Operations with Relational Databases
  - Database Connectivity

**Hands-On Project:**  
**Develop a Blog Platform Backend**

- **Description:** Build a backend for a blogging platform where users can create accounts, write blog posts, comment on posts, and follow other users.
- **Real-World Relevance:** Mimics platforms like Medium or WordPress, focusing on content management and user interactions.
- **Key Features to Implement:**
  - User authentication and authorization
  - CRUD operations for posts and comments
  - Following system to subscribe to other users' content
  - Pagination and searching of blog posts

#### **Weeks 7-8: Advanced Spring Boot Features**

- **Spring Security**
  - Implementing OAuth2 with Social Logins (Google, Facebook)
  - Role-Based Access Control (Admin, Editor, Reader)

- **Validation and Exception Handling**
  - Input Validation with Hibernate Validator
  - Global Exception Handling with @ControllerAdvice

- **Testing Spring Boot Applications**
  - Unit Testing with JUnit and Mockito
  - Integration Testing with MockMVC

**Hands-On Project Enhancement:**  
**Add Advanced Features to the Blog Platform**

- **Key Enhancements:**
  - Implement social login capabilities
  - Add content moderation features for admins
  - Implement rich text editing and image uploads
  - Optimize for SEO (Search Engine Optimization)

#### **Weeks 9-10: Microservices and Messaging**

- **Microservices with Spring Cloud**
  - Breaking the monolith into microservices (User Service, Post Service, Comment Service)
  - Service Discovery with Eureka
  - API Gateway Implementation with Zuul or Spring Cloud Gateway

- **Messaging with Kafka**
  - Implementing Event-Driven Communication between Services
  - Handling Asynchronous Notifications (e.g., email notifications for new followers)

- **Caching with Redis**
  - Implementing Caching for Frequently Accessed Data
  - Session Management

**Hands-On Project Enhancement:**  
**Microservices and Scalability**

- **Key Enhancements:**
  - Refactor the blog platform into microservices
  - Implement real-time notifications using WebSockets
  - Use Redis for caching popular blog posts

#### **Weeks 11-12: Deployment on Azure**

- **Containerization with Docker**
  - Writing Dockerfiles for Each Microservice
  - Managing Containers with Docker Compose

- **Continuous Integration/Continuous Deployment (CI/CD)**
  - Setting Up Pipelines with Jenkins or GitHub Actions
  - Automated Testing and Deployment

- **Azure Deployment**
  - Deploying Microservices on Azure Kubernetes Service (AKS)
  - Setting Up Azure SQL Database
  - Configuring Azure Load Balancer and Traffic Manager

**Final Project:**  
**Deploy the Blog Platform on Azure with Full CI/CD Pipelines**

- **Key Deliverables:**
  - A fully functional, scalable blog platform accessible online
  - Documentation of the deployment process
  - Monitoring and logging setup using Azure Monitor and Application Insights

---

### **Track 2: Python Backend Development with FastAPI**

#### **Objective:** Learn to build high-performance backend applications using Python and FastAPI, including Azure deployment.

#### **Weeks 5-6: Introduction to FastAPI**

- **Environment Setup**
  - Install Python and VS Code/PyCharm
  - Virtual Environments with pipenv or poetry

- **FastAPI Fundamentals**
  - Creating FastAPI Applications
  - Async Programming with asyncio
  - API Endpoints and Routing

- **Database Integration with SQLAlchemy**
  - ORM Basics
  - CRUD Operations
  - Alembic for Migrations

**Hands-On Project:**  
**Build an E-Commerce Backend**

- **Description:** Develop the backend for an e-commerce platform supporting product listings, shopping cart, and order management.
- **Real-World Relevance:** Simulates platforms like Amazon or eBay, focusing on transaction management and product handling.
- **Key Features to Implement:**
  - Product catalog with categories and search functionality
  - User registration and authentication
  - Shopping cart management
  - Order processing and history

#### **Weeks 7-8: Advanced FastAPI Features**

- **Authentication and Authorization**
  - Implementing OAuth2 and JWT Tokens
  - Role-Based Permissions (Customer, Admin)

- **Background Tasks and Middleware**
  - Processing Orders Asynchronously
  - Custom Middleware for Logging and Performance Monitoring

- **Testing FastAPI Applications**
  - Writing Unit Tests with pytest
  - Test Coverage Analysis

**Hands-On Project Enhancement:**  
**Enhance the E-Commerce Backend**

- **Key Enhancements:**
  - Integrate payment gateways (e.g., Stripe or PayPal)
  - Implement product reviews and ratings
  - Add admin dashboards for inventory management

#### **Weeks 9-10: Microservices and Event-Driven Architecture**

- **Building Microservices**
  - Separating Services (Product Service, Order Service, User Service)
  - API Gateway with FastAPI or Kong

- **Messaging Systems**
  - Using RabbitMQ or Kafka for Order Processing
  - Implementing Event Sourcing

- **Caching and Rate Limiting**
  - Using Redis for Session Management and Caching
  - Implementing Rate Limiting to Prevent Abuse

**Hands-On Project Enhancement:**  
**Microservices and Scalability**

- **Key Enhancements:**
  - Implement real-time inventory updates
  - Use Celery for background task processing
  - Set up rate limiting and throttling for APIs

#### **Weeks 11-12: Deployment on Azure**

- **Docker and Containerization**
  - Containerizing Microservices
  - Managing Multiple Containers with Docker Compose

- **CI/CD Pipelines**
  - Setting Up Pipelines with Azure DevOps or GitHub Actions
  - Automated Testing and Deployment

- **Azure Deployment**
  - Deploying Microservices on Azure Kubernetes Service (AKS)
  - Configuring Azure Cosmos DB for NoSQL Data
  - Setting Up Azure API Management

**Final Project:**  
**Deploy the E-Commerce Platform on Azure with Full CI/CD Pipelines**

- **Key Deliverables:**
  - A fully functional e-commerce platform accessible online
  - Deployment scripts and documentation
  - Monitoring with Azure Application Insights

---

### **Track 3: Databases, SQL, NoSQL, and DevOps**

#### **Objective:** Gain deep understanding of databases and DevOps practices, including Azure deployment.

#### **Weeks 5-6: Advanced SQL and Database Design**

- **Relational Database Concepts**
  - Normalization Techniques
  - Indexing and Query Optimization
  - Transactions and ACID Properties

- **Advanced SQL Queries**
  - Window Functions and CTEs
  - Stored Procedures and Triggers
  - Performance Profiling

**Hands-On Project:**  
**Design a High-Performance Database for a Ride-Sharing App**

- **Description:** Create a scalable database schema for a ride-sharing application like Uber or Lyft.
- **Key Features:**
  - Efficient queries for nearby drivers
  - Handling real-time data updates
  - Optimizing read and write operations

#### **Weeks 7-8: NoSQL Databases**

- **Introduction to NoSQL**
  - Understanding Document, Key-Value, Column-Family, and Graph Databases

- **MongoDB**
  - Data Modeling and Schema Design
  - Aggregation Framework
  - Replication and Sharding

- **Redis**
  - Advanced Data Structures
  - Implementing Caching and Session Storage
  - Pub/Sub Messaging

**Hands-On Project:**  
**Implement NoSQL Solutions for a Social Networking Site**

- **Description:** Design and implement a NoSQL database for a social networking platform focusing on user connections and activity feeds.
- **Key Features:**
  - Friend recommendations using graph databases (e.g., Neo4j)
  - Real-time activity feeds using Redis Pub/Sub
  - Flexible data models with MongoDB

#### **Weeks 9-10: DevOps Fundamentals**

- **Version Control with Git**
  - Advanced Git Techniques
  - Managing Releases and Hotfixes

- **CI/CD**
  - Implementing Pipelines with Jenkins, Travis CI, or Azure Pipelines
  - Continuous Testing and Deployment Strategies

- **Infrastructure as Code (IaC)**
  - Automating Infrastructure with Terraform
  - Configuration Management with Ansible

**Hands-On Exercises:**  
**Set Up a Full CI/CD Pipeline for a Web Application**

- **Key Tasks:**
  - Automate build, test, and deployment processes
  - Implement Blue-Green Deployment Strategy
  - Integrate with Azure services

#### **Weeks 11-12: Azure Deployment**

- **Azure Cloud Services**
  - Compute Options: VMs, App Services, Functions
  - Storage Solutions: Blob, File, Queue, Table Storage

- **Azure Databases**
  - Setting Up Azure SQL Database and Azure Cosmos DB
  - Data Migration Strategies

- **Monitoring and Logging**
  - Implementing Azure Monitor and Log Analytics
  - Setting Up Alerts and Dashboards

**Final Project:**  
**Deploy a Scalable Web Application with Robust Database Support on Azure**

- **Key Deliverables:**
  - End-to-end deployment scripts
  - Automated scaling configurations
  - Comprehensive monitoring setup

---

### **Track 4: System Design and Scalability**

#### **Objective:** Learn to design scalable systems and understand distributed systems principles.

#### **Weeks 5-6: System Design Fundamentals**

- **Understanding Requirements**
  - Functional and Non-Functional Requirements
  - Capacity Estimation and Traffic Analysis

- **High-Level Architecture Design**
  - Component Interaction Diagrams
  - Data Flow and Sequence Diagrams

- **Scalability and Load Balancing**
  - Load Balancing Algorithms (Round Robin, Least Connections)
  - CDN Integration

**Case Studies:**  
**Design a Content Delivery Network (CDN)**

- **Key Considerations:**
  - Geographical data distribution
  - Caching strategies
  - Handling high traffic volumes

#### **Weeks 7-8: Distributed Systems Concepts**

- **CAP Theorem**
  - Understanding Trade-Offs

- **Data Partitioning and Replication**
  - Consistent Hashing
  - Data Consistency Models

- **Consensus Algorithms**
  - Paxos and Raft

**Case Studies:**  
**Design a Distributed File Storage System like Google Drive**

- **Key Considerations:**
  - File synchronization
  - Conflict resolution
  - Data redundancy

#### **Weeks 9-10: Caching and Database Scaling**

- **Caching Strategies**
  - Write-Through, Write-Around, Write-Back
  - Cache Eviction Policies (LRU, LFU)

- **Database Scaling**
  - Master-Slave Replication
  - Multi-Master Replication
  - Distributed Transactions

- **Search Systems**
  - Implementing Full-Text Search
  - Indexing Strategies

**Case Studies:**  
**Design a Real-Time Analytics Platform**

- **Key Considerations:**
  - Handling streaming data
  - Real-time processing with tools like Apache Storm or Spark
  - Visualization of analytics

#### **Weeks 11-12: Microservices and Event-Driven Architecture**

- **Microservices Architecture**
  - Service Mesh Implementation
  - Circuit Breaker Patterns

- **Event-Driven Systems**
  - Designing Event Sourcing
  - CQRS (Command Query Responsibility Segregation)

- **API Design and Management**
  - Versioning Strategies
  - API Monetization Models

**Final Project:**  
**Design a Scalable Online Learning Platform**

- **Key Deliverables:**
  - Detailed system design document
  - Architectural diagrams
  - Prototype implementation of critical components

---

## **Additional Modules (Integrated Across Tracks)**

- **Git and Version Control**
  - Collaborative Workflows (GitFlow, Trunk-Based Development)
  - Code Review Best Practices

- **Testing and Quality Assurance**
  - Automated Testing Pipelines
  - Load Testing and Performance Benchmarking

- **Security Best Practices**
  - Secure Communication (TLS/SSL)
  - Data Encryption and Key Management
  - Compliance Standards (GDPR, HIPAA)

- **Networking and Protocols**
  - Understanding HTTP/2 and HTTP/3
  - WebSockets and Real-Time Communication
  - Network Security and Firewalls

- **Design Patterns**
  - Microservices Patterns (Saga, Event Sourcing)
  - Anti-Patterns and How to Avoid Them

---

## **Capstone Projects**

At the end of each track, you'll have the opportunity to apply your knowledge in a comprehensive, real-world project that showcases your skills.

- **Track 1:**  
  **Develop and Deploy a Social Media Backend on Azure**

  - Build a scalable backend for a social media platform with features like user profiles, posts, likes, comments, and real-time notifications.
  - Implement advanced search and recommendation systems.

- **Track 2:**  
  **Create and Deploy a Real-Time Chat Application with FastAPI**

  - Develop a chat application supporting direct messages and group chats.
  - Implement real-time communication using WebSockets.

- **Track 3:**  
  **Build a Comprehensive DevOps Pipeline for a SaaS Application**

  - Design and implement a complete CI/CD pipeline.
  - Ensure high availability and disaster recovery setups.

- **Track 4:**  
  **Design and Prototype a Video Streaming Service**

  - Architect a system similar to Netflix or YouTube.
  - Address challenges like video encoding, storage, and content delivery.

---

## **Recommended Resources**

- **Books:**
  - *Clean Code* by Robert C. Martin
  - *Spring Boot in Action* by Craig Walls
  - *Building Microservices* by Sam Newman
  - *Designing Data-Intensive Applications* by Martin Kleppmann

- **Tools and Platforms:**
  - **Version Control:** Git and GitHub
  - **Cloud Services:** Microsoft Azure
  - **Containerization:** Docker and Kubernetes
  - **Monitoring:** Prometheus, Grafana, and Azure Monitor

---

## **Why Choose Ednova?**

- **Hands-On Learning:** Apply concepts through projects and practical exercises.
- **Career Support:** Receive guidance on interview preparation and career advancement.
- **Flexible Learning Paths:** Customize your education by choosing tracks that align with your goals.
- **Real-World Projects:** Work on creative projects that mirror industry challenges.

---

## **Next Steps**

Ready to embark on your backend engineering journey with Ednova?

- **Enroll Today:** Secure your spot in the upcoming cohort.
- **Connect with Peers:** Join our community forums and study groups.
- **Prepare for Success:** Review the recommended resources and get a head start.

---

## **Contact Us**

For any questions or additional information, please reach out to us at:

- **Email:** [zaccarie@ednova.ai](mailto:zaccarie@ednova.ai)
- **Phone:** +33 660 117 897
- **Website:** [www.ednova.app](http://www.ednova.app)

---

**Ednova** – Empowering the next generation of backend engineers.

---

# **Appendix**

## **Sample Weekly Schedule**

### **Week 1**

- **Tuesday:**
  - **Lecture (2 Hours):**
    - Introduction to Programming in Python and Java
    - Overview of Backend Development
  - **Reading Assignment (1 Hour):**
    - Data Types and Variables in Python and Java

- **Thursday:**
  - **Hands-On Coding (3 Hours):**
    - Implement Basic Algorithms (e.g., Fibonacci, Factorial)
    - Practice Problems on Arrays and Strings

- **Saturday:**
  - **Lecture (2 Hours):**
    - Control Structures and Functions
  - **Lab Session (2 Hours):**
    - Build a Simple CLI Calculator in Both Languages
---

## **FAQs**

**Q:** Can I switch tracks after choosing them?  
**A:** Yes, you can adjust your tracks within the first week of the specialized modules.

**Q:** Do I need prior programming experience?  
**A:** Basic programming knowledge is helpful. The foundational modules will get you up to speed.

**Q:** Will there be support if I have questions outside of class hours?  
**A:** Yes, our instructors are available for additional support.

**Q:** Are the projects team-based or individual?  
**A:** We offer both individual and team-based projects to simulate real-world working environments.

---

## **Commitment to Excellence**

At Ednova, we are committed to providing an exceptional learning experience. We continually update our curriculum to reflect industry trends and employer demands, ensuring you receive education that is both current and relevant.

---

**Embark on your journey to become a skilled backend engineer with Ednova. Your future in technology starts here.**

---

# **End of Curriculum Document**

Please note that this markdown document is formatted to be converted into a PDF. It includes headers, bold text, bullet points, and other markdown elements that translate well into PDF formatting. The projects have been made more creative and aligned with real-world applications to enhance learning and practical experience.
