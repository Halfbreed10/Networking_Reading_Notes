# Ops Reading Notes

## Network and Systems Administration

### Network Address Translation (NAT)

What is the main purpose for implementing NAT on a network? The main purpose of implementing NAT is to allow multiple devices to access the Internet through a single public address.

At what layer of the OSI model does NAT happen? Nat happens at the the third layer in the OSI model.

What happens to packets when NAT runs out of addresses in the pool of available IPs? If NAT runs out of addresses in the pool the packets will be dropped and an Internet Control Message Protocol (ICMP) host unreachable packet to the destination is sent.

What disadvantage does using NAT pose for routers? The disadvantage of using NAT pose for routers are translation results in switching path delays, certain applications will not function while NAT is enabled, complicates tunneling protocols such as IPsec, and lastly the router being a network layer device, should not tamper with port numbers(transport layer) but it has to do so because of NAT. 

### Resources:
https://www.geeksforgeeks.org/network-address-translation-nat/

## Things I would like to know more about
