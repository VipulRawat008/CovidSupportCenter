# Proposal review for EAD feature Submission

### 	1. EAD Group Number - 28 

### 	2. Name of Students

| Name           | Roll Number  |
| -------------- | ------------ |
| Utkarsh Aditya | S20180010182 |
| Vipul Rawat    | S20180010192 |
| Pradum Singh   | S20180010136 |
| Sumanth Bhat   | S20180010171 |
| Sushant Bondle | S20180010030 |

### 	3. Option Chosen - New Project with MERN/MEAN Stack - **Option 2**

### 	4. Name of Project - Covid Support Center

### 5. Brief Description of the EAD feature to be implemented

**Security**   

1. **HTTPS** - Implementation of HTTPS security protocol using node.js. **Access tokens** are usually short-lived JWT Tokens, signed by your server, and are included in every HTTP request to your server to authorize the request. We are storing the JWT tokens in the local storage since its convenient. 
2. **Authorization** - Used JWT token for user authentication. **JSON Web Token** is a means of representing claims to be transferred between two parties. The claims in a JWT are encoded as a JSON object that is digitally signed using JSON Web Signature and/or encrypted using JSON Web Encryption.
3. **CSRF Protection** -  We are planning to utilize the ASP.NET which has the capability to generate anti-CSRF security tokens for consumption by your application.

**Scalability** 

1. **Dockerizing MERN stack application for scalability** - Dockerizing refers to the process of enclosing our MERN application in a container. A container is the standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. 

2. Utilizing **Kubernetes** for load balancing to make scalable web application. 

   ![img](https://miro.medium.com/max/835/1*Mgrhryt4agUB2CMiGjyJNQ.png)

To avoid performance bottlenecks, we will use the concept of load balancing to create a distributed architecture. A load balancer is a process that takes in HTTP requests and forwards these HTTP requests to one of a collection of servers.

### 6. Who is going to implement the feature ?

| Name           | Feature     |
| -------------- | ----------- |
| Utkarsh Aditya | Scalability |
| Vipul Rawat    | Security    |
| Pradum Singh   | Scalability |
| Sumanth Bhat   | Security    |
| Sushant Bondle | Security    |

### 7. Any Remarks - None