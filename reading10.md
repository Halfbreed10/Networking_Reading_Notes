# Ops Reading Notes

## Network and System Administrations

### VPC
Virtual private cloud is important to this section because we have been dealing with online services such as AWS. 

How can one host within a VPC any services that need to be public? One can provide services by leveraging public subnets, internet gateways, appropriate security configurations, and public IP addresses or Elastic IPs, you can securely host services within a VPC while making them accessible to the public internet. 

What are examples of services that would live in the publicly-accessible part of the VPC? The privately-accessible part? Services that would live in the publicly-accessible part of the VPC are web servers, application servers, load balancers, Content Delivery Networks (CDNs), DNS servers, email servers, remote access, and authentification services. For privately accessing the VPC are data base servers, message queues and brokers, internal APIs, and backennd proccessing. 

What are the trade-offs of using a VPC vs traditional infrastructure? Some trade offs are dependecy on internet connectivity, data privacy and controls, cost predictability, latency and performance.

### Resources:
https://www.cloudflare.com/learning/cloud/what-is-a-virtual-private-cloud/
https://www.cloudflare.com/learning/cloud/what-is-multitenancy/
https://chat.openai.com/c/3e77b188-7f6b-44ff-b492-cd67d69fcd0c

### Things I would like to know more about
