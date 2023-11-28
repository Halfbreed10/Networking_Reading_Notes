# Ops Reading Notes

## Networking and System Administrations- OSI layers
OSI model is important to learn and understand because it is a key component of trouble shooting. Depending on the issue understiand the & OSI layers you can troubleshoot more effectively. 

What does “OSI” stand for? OSi stands for Open Systems Interconnection, and it is a 7-layer architecture with each layer having specific functionality to perform. All 7 layers work collaboratively to transmit the data from one person to another across the globe.

List the 7 layers of the OSI model and what each one is responsible for.
Physical Layer- the lowest layer of the OSI and it is responsible for the actual physical connection between devices and for transmitting individual bits from one node to the next. When receiving data, this layer will get the signal received and convert it into 0s and 1s and send them to the Data Link layer, which will put the frame back together.   
Data Link Layer- responsible for the node-to-node delivery of the message. The main function of this layer is to make sure data transfer is error-free from one node to another, over the physical layer. When a packet arrives in a network, it is the responsibility of the DLL to transmit it to the Host using its MAC address.
Network Layer- responsible for the transmission of data from one host to the other located in different networks. It also takes care of packet routing i.e. selection of the shortest path to transmit the packet, from the number of routes available.
Transport Layer- provides services to the application layer and takes services from the network layer. The data in the transport layer is referred to as Segments. It is responsible for the End to End Delivery of the complete message. The transport layer also provides the acknowledgment of the successful data transmission and re-transmits the data if an error is found. 
Session Layer- responsible for the establishment of connection, maintenance of sessions, and authentication, and also ensures security.
Presentation Layer- also referred too as the "Translation" layer. The data from the application layer is extracted here and manipulated as per the required format to transmit over the network. 
Application Layer- implemented by the network applications. The applications produce the data, which has to be transferred over the network. This layer also serves as a window for the application services to access the network and for displaying the received information to the user. 

Distinguish which layers are the “hardware layers”, and which layers are the “software layers”. What does that even mean? The hardware layers (Physical and Data Link) deal directly with physical components and low-level communication, while the software layers (Network, Transport, Session, Presentation, and Application) involve more software-related functions, user interaction, and high-level data manipulation.

How can the OSI model be used in troubleshooting? OSI can be used for troubleshooting because depending on the issue, for example a network issue, you can go directly to that layer to diagnose the issue.

## What is Wireshark and How is it used?

What is Wireshark? Wireshark is a network protocol analyzer, or an application that captures packets from a network connection, such as from your computer to your home office or the internet.

What is a packet? Packet is the name given to a discrete unit of data in a typical Ethernet network. 

What 3 high-level things does Wireshark accomplish? How could these be used for nefarious purposes? For benevolent purposes? The 3 high level things Wireshark does are Packet Captutring, Flitering, and Visualiztion. Some nefarious purposes that could possibly be used are stealing sensative information, exploiting vulnerabilites, and collecting information. Some benevolent purposes could be identifying network issues, performance monitoring, and root cause analysis. 

## Resources:
https://www.geeksforgeeks.org/open-systems-interconnection-model-osi/
https://www.comptia.org/content/articles/what-is-wireshark-and-how-to-use-it
google.com
chatgpt

## Things I would like to know more about
