+++
date = "2020-11-11"
draft = false
title = "Layer 3 OSI Model"
slug = "post-title"
tags = ["OSI","Networking"]
image = ""
share = true	# set false to hide share buttons
menu= ""		# set "main" to add this content to the main menu
author = ""
+++

![Network](https://storage.needpix.com/rsynced_images/network-4028019_1280.jpg)

Network layer is responsible for the actual delivery of every packages which means it will be administrating and managing how the packets will be delivered to the destined node (e.g: pc, laptop, printer, apple watch, ect) . It verifies which node has the destination IP address and also the sender IP addresses so then the deliver of the content can be done safely and without any data leak or delivering the package to a node which has not requested the communication.

**Hardware:**

As you can already imagine the hardware that plays the biggest role during the network layer process is the router, there are some switches that are smart enough already to be part of the third layer but we will be mainly focusing on router which are what we usually seems when talking about this layer.

**Router:**

Network Topologies would really be meaningless without its "backbone" the router serves as the administrator of the MAC addresses table for the local network, forward the request to the DNS server if it does not have it saved in its cache already, serves as the barrier between you and the internet (considering the fact that you don't have a firewall in front of everything) therefore protecting your privacy (most of the time) and translates your private IP address to a public one (NAT Network Address Translation) and much more.

**Protocols:**

- IP (Internet Protocol)
- ICMP (Internet Control Message Protocol)
- IPSec (Internet Protocol Security)
- IGMP (Internet Group Management Protocol)

They all are complex enough to have their own post in the future (which will happen) being the reason why I will not go in depth with them for now, but I will be providing links down bellow explaining detailed their functions. This is just a short list for you to get a certain idea of what the protocols will be mostly related to.

**Resources:**

- [Internet Protocol](https://en.wikipedia.org/wiki/Internet_Protocol)
- [Internet Protocol Security](<https://en.wikipedia.org/wiki/IPsec#:~:text=In%20computing%2C%20Internet%20Protocol%20Security,virtual%20private%20networks%20(VPNs).>)
- [Internet Control Message Protocol](https://en.wikipedia.org/wiki/Internet_Control_Message_Protocol)
- [Internet Group Management Protocol](https://en.wikipedia.org/wiki/Internet_Group_Management_Protocol#:~:text=The%20Internet%20Group%20Management%20Protocol,hosts%20that%20have%20requested%20them.)
