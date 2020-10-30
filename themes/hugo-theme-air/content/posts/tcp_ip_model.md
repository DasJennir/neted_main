+++
date = "2020-10-30"
draft = false
title = "What is the TCP/IP model and why we are adopting that instead of the OSI"
slug = "tcp-ip-model"
tags = ["Networking","OSI","Model"]
image = ""
comments = true	# set false to hide Disqus
share = true	# set false to hide share buttons
menu= ""		# set "main" to add this content to the main menu
author = ""
+++

The TCP/IP model is just like any other computer network model invented and adopted by people to abstract and represent the "steps" in which the data that we send and receive though a computer network the most known being the internet.

This model was created by IETF RFC 1122, Internet STD 3 (1989) (I will be providing link of the documentation in the end of the article) which was mostly invented for the sake of simplicity. Overtime after the creation of the first model (OSI) network engineer started to see that layer 7,6,5 could all be together in one unique and unified layer that is now represented by the application layer of the TCP/IP model.

![TCP/IP model](https://1.bp.blogspot.com/-gdZOMP_8Et4/WTkK6gAKRQI/AAAAAAAACzw/XhDjcUcKGhACYw2URSTEqty4Q7hVOs76ACLcB/s1600/Screen%2BShot%2B2017-06-08%2Bat%2B1.59.05%2BPM.png)

Some models nowadays even adobt only 3 layers like the Arpanet model, but we mostly use the TCP/IP model as refference nowadays. Layers 7,6,5 were not really the biggest concern for us network engineers or enthusiastics, only the first four layers were being mostly used. Remember that the reason why we have a model is to get a complex problem and brake it down into smaller pieces to make it as clear as possible for people to undersatnad. So the adoption of one model over the other is just because it is simplier.

Is one better than the other ? not really in the end we end up having the same thing the only difference being the amount of names that you have to memorize :p. Imagine it like a networking blueprint each person will specialize in one area like trasport and someone else into data link, in the end the model doesn't matter because the abstraction ends up being the same. Imagine a situation which a software engeenier (layer 7,6,5) would have something related to a network engeniers (layer 1,2,3,4) and vice versa,the result would be a disaster, the models are just there to abstract what decision each person will do in the end !

References:

- https://tools.ietf.org/html/rfc1122 (RFC 1122, Internet STD 3 (1989))
- https://tools.ietf.org/html/rfc871 (Arpanet Reference Model (RFC 871) )
- https://en.wikipedia.org/wiki/Internet_protocol_suite (Internet protocol suite)
