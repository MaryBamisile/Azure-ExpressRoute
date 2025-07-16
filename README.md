# Implementation of Azure ExpressRoute

#### ExpressRoute lets you extend your on-premises networks into the Microsoft cloud over a private connection with the help of a connectivity provider.
https://learn.microsoft.com/en-us/azure/expressroute/expressroute-about-virtual-network-gateways

#### Firstly, we create Vnet and Gateway subnet.

1. Go to your Azure portal and search for Virtual Networks.

2. Fill in the parameters and also add a subnet selecting VNet Gateway as the purpose.

3. You can leave others on default value.

![image](https://github.com/user-attachments/assets/b86dd380-6d15-45fc-88e6-e9ef3b3aa550)

4. Now, we move on to create VNet Gateway. Fill appropriately as seen below, the 'Review + create'
![image](https://github.com/user-attachments/assets/f3794733-86ba-45bb-899a-c54444771373)

- Azure VPN Gateway connects your on-premises networks to Azure through Site-to-Site VPNs in a similar way that you set up and connect to a remote branch office. The connectivity is secure and uses the industry-standard protocols Internet Protocol Security (IPsec) and Internet Key Exchange (IKE).

The creation takes some time. Hence, remain calm while at it!

Next step is create the "ExpressRoute" resource

## Importart parameter to watch out for (port type):
Choosing between ExpressRoute Direct and the Service Provider model depends on the requirements of the organization. These requirements include performance requirements, budget constraints, and desired level of control over the network infrastructure. Large enterprises with high data transfer needs might opt for ExpressRoute Direct. Smaller businesses or those seeking managed services might prefer the Service Provider model.

ExpressRoute Direct provides a direct connection to Microsoft's network through dual 10-Gbps or 100-Gbps ports.

## Continuing with the demo...

In Azure portal marketplace, search for ExpressRoute and create.
![image](https://github.com/user-attachments/assets/11e0a6e8-e8d1-409d-be4f-62c077837969)

After the resource is done creating, on the overview page for service key as it will be required to reach out to your connectivity provider for provisioning.

The status of provisioning can always be checked for thesame overview page.
