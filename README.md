# Implementation of Azure ExpressRoute

###### ExpressRoute lets you extend your on-premises networks into the Microsoft cloud over a private connection with the help of a connectivity provider.
https://learn.microsoft.com/en-us/azure/expressroute/expressroute-about-virtual-network-gateways

#### Firstly, we create Vnet and Gateway subnet.

1. Go to your Azure portal and search for Virtual Networks.

2. Fill in the parameters and also add a subnet selecting VNet Gateway as the purpose.

3. You can leave others on default value.

![image](https://github.com/user-attachments/assets/b86dd380-6d15-45fc-88e6-e9ef3b3aa550)

4. Now, we move on to create VNet Gateway. Fill appropriately as seen below, the 'Review + create'
![image](https://github.com/user-attachments/assets/f3794733-86ba-45bb-899a-c54444771373)

###### Azure VPN Gateway connects your on-premises networks to Azure through Site-to-Site VPNs in a similar way that you set up and connect to a remote branch office. The connectivity is secure and uses the industry-standard protocols Internet Protocol Security (IPsec) and Internet Key Exchange (IKE)
