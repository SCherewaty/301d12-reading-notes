Reading
VirtualBox Network Settings Guide

Which network mode in VirtualBox can be used to emulate unplugging the Ethernet cable from the network?
The "Not Attached" mode will emulate unplugging the ethernet cable from the network.

Which network mode would be best if you wanted to run a server on a VM that could be fully accessible from your physical local area network?
The "Bridged Adapter" mode will accomplish this.

What are the three options of promiscuous mode and what does each do?
Deny - "Any traffic that is not intended to the virtual network adapter of the VM is hidden from the VM. This option is set by default."
Allow VM's - "All traffic is hidden from the VM network adapter except the traffic transmitted to and from other VMs."
Allow All - "There are no restrictions in this mode. A VM network adapter can see all incoming and outgoing traffic."

What is Port Forwarding?
"Port forwarding is a process of intercepting traffic addressed to the appropriate IP address and port in addition to redirecting that traffic to a different IP address and/or port."

Sources:
VirtualBox Network Settings: Complete Guide
Updated: June 1, 2023
Written by: NAKIVO Team
https://www.nakivo.com/blog/virtualbox-network-setting-guide/

## Things I want to know more about
