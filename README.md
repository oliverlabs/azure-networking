# A Curated List of Azure Networking Resources

The resources linked in this repo can be used to prepare for your AZ-700 exam or simply to get more familiar with networking concepts in Microsoft Azure. #

Enjoy! :roller_coaster:

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Markdown Link Checker](https://github.com/oliverlabs/azure-networking/actions/workflows/markdown-link-checker.yml/badge.svg)](https://github.com/oliverlabs/azure-networking/actions/workflows/markdown-link-checker.yml)

## Blogs

1. [MS Tech Community: Azure Network Security Blog](https://techcommunity.microsoft.com/t5/azure-network-security-blog/bg-p/AzureNetworkSecurityBlog)
2. [Azure Network Security - Interactive Guide](https://mslearn.cloudguides.com/guides/Azure%20network%20security)

## GitHub Resources

1. [Enterprise-class networking in Azure - Hands-on Lab][def1]
   
   In this workshop, you will learn to setup and configure a virtual network with subnets in Azure. You will learn how to secure the virtual network by deploying a network virtual appliance and configure firewall rules and route tables. Additionally, you will set up access to the virtual network with a jump box and a site-to-site VPN connection.
   
   At the end of the workshop, you will be better able to plan and design virtual networks in Azure with multiple subnets to filter and control network traffic. In addition, you will learn to create a virtual network and provision subnets, create route tables with required routes, build a management jump box, configure firewalls to control traffic flow, and configure site-to-site connectivity.
2. [Azure Private DNS Resolver Micro-Hack][def2]
   Great diagrams and terraform code.
3. [Azure Private DNS Resolver Bicep Lab][def3]
4. [Basic Terraform Network][def4]
5. [Azure Terraform VNet][def5]
6. [Traffic Flows in Common Azure Networking Patterns][def6]
7. [Azure Networking Lab from Jose Moreno][def7]

8. [Draw.io Network Diagrams: The Art of Possible in Azure Networking and the Why][def8]
9. [Azure Networking Security and Lab Templates][def9]
10. [Azure Networking Labs PDF][def10]
    
    This set of Azure Networking labs are simplified to demonstrate a single concept in each lab, using Azure portal or Azure CLI. Each lab has a lab diagram that provides information on the lab setup. Most labs build on each other so prior setup is expected. Please use the lab diagram as guidance if you are doing a specific lab out of order.

11. [A Journey through Azure Networking][def11]
    
    This repository contains a collection of core networking patterns starting from basic to advanced. The goal is to assist customers with picking the right pattern for their stage of the journey. Each pattern includes a summary, benefits and considerations, and diagrams providing examples of the patterns and what the route tables could look like.

12. [Azure PrivateLink DNS MicroHack][def12]
    
    This microhack will walk you through the steps to configure Azure PrivateLink DNS. You will learn how to configure Azure PrivateLink DNS to resolve private endpoints in a virtual network. You will also learn how to configure Azure PrivateLink DNS to resolve private endpoints in a virtual network that is peered to another virtual network.
13. [Hub and Spoke Network Lab (Terraform): Dual-region Hub and Spoke Topology][def13]

      This repo provides Terraform templates for a dual-region hub and spoke topology, connected to simulated on-prem datacenters.

14. [Private DNS Resolver with Forwarding Rules (Bicep)][def14]

15. [Private Link/Endpoint DNS Integration Resources][def23]

16. [Azure Virtual Network Manager Hands-on Lab][def25]

17. [vWAN and AVNM for Red/Blue Scenarios][def26]
18. [Azure Virtual WAN Labs by dmauser](https://github.com/dmauser/azure-virtualwan/tree/main)
19. [Global Secure Access With Microsoft Security Service Edge (SSE)](https://www.youtube.com/watch?v=W2wM774n6Nc)
20. [Azure Network Security - Use Azure Firewall as a DNS Proxy in a Hub and Spoke topology along with Private Endpoints](https://github.com/Azure/Azure-Network-Security/tree/master/Azure%20Firewall/Template%20-%20Azure%20Firewall%20as%20a%20DNS%20Proxy%20in%20Hub%20and%20Spoke%20topology)
21. [ESU enabled by Azure Arc, Network Considerations](https://github.com/adstuart/azure-arc-esu)
22. [AVS Enterprise-Scale Networking](https://github.com/Azure/Enterprise-Scale-for-AVS/tree/main)

# Azure Networking Services

Here is a list of Microsoft Azure services that can be used to demonstrate networking concepts in Azure. This list is not exhaustive, but it is a good starting point.

- Azure Bastion
- Azure DDoS Protection
- Azure Firewall
- Network Security Groups / Application Security Groups
- Azure Private Link
- Azure VPN
- Azure Application Gateway
- Azure Front Door
- Azure Traffic Manager
- Azure Network Watcher
- Azure Virtual Network Manager
- Network Security Checklist
- Azure VirtualWAN
  
# Microsoft Certification
## Learning Path
Here is a link to [AZ-700: Microsoft Azure Networking Technologies][def16] learning path on Microsoft Learn.

## Exam 
Link to the [AZ-700][def17] exam.

## Study Guide
[AZ-700 Study Guide][def18] should help you understand what to expect on the exam. It includes a summary of the topics the exam might cover and links to additional resources.


# Noteable Articles
A collection of weekly Networking articles and resources worth reading:

## March 2024
- [Use Azure cloud native DNS resolver for split horizon][def30]

## December 2023
- [Use a cloud native DNS resolver in Azure][def29]

## September 2023
- [Using DNS in Azure IaaS][def28]

## March 2023 
- [Azure vWAN - A RED & BLUE puzzle solved with Virtual Network Manager][def22]
- [Azure Network Security webinar: Content Inspection Using TLS Termination with Azure Firewall Premium][def24]
- [Use traffic analytics to spot common azure network mistakes][def27]

# Noteable YouTube Channels

- [Adam Stuart][def19]

- [John Savill][def20]

- [Nehali Neogi][def21]

<!-- Links -->

[def1]: https://github.com/microsoft/MCW-Enterprise-class-networking
[def2]: https://github.com/dawlysd/azure-dns-private-resolver-microhack
[def3]: https://github.com/mddazure/dns-resolver-lab
[def4]: https://github.com/Azure/terraform-azurerm-network/blob/main/examples/startup/main.tf
[def5]: https://github.com/Azure/terraform-azurerm-vnet/tree/main/examples
[def6]: https://github.com/mattfeltonma/azure-networking-patterns
[def7]: https://github.com/erjosito/azure-networking-lab
[def8]: https://github.com/nehalineogi/azure-networking
[def9]: https://github.com/Azure/Azure-Network-Security/tree/master/Lab%20Templates
[def10]: https://github.com/Azure/Azure-Network-Security/tree/master/Lab%20Templates
[def11]: https://github.com/mattfeltonma/azure-network-journey
[def12]: https://github.com/adstuart/azure-privatelink-dns-microhack
[def13]: https://github.com/fguerri/hubandspokelab
[def14]: https://github.com/mddazure/dns-resolver-lab
[def16]: https://learn.microsoft.com/en-gb/training/paths/design-implement-microsoft-azure-networking-solutions-az-700/
[def17]: https://learn.microsoft.com/en-gb/certifications/exams/az-700
[def18]: https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE4PaHw
[def19]: https://www.youtube.com/@AdamStuart1
[def20]: https://www.youtube.com/@NTFAQGuy
[def21]: https://www.youtube.com/@nehalineogi
[def22]: https://github.com/Danieleg82/vWAN-and-AVNM-For-Red-Blue/blob/main/README.md
[def23]: https://github.com/dmauser/PrivateLink
[def24]: https://www.youtube.com/watch?v=A-hWyZZsFVY&t=1s&ab_channel=MicrosoftSecurityCommunity
[def25]: https://github.com/adtork/Lab-Azure-Virtual-Network-Manager
[def26]: https://github.com/Danieleg82/vWAN-and-AVNM-For-Red-Blue
[def27]: https://autosysops.com/blog/use-traffic-analytics-to-spot-common-azure-network-mistakes
[def28]: https://autosysops.com/blog/azure-dns-explained
[def29]: https://autosysops.com/blog/cloud-native-dns-resolver-in-azure
[def30]: https://autosysops.com/blog/use-azure-cloud-native-dns-resolver-for-split-horizon
