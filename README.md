# Microsoft-Azure-Exams-Tips

This list is composed taking twitter posts with study tips from [@tectrainertim](https://twitter.com/techtrainertim) and adding links from docs.com on the specific tip.
Thanks @tectrainertim for these posts, they are very useful studying for the AZ certifications.

If you find a link being outdated or another link that would be better suited, please feel free to do a pull request.

If you find this useful please share in any shape and let me know on twitter [@Michael_Jonsson](https://twitter.com/Michael_Jonsson)

Happy Studying.

- [AZ-100](README.md#AZ-100-links)

# AZ-100 Microsoft Azure Infrastructure and Deployment
Skills measured, look at the official link for potential updates [AZ-100](https://www.microsoft.com/en-us/learning/exam-AZ-100.aspx)

- Manage Azure subscriptions and resources (15-20%)
- Implement and manage storage (20-25%)
- Deploy and manage virtual machines (VMs) (20-25%)
- Configure and manage virtual networks (20-25%)
- Manage identities (15-20%)



# Manage Azure subscriptions and resources (15-20%) 
May include but not limited to: Assign administrator permissions; configure cost center quotas and tagging; configure Azure subscription policies at Azure subscription level

## Analyze resource utilization and consumption May include but not limited to:
Configure diagnostic settings on resources; create baseline for resources; create and rest alerts; analyze alerts across subscription; analyze metrics across subscription; create action groups; monitor for unused resources; monitor spend; report on spend; utilize Log Search query functions; view alerts in Log Analytics 

## Manage resource groups
May include but not limited to: Use Azure policies for resource groups; configure resource locks; configure resource policies; implement and set tagging on resource groups; move resources across resource groups; remove resource groups 
 
# Implement and manage storage (20-25%)
Create and configure storage accounts  May include but not limited to: Configure network access to the storage account; create and configure storage account; generate shared access signature; install and use Azure Storage Explorer; manage access keys; monitor activity log by using Log Analytics; implement Azure storage replication

## Import and export data to Azure  May include but not limited to: 
Create export from Azure job; create import into Azure job; Use Azure Data Box; configure and use Azure blob storage; configure Azure content delivery network (CDN) endpoints

## Configure Azure files  
May include but not limited to: Create Azure file share; create Azure File Sync service; create Azure sync group; troubleshoot Azure File Sync 

## Implement Azure backup
May include but not limited to: Configure and review backup reports; perform backup operation; 
create Recovery Services Vault; create and configure backup policy; perform a restore operation 
 
# Deploy and manage virtual machines (VMs) (20-25%) 
## Create and configure a VM for Windows and Linux
May include but not limited to: Configure high availability; configure monitoring, networking, storage, and virtual machine size; deploy and configure scale sets 

## Automate deployment of VMs 
May include but not limited to: Modify Azure Resource Manager (ARM) template; configure location of new VMs; configure VHD template; deploy from template; save a deployment as an ARM template; deploy Windows and Linux VMs 

## Manage Azure VM
May include but not limited to: Add data discs; add network interfaces; automate configuration management by using PowerShell Desired State Configuration (DSC) and VM Agent by using custom script extensions; manage VM sizes; move VMs from one resource group to another; redeploy VMs 

## Manage VM backups
May include but not limited to: Configure VM backup; define backup policies; implement backup policies; perform VM restore 
 
# Configure and manage virtual networks (20-25%) 
## Create connectivity between virtual networks
May include but not limited to: Create and configure VNET peering; create and configure VNET to VNET; verify virtual network connectivity; create virtual network gateway 

## Implement and manage virtual networking
May include but not limited to: Configure private and public IP addresses, network routes, network interface, subnets, and virtual network 

## Configure name resolution
May include but not limited to: Configure Azure DNS; configure custom DNS settings; configure private and public DNS zones 

## Create and configure a Network Security Group (NSG)  
May include but not limited to: Create security rules; associate NSG to a subnet or network interface; identify required ports; evaluate effective security rules 

# Manage identities (15-20%) 
## Manage Azure Active Directory (AD) 
May include but not limited to: Add custom domains; configure Azure AD Identity Protection, Azure AD Join, and Enterprise State Roaming; configure self-service password reset; implement conditional access policies; manage multiple directories; perform an access review 
 
## Manage Azure AD objects (users, groups, and devices)
May include but not limited to: Create users and groups; manage user and group properties; manage device settings; perform bulk user updates 

## Implement and manage hybrid identities
May include but not limited to: Install and configure Azure AD Connect; configure federation and single sign-on; manage Azure AD Connect; manage password sync and writeback 



# AZ-100 Links

|AZ-100|
|------|
|[Microsoft Azure AZ-100 certification exam tip: Know the steps required to deploy Azure File Sync](https://docs.microsoft.com/en-us/azure/storage/files/storage-sync-files-deployment-guide?tabs=azure-portal)|
|Microsoft Azure AZ-100 certification exam tip: Know the steps required to deploy Azure File Sync|
|Microsoft Azure AZ-100 certification exam tip: Understand the steps required to use the Azure Import/Export service. |
|Microsoft Azure AZ-100 certification exam tip: Understand how to troubleshoot Azure Recovery Services vault deletions. |
|Microsoft Azure AZ-100 certification exam tip: Be aware of why and when Azure Storage Explorer can be useful. |
|Microsoft Azure AZ-100 certification exam tip: Know how to use VM extensions to automate post-deployment configuration management. |
|Microsoft Azure AZ-100 certification exam tip: Be able to differentiate features among the various Azure VM size categories. |
|Microsoft Azure AZ-100 certification exam tip: Understand the "gotchas" involved in moving Azure resources between resource groups and regions. |
|Microsoft Azure AZ-100 certification exam tip: Understand the "gotchas" involved in moving Azure resources between subscriptions. |
|Microsoft Azure AZ-100 certification exam tip: Be aware of Cloudyn and the other Azure tools to help you manage cost. |
|Microsoft Azure AZ-100 certification exam tip: Be aware that Azure CLI v2.0 exists  but be prepared to interpret lots of Azure PowerShell. |
|Microsoft Azure AZ-100 certification exam tip: Be able to troubleshoot NSG assignments at the NIC and vNET subnet level. |
|Microsoft Azure AZ-100 certification exam tip: Differentiate between Application Security Groups and Network Security Groups |
|Microsoft Azure AZ-100 certification exam tip: Understand when and how you register Azure resource providers. |
|Microsoft Azure AZ-100 certification exam tip: Know when and how to apply and lift resource locks in Azure. |
|Microsoft Azure AZ-100 certification exam tip: Be able to troubleshoot VM network connectivity by using Network Watcher. |
|Microsoft Azure AZ-100 certification exam tip: Be able to troubleshoot name resolution in Azure  especially when involving Azure DNS zones |
|Microsoft Azure AZ-100 objective of the day: Assign administrator permissions to Azure AD and Azure resources. |
|Microsoft Azure AZ-100 objective of the day: Configure cost center quotas and taxonomic tagging. |
|Microsoft Azure AZ-100 certification exam tip: Know how to configure Azure AD Connect  especially in a fault-tolerant manner. |
|Microsoft Azure AZ-100 objective of the day: Configure Azure policies at the subscription level. |
|Microsoft Azure AZ-100 certification exam tip: Know how to manage licenses in your Azure AD tenant. |
|Microsoft Azure AZ-100 objective of the day: Configure diagnostic settings on Azure resources. |
|Microsoft Azure AZ-100 certification exam tip: Be aware of the idfix utility and why you might use it in conjunction with Azure AD Connect. |
|Microsoft Azure AZ-100 objective of the day: Create a performance baseline for Azure resources |
|Microsoft Azure AZ-100 certification exam tip: Be sure you can interpret JSON  especially in Azure Policy and ARM templates. |
|Microsoft Azure AZ-100 objective of the day: Create and test alerts and action groups. |
|Microsoft Azure AZ-100 certification exam tip: Understand the relationship between App Service apps and Service Plans. |
|Microsoft Azure AZ-100 objective of the day: Analyze alerts across an Azure subscription. |
|Microsoft Azure AZ-100 certification exam tip: Be able to use taxonomic tags to help define cost reports in Azure. |
|Microsoft Azure AZ-100 objective of the day: Analyze metrics across an Azure subscription. |
|Microsoft Azure AZ-100 certification exam tip: Understand some of the most common examples used in Azure Policy (search the docs!). |
|Microsoft Azure AZ-100 objective of the day: Create action groups in Azure Monitor.|
|Microsoft Azure AZ-100 certification exam tip: Be able to demonstrate you know how to create and configure storage accounts in the Azure portal.|
|Microsoft Azure AZ-100 objective of the day: Monitor for unused Azure resources|
|Microsoft Azure AZ-100 certification exam tip: Know the steps to deploy and configure an Azure CDN profile and endpoint.|
|Microsoft Azure AZ-100 objective of the day: Monitor Azure spend -To this point -  don’t forget about Cloudyn!|
|Microsoft Azure AZ-100 certification exam tip: Know when creating a private zone in Azure DNS is helpful (hint: think inter-VNet name resolution).|
|Microsoft Azure AZ-100 certification exam tip: Differentiate between the Import/Export Service and Azure Data Box - I’d suggest you place more emphasis on Import/Export Service because some of the Data Box products are still in preview (only GA products are covered on tests)|
|Microsoft Azure AZ-100 objective of the day: Use Log Search query functions.|
|Microsoft Azure AZ-100 certification exam tip: Differentiate between Azure AD ID Protection (IDP) and Azure AD Privileged Identity Management (PIM).|
|Microsoft Azure AZ-100 objective of the day: View alerts in Azure Log Analytics.|
|Microsoft Azure AZ-100 objective of the day: Use Azure Policy for resource groups.|
|Microsoft Azure AZ-100 objective of the day: Configure resource locks.|
|Microsoft Azure AZ-100 objective of the day: Configure resource policies.|
|Microsoft Azure AZ-100 objective of the day: Implement and set taxonomic tagging on Azure resource groups.|
|Microsoft Azure AZ-100 objective of the day: Move resources across resource groups.|
|Microsoft Azure AZ-100 objective of the day: Remove resource groups.|
|Microsoft Azure AZ-100 certification exam tip: Be able to use taxonomic tags to help define cost reports in Azure.|
