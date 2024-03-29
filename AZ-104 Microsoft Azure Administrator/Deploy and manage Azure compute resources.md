# Deploy and manage Azure compute resources (20–25%)

## Automate deployment of resources by using Azure Resource Manager (ARM) templates or Bicep files

- Interpret an Azure Resource Manager template or a Bicep file
- Modify an existing Azure Resource Manager template
- Modify an existing Bicep file
- Deploy resources by using an Azure Resource Manager template or a Bicep file
- Export a deployment as an Azure Resource Manager template or convert an Azure Resource Manager template to a Bicep file

- Provisioning
  - Don't use the portal, CLI and Powershell for Provisioning.
  - ARM JSON Templates
    - Good source is the github page from MS with the quickstart templates
    - You can export a resource from the portal with the export template option.
    - Are not very human friendly
  - Azure Bicep (translates to ARM JSON)
  - Terraform (translates to ARM JSON)
 
- Shared Responsibility
  - On-premise
  - IaaS
  - Paas
  - SaaS
    - leased responsibility
 
  - Virtual Machine sizes
      - Sizing
           - General Support 1/4 optimized
           - Compute optimized 1/2 optimized
           - Memorty opzimized 1/8 optimized
           - S variant supports Permium Storage
           - b variant is banked, uses only 20% of the CPU, you can use more if needed for a short time from banked.
           - Temp drive, or cache drives are local disks on the host of the vm. This is only voor de types with a (v) 

## Create and configure virtual machines

- Create a virtual machine
- Configure Azure Disk Encryption
- Move a virtual machine to another resource group, subscription, or region
- Manage virtual machine sizes
- Manage virtual machine disks
- Deploy virtual machines to availability zones and availability sets
  - vm runs in a rack (fault domain)
  - multible racks are miltiple fault domains
  - Availability sets spread vms over multiple failt domains witnin a datacenter.
  - Availablity zones isolate, Power, Cooling and networking
  - Availablity zones spread vms over multiple data centers witin an zone
- Deploy and configure an Azure Virtual Machine Scale Sets
    - VMSS Types are uniform of flex
    - Scaling profile:
        - VM template to use
        - Configuration (SKU etc)
        - Min and MAX count
        - Scale settings (if cpu is more thans x than) > horizontal scaling
    - Flexible ??

## Provision and manage containers in the Azure portal

- Create and manage an Azure container registry
- Provision a container by using Azure Container Instances
- Provision a container by using Azure Container Apps
- Manage sizing and scaling for containers, including Azure Container Instances and Azure Container Apps

Container registry contains the images
Docker file contains the information of how we want the image to look like. this uses an image from the registery and change is based on the rule

Conainter host
Kernel is shared
Usermode creates different sandboxes and loads the images in this container
ACI is the most basic services form Azure. this is the place you can run your image.

Kubernatis orchestrate 
Management controle > API server, ETCD, Scheduler, controlers
Create node pools
Each node is communicating to the management
each node contains different pods where the images are running
horizontal pod auto scaler, increases
KEDA 

Node level has Cluster autoscaler

Burst to ACI

## Create and configure Azure App Service

- Provision an App Service plan
- Configure scaling for an App Service plan
- Create an App Service
- Configure certificates and Transport Layer Security (TLS) for an App Service
- Map an existing custom DNS name to an App Service
- Configure backup for an App Service
- Configure networking settings for an App Service
- Configure deployment slots for an App Service

  Create a app service plan contains the apps
  Scaling properties:
  - Rules (define by yourself)
  - Elestic (auto scaling)
  
