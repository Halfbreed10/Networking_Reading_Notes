# Ops Reading Notes

## Networking and Systems Administrations

## Network Scanning with NMAP
Undertanding how port work and what each port is used for helps with troubleshooting. If you a missing a certain connection, you can go directly to that specific port to assess the issue.

What is a port? Describe it with an analogy that would help a family member understand. A port is a virtual location where networking communication starts and ends. For example, imagine a port on a computer like different doors in a house. Each door serves a specific purpose, allowing different things to come in and out. 

What does a port scanner send to a port to check the current status? A port scanner sends a network request to connect to a specific TCP or UDP port on a computer and records the response.

When a port scanner sends a request to connect, what are the three possible responses? Describe them. The three possible responses are open, closed, or filtered. Open means the port is not in use and will allow you to transfer data. Closed means the port is currently in use and will not allow transmission of data. Lastly, filtered means you will no recieve a response, therefore you were either blocked or dropped from connection with the port.

What is the difference between TCP and UDP? The difference between TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) is that TCP sends each packet in order, complete with error checking, verification, and a 3-way handshake to confirm each packet is successful. UDP tends to be faster and is a connectionless protocol, so programs that use UDP just send the data and if you miss a packet, you will never get it again. An example of UDP is live straming and online gaming. 

Common Ports

List and describe the ports used for the following:
Telnet- Port 23 TCP, Telecommunication Network Protocol, if you need to get a console screen from a remote device, this allows you to connect to that device remotely, and you’re able to view information on the single terminal screen.
SSH- Port 22 TCP, Secure Shell, all information sent through this port in encrypted to be more secure. In order to switch  a router, or firewall, or any other server on the network using this terminal communication would need to be done through port 22.
DNS- Port 53 UDP, Domain Name System, used to convert the name that you’re typing in to the IP address of the service.
SMTP- Port 25 or for encrypted SMTP that use TLS use port 587, Simple Mail Transfer Protocol,  is server-to-server communication and it’s one of the most common ways to send email messages over the internet.
HTTP- Port 80 TCP, Hypertext Transfer Protocol, sends information between the client and the server over a nonencrypted communications channel.
HTTPS- Port 443 TCP, Hypertext Transfer Protocol Secure, this encrypted communication historically used SSL, or Secure Sockets Layer, although newer web servers will use a newer version of SSL called TLS, or Transport Layer Security.
RDP- Port 3389 TCP, Remote Desktop Protocol, remote access software that provides shared desktop view.
Ping- uses ICMP, therefore are no real ports being used. ICMP roots itself to the IP address.

## Resources:
https://www.varonis.com/blog/port-scanning-techniques
https://www.professormesser.com/network-plus/n10-008/n10-008-video/common-ports-n10-008/
google.com

## Things I would like to know more about
