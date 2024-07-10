# How-to-configure-Network-Settings-in-Windows

## Objectives:
1.	Identify and configure network settings in Windows.
   
2. Set a static IP address, subnet mask, and default gateway.


**IP Address:** A unique identifier, assigned to every device on a network. It is a set of numbers separated by periods, such as 192.168.1.1. IP addresses identify devices on a network so they can communicate with one another. In a local network, IP addresses are typically assigned by a DHCP server or manually assigned by an administrator.

**Subnet Mask:** A subnet mask is used with an IP address to divide the IP address into two parts: the network address and the host address. The subnet mask consists of a series of 1s followed by a series of 0s. The 1s represent the network portion of the IP address, while the 0s represent the host portion.

**Default Gateway:** The IP address of the router that connects a local network to other networks, such as the internet. When a device on the local network wants to communicate with a device on another network, it sends the data to the default gateway, which then routes the data to the appropriate network.


## Objective 1-2: Identify and configure network settings in Windows
• Navigate to the search bar and type **Control Panel**, and *Open* the application.

<p align="center">
  <img src="https://github.com/KamelAdjei/Configure-Network-Settings/assets/34016698/54ab2856-da46-45c4-a57d-1032aa520d60" alt="Configuring network" />
</p>

•	Navigate to _Network and Internet_ -> _Network and Sharing Center_

<p align="center">
  <img src="https://github.com/KamelAdjei/Configure-Network-Settings/assets/34016698/613de8b3-deaf-4da0-becb-67c1db7577bf"/>
</p>
<p align="center">
  <img src="https://github.com/KamelAdjei/Configure-Network-Settings/assets/34016698/831345a7-68e4-422f-a11b-30454a2d85e9"/>
</p>

•	Click Change adapter settings.

<p align="center">
  <img src="https://github.com/KamelAdjei/Configure-Network-Settings/assets/34016698/d2ffa7e0-70f5-4e40-89f8-9526a1f5c3de"/>
</p>

•	Right-click the network adapter you want to configure and select **Properties.**
<p align="center">
  <img src="https://github.com/KamelAdjei/Configure-Network-Settings/assets/34016698/904ca46b-6f8b-4ce5-a747-71a49e74279d"/>
</p>

•	Select **Internet Protocol Version 4 (TCP/IPv4)** and click **Properties.**
<p align="center">
  <img src="https://github.com/KamelAdjei/Configure-Network-Settings/assets/34016698/16c5ace1-47f0-4df9-839e-7c6f2415e386"/>
</p>

•	Choose **Use the following IP address** and _manually_ enter the IP address.
<p align="center">
  <img src="https://github.com/KamelAdjei/Configure-Network-Settings/assets/34016698/f074b31e-c056-4e4a-9a4d-a19c67d5fedb"/>
</p>

•	For example, enter the _IP address 10.0.0.50_, along with the _subnet mask 255.0.0.0_ and the _default gateway 10.0.0.1._ Then click **OK** to save the changes.
<p align="center">
  <img src="https://github.com/KamelAdjei/Configure-Network-Settings/assets/34016698/9e2bd4cd-2785-4438-b6f2-0111b3bf5e4f"/>
</p>

•	Hooray! You made it to the end :)



