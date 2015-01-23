---
layout: post
title:  "Encrypted blindness"
date:   2015-01-23 15:51  
---

With all the security leaks, and hacks that have been happening lately, having some kind of encryption scheme in our day-to-day communication systems is a must. Wikipedia entry on encryption defines it as:

> "The process of encoding messages or information in such a way that only authorized parties can read it". 

However, it's not always clear who these authorized parties are, specially in mobile communications, where there are many players involved.

Encryption adds a security layer to the communications that makes both the users, and the content providers feel safe(r) when sending/receiving messages. Content providers are starting to implement security protocols such as SPDY to face this problem.

On the other hand, mobile network operators (MNOs) are struggling with the soaring traffic happening in their networks. They try to find the most efficient way to deal with the data without compromising the user's experience. 

Given their limited resources, MNOs analyze the traffic and follow some QoS and policy rules that fit the network conditions and user's needs. 

![Blindness](https://gooddeedaday.files.wordpress.com/2010/02/yossi-blind-cartoon.jpg)


But right now, MNOs are facing a new problem that is making them blind: encryption.

MNOs are not able to know what kind of packages are flowing through their network, and thus cannot optimize them. When traffic is encrypted, the (blind) operator cannot perform the tasks that guarantee a better experience for the user. 

With the current encryption implementations, MNOs are not seen as an authorized party.

Keith Dyer, from The Mobile Network, did an excellent job on his [piece](http://the-mobile-network.com/2015/01/how-encryption-threatens-mobile-operators-and-what-they-can-do-about-it/ "Keith Dyer Article") on this topic. He got really good inputs from the interviews he conducted, like this one from the CTO of a major vendor:

>"There’s a tug of war right now between operators and OTT encryption. Google’s SPDY protocol is an IETF standard that is meant to provide a better service between endpoints – but it doesn’t consider the network. In the mobile network you have different needs and you need to be able optimise because of resources you have. We are working with a number of technologies to be able to keep doing that so even if the payload is encrypted the knowledge about what kind of traffic it is will be open."

Internet has become the core of mobile communications. However, it seems like it’s not the same the other way around.

More than ever, the Internet Engineering Task Force must work closer together with the 3GPP, in order to find common measures and protocols that aim to fight today’s security and capacity problems.
