+++
date = "2020-11-17"
draft = false
title = "Layer 4 OSI Model"
slug = "layer-four"
tags = ["OSI","Networking"]
image = "https://cdn.pixabay.com/photo/2018/06/13/15/17/network-3472956_1280.jpg"
comments = true	# set false to hide Disqus
share = true	# set false to hide share buttons
menu= ""		# set "main" to add this content to the main menu
author = ""
+++

![Main Image](https://stemjar.b-cdn.net/wp-content/uploads/2018/04/computer-networking-basics-696x464.jpg)

**High Level Explanation:**

Transport layer is very self explanatory by itself, it will be responsible for the for the delivery of the package. Imagine that you as a person can send the letter to a address (layer three) but who actually make sure that the latter will reach the right person ? that is right the mail person (layer four). It controls and responds if the node in which the "address" is destined to is reachable and if not how to handle it (error control). And what if you send a huge component let's say a industrial machine, you can't really send it using only one package or transport that is when the "mail person" will choose which boxes to use or if it will be transported via plane, ship, truck etc (Segmentation)

**Low Level Explanation:** [reference where I have taken this paragraph](https://en.wikipedia.org/wiki/OSI_model#Layer_4:_Transport_Layer)

The transport layer controls the reliability of a given link through flow control, segmentation/desegmentation, and error control. Some protocols are state- and connection-oriented (TCP). This means that the transport layer can keep track of the segments and retransmit those that fail delivery. The transport layer also provides the acknowledgement of the successful data transmission and sends the next data if no errors occurred. The transport layer creates segments out of the message received from the application layer. Segmentation is the process of dividing a long message into smaller messages.

In other words the layer four is also the spokesperson between layer 3 and 5,6, and 7 . It will tell layer three if a package failed to be delivered and ask another one to substitute the one that hasn't reached its destination, and layers 5,6, and 7 which protocol they will be using , number of packages that they are supposed to receive and so on.

**~~Hardware:~~**

This layer doesn't really have any hardware, because its only purpose is mainly managing protocols.

**Protocols:**

The protocols used by this layer are the TCP and UDP.

TCP: is a connection-oriented protocol which will make sure that every bit send by the server is delivery to the destined node for example when you send a message or send a email to a person.

UDP: is a connection-less protocol which doesn't care all data send will be delivery or not as long as it gets send to the destined node like all steaming platform uses when a person is live streaming something.

**Resources:**

- [TCP vs UDP](https://www.privateinternetaccess.com/blog/tcp-vs-udp-understanding-the-difference/#:~:text=TCP%20is%20a%20connection%2Doriented,a%20connection%20before%20sending%20data.)

- [More about layer 4](https://en.wikipedia.org/wiki/OSI_model#Layer_4:_Transport_Layer)
