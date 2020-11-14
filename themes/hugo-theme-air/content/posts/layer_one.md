+++
date = "2020-10-28"
draft = false
title = "Layer 1 OSI Model"
slug = "layer-one"
tags = ["OSI","Networking"]
image = "https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fiber-optical-networking.com%2Fwp-content%2Fuploads%2F2018%2F10%2Ffiber-optic-cable-installation.jpg&f=1&nofb=1"
comments = true	# set false to hide Disqus
share = true	# set false to hide share buttons
menu= ""		# set "main" to add this content to the main menu
author = ""
+++

![Layer one Optic Cable](https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fiber-optical-networking.com%2Fwp-content%2Fuploads%2F2018%2F10%2Ffiber-optic-cable-installation.jpg&f=1&nofb=1)

The OSI model has been already explained on this website if you are not sure what this is I highly suggest you to have a look there before you start reading this article.

Layer 1 :

The physical layer is the first and lowest layer of the OSI model. It represents the hardware involved during the transport of bits (data) though a computing network. Examples of devices from the first layer are copper cables, hubs, and NICs (network interface card). We interpret these devices as the first layer because they are responsible to carry the actual "physical data" which is the electricity voltage (ethernet cable), light (fiber optic cable), radio frequency (wi-fi/wireless).

**_What about others hardwares_**

So why aren't routers and switches part of the first layer ? Good question ! the reason why rubs, cables and NICs are and the others aren't is because they don't need to do any kind of calculation or "thinking" their only task is to forward the data to the next device until they reach the desired destination !!!

So if you take this in consideration this is one of the easiest layers to interpret and understand.

**_Functionality of each device_**

**_Ethernet Hubs/Repeaters:_** (I will be interpreting repeaters and hubs as the same thing in this explanation because their points is pretty much the same)

The purpose of the hub or a repeater is to expand and emplify a network, we could compare that to a switch but they have a fair difference among each other for a comparison to be possible. First of all hubs forward all data that they received to all ethernet cables connected to it, hubs don't know what device send the data from. So imagine five ethernet cables connected together forwarding data to each other all the time without knowing which port to send to, it causes a lot of performance issues to the network as a whole. You are probably saying to yourself 'wow hubs are really useless what is the point to have one ?', well hubs are cheap and can be easily upgraded by just plugging the internet cable on it, without the need of setting up anything at all, so you have to imagine yourself as a home user, you want practice,so if you want to have more ethernet ports for your router for a lower cost at home, it is ok if you lose a little bit of performance as long as you get things done ! Well... maybe in the early 20s, nowadays with the advance of technology hubs are losing their purpose because there are switches in the market which get the job done for the same price of a hub, you may find a purpose for one of them but the more their time passes by the least amount of hubs you will find.

**_Copper cables:_**

The most well known copper cables used in computing network is the RJ-45, they are responsible to transport the electricity that will represent the bits (0 and 1) when they reach their destination. The rj-45 has a lot of categories nowadays popular known as CATs (Cat5/Cat5e/Cat6/Cat7/Cat8) the main point to know about is that the numbers essentially represents an improvement over its predecessor, which means Cat 8 carries much more data than Cat 5. Copper cables are good for short distances but what if we want to carry data let's say from one building to another ? that is when fiber optic cables comes in.

**_Fiber optic cables:_**

This kind of cables have a different purpose, it is able to provide higher bandwidth and transmit data over longer distances than copper cables but at a higher cost, these are the ones responsible to transmit data over the continents (with the help of repeaters of course). There are two kinds of fiber optics available, the Multimode and Singlemode. Singlemode is used to transmit data over longer distances without the cost of losing bandwidth but with the cost of only being able to care one signal at a time, and Multimode is able to carry multiples signals at the same time with the cost of not transporting data over such long distances as Singlemode does.

**_Data Unit:_**

The data unit name that we use to represent the data send are the Bits which is the lowest level that we can interpret and represent of data that we can possibly send. Bits are 1 and 0 they simply represent on and off or as some people prefer to say yes and no 1=ON/YES and 0=OFF/NO bits is a very complex subject if we take in consideration how we transform these two number into images, movies, video games, etc. In the future I will be creating a topic only discuss bits and how we can possible make so many things out of these two numbers.

**_*Resources:*_**

If you would like to have a little more in depth of each subject here are some really useful resources:

- Hubs: https://www.lifewire.com/ethernet-and-network-hubs-816358

- CATs Category: http://www.meridianoutpost.com/resources/articles/cat5-rj45-wiring.php

- Fiber Cable:
  - https://www.lifewire.com/fiber-optic-cable-817874
  - https://www.techicy.com/what-are-the-two-types-of-fiber-optic-cable.html
