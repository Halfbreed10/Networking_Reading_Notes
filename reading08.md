# Ops Reading Notes

## Network and System Administrations

### RADIUS Authentication

Computer Network - AAA (Authentication, Authorization and Accounting)

Explain each of the three A’s as you would to a non-technical family member. Use an analogy or a story. The first A is Authentication, which is the process to authenticate you are who you say you are, such as going to the store using a credit card and the cashier checking your id. The second A is Authorization, which is the process of allocating what uou are allowed to do after you have been authenticated, for example going to a basktball game. You enter the stadium and you are allowed in the crowd, however you do not have authorization to go on the court. The last A is Accounting, which is the process of monitoring what you are doing during the time you are at the basketball game, such as security and cameras making sure you are not getting out of line.

What should the administrator do if the ACS server fails to authenticate a user during AAA implementation? The administrator should mention using the local database of the device as a backup, in the method list, to implement AAA.

What is the role of the NAS in the AAA implementation using an ACS server? Use a diagram.
  +-------------------+
     |   End-User/Client |
     +-------------------+
               |
               |
               v
        +-------------+
        |     NAS     |   <------ Network Communication ------>
        +-------------+               |
               |                      |
               |                      |
               v                      v
       +------------+        +-----------------------+
       |  ACS Server|        |  Network Resources    |
       +------------+        +-----------------------+
RADIUS Concepts

What are the benefits of using RADIUS for authentication and authorization? The benefits are centralized authentification, Enhanced Security, Scalability and Flexibility, Policy-Based Authorization, and Cost Effectiveness. 

What is RADIUS and what does it stand for? RADIUS stands for Remote Authentication Dial-In User Service.

Research: What encryption algorithms does RADIUS use? RADIUS relies on several encryption algorithms and protocols to secure authentication and communication between RADIUS clients and servers. Such as PAP (Password Authentication Protocol), CHAP (Challenge-Handshake Authentication Protocol), MS-CHAP (Microsoft Challenge-Handshake Authentication Protocol), EAP (Extensible Authentication Protocol), TLS (Transport Layer Security), and IPsec (Internet Protocol Security). 

### Resources
https://www.geeksforgeeks.org/computer-network-aaa-authentication-authorization-and-accounting/
https://chat.openai.com/c/3e77b188-7f6b-44ff-b492-cd67d69fcd0c
https://archive.is/27Y19

### Things I would like to know more about 
RADIUS. I dont really understand it.
