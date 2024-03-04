#Define public and private endpoints

"Public Endpoint"
- Public Endpoint are internet routable
- They contain somekind of authenticate on service, to authenticate over the internet
- Always have somekind of service firewall to filter traffic to the service
- You can also specify that access is available only trough a certain Azure service subnet by lockdown a subnet and define it as a Service Endpoint and configure it in the firewall settings of the service.

"Service": "Networking" > "Firewall and Public Endpoint"

"Private Endpoint"
- Is a IP adres in a subnet
- This IP adres represents a connection to a instance of a services, like a storage account
- Can connect to this private IP trough connected vnets, even onprem netwerks over VPN
- Requires a specific DNS setting in Azure

"Service": "Networking" > "Private endpoint" 