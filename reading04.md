# Ops Reading Notes

## Networking and Administrations

### Virtual Network Settings
We use VM's in the course and will continue to use them in the field. Understading the settigns will make for quick and easy use of the VM's.

Which network mode in VirtualBox can be used to emulate unplugging the Ethernet cable from the network? Not attached mode will emulate unplugging the Ethernet cable from the network.

Which network mode would be best if you wanted to run a server on a VM that could be fully accessible from your physical local area network? You would want to run it in NAT mode.

What are the three options of promiscuous mode and what does each do? The three options of Promiscuous Mode are Deny, Allow VMs, and Allow All. Deny hides any traffic that is not intended to the virtual network adapter of the VM. Allow VM's hides all traffic from the VM network adapter except the traffic transmitted to and from other VMs. Lastly, Allow All has no restrictions and the VM network adapter can see all incoming and outgoing traffic. 

What is Port Forwarding? Port forwarding can be used to configure access from the host machine and other hosts of the same physical network to the services running on the guest OS inside the VM 

### Resources:
https://www.nakivo.com/blog/virtualbox-network-setting-guide/

## Things I would like to know more about 
