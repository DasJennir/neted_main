+++
date = "2020-11-04"
draft = false
title = "Layer 2 OSI Model"
slug = "post-title"
tags = ["OSI","Networking"]
image = ""
share = true	# set false to hide share buttons
menu= ""		# set "main" to add this content to the main menu
author = ""
+++

![OSI Layer 2](https://images2.minutemediacdn.com/image/upload/c_fill,g_auto,h_1248,w_2220/f_auto,q_auto,w_1100/v1555347594/shape/mentalfloss/e_27.png)

The OSI model has been already explained on this website if you are not sure what this is I highly suggest you to have a look there before you start reading this article.

**Layer 2:**

Data link layer (layer 2 from the osi model) is responsible for the transport of frames between nodes (computer, laptops, servers, etc) between a network segment among the physical layer. Any errors and corruptions during the process of frames is corrected and fixed by this layer protocols therefore providing integrity and confidentiality.

**Integrity Check:**

The PDU (Protocol Data Units) of this layer is the frame. Frame Synchronization (FM) is one of the features which gives the integrity of the frames received which consists of a sequence of bits symbols that indicate to the receiver node the beginning and the end of the payload frames (email, website frontend, file received via ftp etc). With FM also comes FCS (Frame Check Sequence) that is an error-detecting code added to the frame its only purpose is for error detection not recovery.

**Hardware:**

Switches and bridges, WAP (wireless access points) are just some examples of the hardware that this layer consist of, they play a big role during the process of transportation ensuring that frames are being transmitted correctly without any corruption.

**Switches:**

Switches are devices that takes care of multiples frames being transmitted at the same time to different nodes separating and filtering each frame received individually to avoid collisions (they use the ASIC chips to make these decisions),increasing stability and reliability of a network segment, they are a better version of a Hubs which did not have this "intelligence".

**Bridges:**

Bridges are similar to switches with only some minor differences which you can check on the references that I will be listening bellow the post

**Wireless Access Point:**

Is the device that allows people to access the network using radio frequencies, it somehow acts like a hub because all frames are being transmitted though the same "air space" but they can be separated though different channel numbers which the government chooses which are allowed to be used or not.

If you would like to have a little more in depth of each subject here are some really useful resources:

- https://techdifferences.com/difference-between-bridge-and-switch.html (Differences Between Router and Switch)

- https://en.wikipedia.org/wiki/Frame_synchronization
