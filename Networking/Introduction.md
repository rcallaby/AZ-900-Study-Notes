# Networking

Azure is Microsoft’s cloud computing platform that allows users to build, deploy, and manage applications and services through a global network of data centers. As an AZ-900 exam candidate, it’s important to understand the basics of networking in the Azure cloud environment. In this article, we’ll cover the following topics:

* Virtual Networks in Azure

* Azure Subnets

* Azure Network Security Groups (NSGs)

* Azure Load Balancer

* Azure Application Gateway

## Virtual Networks in Azure
Virtual networks (VNet) in Azure provide a private and secure network connection between Azure resources. VNets allow users to define their IP address space, configure routing tables, and subnets. When you create a virtual machine in Azure, it is connected to a VNet that provides it with an IP address, allowing it to communicate with other resources within the same VNet.

## Azure Subnets
A subnet is a range of IP addresses within a virtual network that can be used to segment network traffic. Azure subnets allow users to partition their VNet into smaller networks to improve performance and security. Subnets can be used to group resources by function, application, or security requirements. For example, you might create a subnet for your web application servers and another subnet for your database servers.

## Azure Network Security Groups (NSGs)
Azure Network Security Groups (NSGs) provide a way to filter network traffic to and from Azure resources in a VNet. NSGs allow you to create rules that specify which traffic is allowed or denied. For example, you might create an NSG rule that allows traffic from your web servers to your database servers but denies traffic from the internet to your database servers.

## Azure Load Balancer
Azure Load Balancer is a Layer 4 (Transport Layer) load balancer that distributes incoming traffic across multiple resources in a VNet. Load balancing can improve application availability and scalability by distributing traffic across multiple instances of an application. Azure Load Balancer can be used for both inbound and outbound traffic.

## Azure Application Gateway
Azure Application Gateway is a Layer 7 (Application Layer) load balancer that provides advanced traffic management capabilities for web applications. Application Gateway can be used to improve the availability, scalability, and security of web applications by distributing traffic based on URL paths or hostnames, performing SSL termination, and applying web application firewall (WAF) rules to protect against common web vulnerabilities.


Azure provides a range of networking services that allow users to build secure, scalable, and highly available applications in the cloud. As an AZ-900 exam candidate, it's important to have a solid understanding of Azure virtual networks, subnets, NSGs, Load Balancer, and Application Gateway. By mastering these concepts, you'll be well on your way to becoming an Azure certified professional.