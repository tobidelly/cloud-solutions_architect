# Core Architectural Components of Azure: A Comprehensive Guide

![image](https://github.com/tobidelly/cloud-solutions_architect/assets/111124314/7330d08f-b563-4c71-892d-762eeabc79f3)


Azure is a robust cloud computing platform that offers a wide range of services and tools to support the development and deployment of scalable and reliable applications. At the heart of Azure's architecture are several core components that work together to provide high availability, scalability, and manageability. In this blog, we will explore the core architectural components of Azure, including Azure regions, availability zones, Azure Resource Manager, resource groups, subscriptions, and management groups.

**Azure Regions**

![image](https://github.com/tobidelly/cloud-solutions_architect/assets/111124314/5e537442-05e0-4ef7-a1a2-70fbc5cf614d)


Azure regions are geographic locations where Microsoft Azure operates data centers. These regions provide organizations with the flexibility to deploy their resources in specific regions for performance optimization, compliance, and availability purposes. Each region is a set of data centers deployed within a latency-defined perimeter and connected through a dedicated regional low-latency network. With more global regions than any other cloud provider, Azure gives customers the flexibility to deploy applications where they need to. Azure is generally available in 52 regions around the world, with plans announced for 6 additional regions

**Azure Availability Zones**

![image](https://github.com/tobidelly/cloud-solutions_architect/assets/111124314/df772698-a585-4c58-80f5-918938a26d5a)


Azure Availability Zones are unique physical locations within an Azure region. Each zone is made up of one or more data centers equipped with independent power, cooling, and networking infrastructure. The physical separation of Availability Zones within a region protects applications and data from datacenter failures. Zone-redundant services replicate applications and data across Azure Zones to protect from single-points-of-failure. Not every region has support for Availability Zones, but examples of regions with Availability Zones include Central US, East US 2, West US 2, West Europe, France Central, North Europe, and Southeast Asia

**Azure Resource Manager**

![image](https://github.com/tobidelly/cloud-solutions_architect/assets/111124314/f756fd47-91e5-4311-b1cd-daa2d7b541d5)


Azure Resource Manager (ARM) is a tool that lets you work with all the underlying resources that are part of a solution as a group. With ARM, you can deploy, update, and even delete all resources that form a solution in a single, coordinated operation. ARM also allows you to use templates to streamline deployments. Such templates can be used to uniformly deploy separate environments, such as development, staging, and production. Resource Manager provides a consistent management layer for all Azure resources, security and auditing features, as well as tagging features that you can use to manage your resources once they've been deployed into Azure[2].

**Resource Groups** 

![image](https://github.com/tobidelly/cloud-solutions_architect/assets/111124314/0f525f31-1aa0-4a54-b264-96f489681033)


Resource groups are logical containers in Azure that hold related Azure resources that are part of a larger Azure solution. These resource groups can host all resources that comprise an overall Azure solution, or they can also host just the resources that need to be managed as part of a group. The administrator gets to decide, based on needs, how to allocate resources in resource groups within Azure. When working with Azure resource groups, there are a few things to consider. First and foremost, since all resources within a single resource group usually share a similar lifecycle, it's important to determine the lifecycle of the resources you plan to place in a single resource group.

**Subscriptions**

In Azure, subscriptions are a unit of management, billing, and scale. To create and use Azure services, you need an Azure subscription which is linked with an Azure account, which is an identity in Azure Active Directory (Azure AD). After you've created an Azure account, you're free to create additional subscriptions. A company might use a single Azure account for your business and separate marketing, and sales departments.

**Management Groups**

Azure management groups provide a level of scope above subscriptions. You organize subscriptions into containers called management groups and apply governance conditions to the management groups. For a company dealing with multiple applications, multiple development teams, in multiple geographies, and having many subscriptions, you might need a way to efficiently manage access, policies, and compliance for those subscriptions. Azure management groups provide a way to do this.

**Conclusion**

In conclusion, the core architectural components of Azure include Azure regions, availability zones, Azure Resource Manager, resource groups, subscriptions, and management groups. These components work together to provide high availability, scalability, and manageability for Azure applications and services. Understanding these components is crucial for building and deploying scalable and reliable applications on the Azure platform.


## Citations:
[1] https://faun.pub/core-architectural-component-of-azure-1a2da1b2f909?gi=42f4374e9209
[2] https://cloudacademy.com/blog/understanding-core-azure-architectural-components/
[3] https://k21academy.com/microsoft-azure/architect/azure-availability-zones-and-regions/
[4] https://learn.microsoft.com/en-us/azure/reliability/availability-zones-overview
[5] https://azure.microsoft.com/en-us/explore/global-infrastructure/availability-zones
[6] https://www.ninjaone.com/blog/what-is-azure-resource-manager/
[7] https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/overview
[8] https://learn.microsoft.com/en-us/azure/governance/management-groups/manage
[9] https://learn.microsoft.com/en-us/azure/governance/management-groups/overview
