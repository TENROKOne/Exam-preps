https://docs.github.com/en/get-started/writing-on-github

# Exam Resources

https://learn.microsoft.com/nl-nl/credentials/certifications/resources/study-guides/az-900

# Skills at a glance

- Describe cloud concepts (25–30%)
- Describe Azure architecture and services (35–40%)
- Describe Azure management and governance (30–35%)

## Describe cloud concepts (25–30%)

### 1. Describe cloud computing

1.1 Define cloud computing
    - Providing computer services over the internet
    - Computer, Networking and Storage
    - Benefids of the cloud:
        - High availability
            - SLA (Guarantee about the uptime from MS to the customer)
        - Elasticity
            - Increase / decrease capacity when you need 
        - Scalability
            - Horizontal 
                - Scale out
                - Adding more servers
            - Vertical
                - Scale up
                - Adding more resource to a single server
        - Reliability
            - Time it takes to get data available while an outage occurs 
        - Predictability
            - See what you use and predict what you need
        - Security
            - Datacenter security is managed by microsoft
        - Governance
            - Azure Policies
        - Manageability
1.2 Describe the shared responsibility model
    - Customer
        - Information and data
        - Devices
        - Accounts and identities
    - On-prem
        - Customer is responsible
    - IaaS
        - Microsoft 
            - does less you do more
            - Microsoft provides Datacenter, Servers and Storage, Networking (firewall en security)
        - Customer
            - Managing the VM and installing updates etc is your responsibility
        - Infrastructure migration / lift and shift model
    - PaaS
        - Microsoft
            - Operating systems, patching etc
            - Management tools
        - Customer
            - Does not have to focus on the underlying infrastructure
            - Build the application and deploy and update
        - Example: App Services
    - SaaS
        - Microsoft
            - Manage the infrastructure and application updates and security
        - Customer
            - Specific settings and data input
        - Example: Outlook, excel powerpoint etc.
1.3 Define cloud models, including public, private, and hybrid
    - Private Cloud
        - Is like an onprem cloud, you need to manage everything yourself, like updates and hardware maintenance
        - You have to buy servers in forehand (capex)
    - Public Cloud
        - Owned by a service provider
        - Pay what you use
    - Hybrid Cloud
        - Combination of public and private cloud
        - Most flexible
    - Keep some services on prem for legacy, security or Legaly purpose
    - CapEx
        - Upfront cost
        - Reduce over time
    - OpEx
        - Spend as you need is
        - Get billed immediately
    Operational cost
1.4 Identify appropriate use cases for each cloud model
1.5 Describe the consumption-based model
    - Pay for what you actually using
1.6 Compare cloud pricing models
    - Azure account (privided by a company)
    - Azure free account
        - 12 months free
        - 52 products are free to use after 12 months
        - Need creditcard
    - Azure free student account
    - Microsoft Learn sandbox (search AZ-900 azure learn sandbox)
1.7 (Describe serverless)

### Describe the benefits of using cloud services

- Describe the benefits of high availability and scalability in the cloud
- Describe the benefits of reliability and predictability in the cloud
- Describe the benefits of security and governance in the cloud
- Describe the benefits of manageability in the cloud

### Describe cloud service types

- Describe infrastructure as a service (IaaS)
- Describe platform as a service (PaaS)
- Describe software as a service (SaaS)
- Identify appropriate use cases for each cloud service type (IaaS, PaaS, and SaaS)

## Describe Azure architecture and services (35–40%)

### Describe the core architectural components of Azure

- Describe Azure regions, region pairs, and sovereign regions
- Describe availability zones
- Describe Azure datacenters
- Describe Azure resources and resource groups
- Describe subscriptions
- Describe management groups
- Describe the hierarchy of resource groups, subscriptions, and management groups

### Describe Azure compute and networking services

- Compare compute types, including containers, virtual machines, and functions
- Describe virtual machine options, including Azure virtual machines, Azure Virtual Machine Scale Sets, availability sets, and Azure Virtual Desktop
- Describe the resources required for virtual machines
- Describe application hosting options, including web apps, containers, and virtual machines
- Describe virtual networking, including the purpose of Azure virtual networks, Azure virtual subnets, peering, Azure DNS, Azure VPN Gateway, and ExpressRoute
- [Define public and private endpoints](define-public-and-private-endpoints.md)

### [Describe Azure storage services](describe-azure-storage-services.md)

- Compare Azure Storage services
- Describe storage tiers
- Describe redundancy options
- [Describe storage account options and storage types](describe-storage-account-options-and-storage-types.md)
- Identify options for moving files, including AzCopy, Azure Storage Explorer, and Azure File Sync
- Describe migration options, including Azure Migrate and Azure Data Box

### Describe Azure identity, access, and security

- Describe directory services in Azure, including Microsoft Entra ID and Microsoft Entra Domain Services
- Describe authentication methods in Azure, including single sign-on (SSO), multi-factor authentication (MFA), and passwordless
- Describe external identities in Azure, including business-to-business (B2B) and business-to-customer (B2C)
- Describe Microsoft Entra Conditional Access
- Describe Azure role-based access control (RBAC)
- Describe the concept of Zero Trust
- Describe the purpose of the defense-in-depth model
- Describe the purpose of Microsoft Defender for Cloud

## Describe Azure management and governance (30–35%)

### Describe cost management in Azure

- Describe factors that can affect costs in Azure
- Compare the pricing calculator and the Total Cost of Ownership (TCO) Calculator
- Describe cost management capabilities in Azure
- Describe the purpose of tags

### Describe features and tools in Azure for governance and compliance

- Describe the purpose of Microsoft Purview in Azure
- Describe the purpose of Azure Policy
- Describe the purpose of resource locks

### Describe features and tools for managing and deploying Azure resources

- Describe the Azure portal
- Describe Azure Cloud Shell, including Azure Command-Line Interface (CLI) and Azure PowerShell
- Describe the purpose of Azure Arc
- Describe infrastructure as code (IaC)
- (Describe Azure Resource Manager (ARM) and ARM templates)[describe-azure-resource-manager-adnarm-templates.md]

### Describe monitoring tools in Azure

- (Describe the purpose of Azure Advisor)[describe-the-purpose-of-azure-advisor.md]
- Describe Azure Service Health
- (Describe Azure Monitor, including Log Analytics, Azure Monitor alerts, and Application Insights)[describe-the-functionality-and-usage-of-azure-monitor.md]

TODO:
- Describe the benefits and usage of Cosmos DB, Azure SQL Database, Azure Database for MySQL, Azure Database for PostgreSQL, and SQL Managed Instance
(Describe the benefits and usage of Azure Marketplace)[describe-the-benefits-and-usage-of-azure-marketplace.md]

(Describe the benefits and usage of Internet of Things (IoT) Hub, IoT Central, and Azure Sphere)[describe-the-benefits-and-usage-of-internet-of-things-hub-IoT-Central-and-szure-sphere.md]

(Benefits and Usage of Big Data and Analytics Services)[benefits-and-usage-of-big-data-and-analytics-services.md]

(Benefits and Usage of AI Services)[benefits-and-usage-of-ai-aervices.md]

(Benefits and Usage of Serverless Technologies)[benefits-and-usage-of-serverless-technologies.md]

(Describe the benefits and usage of Azure DevOps, GitHub, GitHub Actions, and Azure DevTest Labs)[benefits-and-usage-of-devops-technologies.md]

(Describe the functionality and usage of the Azure Portal, Azure PowerShell, Azure CLI, Cloud Shell, and Azure Mobile App)
[functionality-of-azure-management-solutions.md]