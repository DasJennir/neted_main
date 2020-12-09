+++
date = "2020-12-09"
draft = false
title = "Layer 6 OSI Model"
slug = "layer-six"
tags = ["OSI","Networking"]
image = "https://cdn.pixabay.com/photo/2018/06/13/15/17/network-3472956_1280.jpg"
comments = true	# set false to hide Disqus
share = true	# set false to hide share buttons
menu= ""		# set "main" to add this content to the main menu
author = ""
+++

![Main Image](https://cdn.24slides.com/presentbetter/wp-content/uploads/2019/11/presentation-styles.jpg)

**High Level Explanation:**

Layer 6 is responsible for filtering and processing data to be later displayed to the end user or processed by the node in which the data was planed to be send , without it things would get very complicated because everyone is using a different OS or browser meaning that if the data was processed exactly as it was sended from the server the user would probably get a syntax error, each browser and OS has a different way to handle data received for example if you are writing a paragraph and it has spaces, tabs or any kind of special characteristic that needs to be added, layer six will do it so then layer seven can easily take care of the rest. In the end we can interpret it as a translator between different data formats and computer systems.

**Low Level Explanation:**

Layer 6 will get the mapping (a set of instructions) distributed by the browser, OS, framework, etc that the data needs to be received and encapsulated into session protocol data units, and passed down the stack, which means that data is processed, filtered and send into stacks of data to layer 7. For example when you send a string of data like "Bye World" it will be processed by layer six as "Bye\0World" because it is adding a null-terminated string which is a standart format to handle data. It also encrypts and decrypts data, so, if you are using https instead of http it needs to decrypts all data send to you using the key that you and the server has exchanged.

**~~Hardware:~~**

This layer doesn't really have any hardware, because its only purpose is mainly presenting protocols.

**Protocols:**

All the following protocols have one main definition which is allowing data to be transferred between different kinds of computer systems.

- Lightweight Presentation Protocol

- External Data Representation (XDR)

- Network Data Representation

**Resources:**

- [Find out more about all layer mentioned above and what they specifically](https://en.wikipedia.org/wiki/Presentation_layer)

- [More about layer 6](https://osi-model.com/presentation-layer/)
