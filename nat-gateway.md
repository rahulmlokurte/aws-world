
**NAT Gateway**

A NAT is a Network Address Translation (NAT) service. This is a service that is used in routers and its purpose is to translate a set of IP addresses to another set of IP addresses and the reason for having the NAT service is to help preserve the limited amount of IPV4 public addresses that we have available around the world. There are 4,294,967,296 public IPV4 addresses. So, in order to prevent a shortage of public IPV4 addresses, engineers developed private IP addresses and network address translation(NAT).

There are two types of IPV4 addresses. One is public IPV4 address and another is private IPV4 address. Public IP addresses are publicly registered on the Internet. We have to have a public IP address, if we want to use internet. Private IP address are not publicly registered, so we cannot directly access the internet. Private IP addresses are only used internally such as inside a home and business.

The router is what assigns our internal devices a private IP. Most homes and businesses are not going to have just one device that needs internet access. They are going to have multiple devices that need access to the internet. So, those devices need a public IP address if they want to access the internet. The router assigns all of our devices a private IP addresses and when our devices need to access the internet, the private IP address will be translated by NAT in the router to the one public IP address that we have been given. 

The NAT will also translate public IP address to private IP address. If computer out on the internet wants to communicate with a computer on this private network, then the public IP address needs to be translated by NAT to the private IP address for that computer.

