+++
date = "2020-11-27"
draft = false
title = "Layer 5 OSI Model"
slug = "layer-five"
tags = ["OSI","Networking"]
image = "https://cdn.pixabay.com/photo/2018/06/13/15/17/network-3472956_1280.jpg"
comments = true	# set false to hide Disqus
share = true	# set false to hide share buttons
menu= ""		# set "main" to add this content to the main menu
author = ""
+++

![Main Image](https://www.open.edu/openlearn/ocw/pluginfile.php/1568585/mod_resource/content/0/opnl_1_786px.jpg)

**High Level Explanation:**

Layer 5 is responsible for maintaining connections and for controlling ports and session during the process of messages transfer between nodes.

**Low Level Explanation:**

The session layer has a lot of correlation with layer four for the reason that both are responsible for the integrity of the data, while layer four verifies that data was lost or not, layer five will do the hard work by establishing, managing and terminating connections to the other node using the ISO-SP, OSI session-layer protocol (X.225, ISO 8327).

**~~Hardware:~~**

This layer doesn't really have any hardware, because its only purpose is mainly managing protocols.

**Protocols:**

_You will notice that all protocols mentioned bellow do very similar functions that may clarify a little more why we use layers for computer networking as a separation method._

- ITU X.225 (ISO 8327) :

  - Also known as ISO 8327 is a connection-oriented session layer protocol in the Open Systems Interconnection (OSI) model. It does literally what we have just mentioned about layer 5, it establishes, manage and terminate communications between node. [More about this layer...](https://www.iso.org/obp/ui/#iso:std:27869:en)

- AppleTalk Data Stream Protocol (ADSP)

  - ADSP is a session-level protocol that provides symmetric, connection-oriented, full-duplex communication between two sockets on the AppleTalk internet. In addition, it handles flow-control and reliability.

- Network Basic Input/Output System (NetBIOS)

  - NetBIOS is an acronym for Network Basic Input/Output System. It provides services related to the session layer of the OSI model allowing applications on separate computers to communicate over a local area network.

- Password Authentication Protocol (PAP)

  - Password Authentication Protocol is a password-based authentication protocol used by Point to Point Protocol to validate users.

- Remote Procedure Call Protocol (RPC)
  - In distributed computing, a remote procedure call (RPC) is when a computer program causes a procedure (subroutine) to execute in a different address space (commonly on another computer on a shared network)

**Resources:**

- [Find out more about all layer mentioned above and what they specifically](https://en.wikipedia.org/wiki/Session_layer#Protocols)

- [More about layer 5](https://en.wikipedia.org/wiki/Session_layer)
