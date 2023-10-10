Aneissa Uribe

**CIT114 - Notes 05, Networking and Content Delivery**

*Computer Network*

- Two or more machines that are connected together in order to communicate

*IP Address*

- A unique number assigne to a machine in order to identify it uniquely

- 32-bit IP address is called an IPv4 address

- 128-bit IP address is called an IPv6 address; composed of eight groups of four letters and numbers seperated by colons

*Classless Inter-Domain Routing (CIDR)*

- networks and group of IP addresses
- first address of the network, followed by '/'
- Ex. 192.0.2.0/24 , 24 tells you that the first 24 bits must be fixed and the last 8 bits are flexible

*Open Systems Interconnection (OSI) model*

- A model that is used to explain data as it travels over a network

*Amazon VPC (Virtual Private Cloud)*

- You can launch AWS resources in a virtual network
- You have control over the resources
- Can customize the network configuration for your VPC
- Can add multiple layers of security

*VPC*

- isolated from other VPC's
- in your AWS account
- belong to a single AWS Region and can span into multiple availability zones

*Subnets*

- Range of IP addresses that divide a VPC
- Belong to a single availability zone
- can be labeled as public or private

*IP Addressing*

- When you create a VPC, you assign to an IPv4 CIDR block
- cannot change the address range
- largest IPv4 CIDR block size is /16
- smallest IPv4 CIDR block size is /28

*Reserved IP Addresses*

- 5 are reserved by AWS

*Public IPv4 Address*

- manually assigned through an Elastic IP address
- automatically assigned

*Elastic IP Address*

- Associated with an AWS account
- can be allocated and remapped anytime
- additional costs might apply

*Elastic network interface*

- a virtual network interface that can be attached to an instance and detached and attach to another to redirect network traffic

*Route Table*

- contains set of rules that you can configure to direct network traffic from your subnet

*NAT Gateway*

- managed service that provides better availability, higher bandwidth, and less administrative effort

*VPC Peering*

- Can connect VPC's in your own account, between other accounts, or between Regions

*Security Group*

- virtual firewall that controls inbound and outbound traffic

*Network access contro lists (network ACLs)

- control list work at the subnet level, controls traffic in and out of the subnet

*Route 53*

- high available and scalable Domain Name System (DNS) web service

*Amazon CloudFront*

- fast, global, and secure CDN service
- pay-as-you-go pricing

**Question 2**

\You have complete control over your virtual networking environment, including selection of your own IP address range, creation of subnets,configuration of route tables, and gateways.  

- I find this line interesting because before Cloud, testing was done on premises and you weren't able to choose your own IP address and subnets. It has evolved.

/Route 53 finds out where the customer is located in the world, and i responds with the IP address of the edge location closest to that customer

- I find this interesting because it shows how advanced Amazon has gone with their technology and how well structured their cloud services are.

**Question 4**

  How were IP addresses created and configured for computers to read them?
