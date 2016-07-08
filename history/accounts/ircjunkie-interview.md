---
layout: account
title: IRC-Junkie interview with Jarjjo Oikarinen
author: IRC-Junkie + Jarkko Oikarinen
written: April 23 2012
source: http://www.irc-junkie.org/2012-04-23/interview-with-jarkko-oikarinen-the-inventor-of-irc/
---
_This interview was performed by IRC-Junkie back in 2012. Figured I'd reproduce it here since the site isn't around any longer_

---

Today we've got something very special:

An Interview with the creator of IRC himself, Mr. Jarkko Oikarinen.

We've asked Mr. Oikarinen a few questions about his invention as well as himself - without much further ado lets get straight to the interview.

***First, please introduce yourself to our readers (even though you really shouldn't have to ;) )***

My name is Jarkko Oikarinen. I am the developer of original IRC server and client and was actively developing IRC from it's inception in summer 1988 until somewhere around 1992.

Since then I've been working in many areas in software industry, including multiuser games, software for advanced neurosurgery, medical imaging software, 3D computer graphics (which was my PhD research area), mobile applications and operating systems.

Most recently I have sort of went back to my roots and become involved in the development of a different kind of multiuser "chat", Google Hangouts.

***Out of what necessity did you invent IRC?***

In 1988 I was working as a summer intern in University of Oulu (in Finland), and I was the sysop on a BBS (bulletin board system) called OuluBox. That was one of the few BBS systems where one could connect to over both phone lines (using modem) and Internet.

I decided to improve the multiuser chat system for OuluBox and IRC was the result of that effort.

The name 'Internet Relay Chat' was definitely more ambitious than the original intention.

***How much time did it take to come up with the first versions of the protocol, daemon and client?***

The first versions took maybe 1-2 months, depending on how you count. At that time I was doing all kinds of small networked programs, games etc, parts of which was easily reusable here.

***Do you still use IRC? If so, for what and if not, why?***

I use IRC very rarely nowadays.

Main reason for not using it is simply lack of time. Also in the early times I was in fact spending more time developing IRC than using it… it's like many other things for me, I am more interested in developing new solutions than actually using them myself for very long.

***Did you ever imagine IRC would be as popular as it is now (or was)?***

Definitely not.. there were several other chat programs also at that time, but IRC's distributed design made it different from others.

The timing for IRC was perfect in that it was introduced when Internet was just about to link together all continents.

***What's your view on the development of your invention, be it technical or its use?***

It actually looks like there has not been that radical development on the chat systems during the last decade. I find that surprising given all the areas where improvements could be made.

***If you had to write the protocol today, would you do it differently now?***

Yes, of course… obvious examples are usage of proper cryptography and making of the IRC spanning tree more fault tolerant.

I would also think of scaling, so that the size of an individual IRC network could be larger than what it can be now in practise.

***IRC in the early days must've been like the Wild Wild West - how did you experience it?***

It was very exciting and unique; it felt like much smaller world, almost everyone knew everyone else, there were many happenings where IRC users met each other in real life.

I presume much of the similar atmosphere exists even now within individual IRC networks, but I have only later really understood how unique the early days of IRC were. I also had the opportunity of getting many IRC friends around the world, many of which I still keep some contact with.

***The Great Split - What role and position did you have?***

I assume you refer to the eris split. I was of the opinion that anonymous servers should not be allowed in the irc network. That opinion was based on the IRC protocol limitations; it allows anonymously attacking the irc in such a way that the discussions could be eavesdropped.

The IRC security model depended on the server administrators being reliable, and anonymous access would allow anyone to have the same access rights than the administrators.

On the other hand, I support the concept of having multiple smaller independent irc networks, there is no need to have just one big network.

***If you had to modernize IRC for it to be able to compete with all the social networks, what would you do?***

I think the key words are security (the servers should not rely on each other so much), privacy (cryptographic guarantee for conversation privacy) and multimedia (audio, video).

But I'm not sure if IRC would be the same thing after these changes… :-) 

***If you wanted to see one thing implemented in IRC, what would that be?***

It's hard to pick just one thing, but the area which I worked as one last thing (but never got to finish it) was the network of networks concept.

It would link the independent networks together but allow individual networks keep their identity and control, while simultaneously allowing users to easily browse all channels in all networks.

***What kind of influence do you still have on IRC?***

I have not been actively participating in IRC development for a long time, and am not planning to do that either; I just don't have the time.

Non-paid projects such as IRC have more people who like to tell how features should be done instead of actually completing the features themselves. It's so much more fun to design software than actually go through all implementation necessary.

Therefore the direction is truly influenced by people who actively develop the software who actually make the decisions on what they choose to implement. That is also how it should be, as far as I am concerned.

***What's your take on projects that try to unify IRC networks once again, such as the Janus interlinking service?***

I have not studied that very much, but by initial look it looks like something similar to the network of networks concept. There probably are a few different approaches, but I would try to keep the network linking loose so that the individual networks can develop their servers and add new features independently, without necessarily requiring those features to be added to all other networks.

My ideology would concentrate on providing value to users and allow them to explore the whole IRC metanetwork from their clients.

***Is the original source of the IRCd still around somewhere for folks to look at?***

I don't think the very original source is available anymore. I tried to search it a few years back, but was not able to find it anywhere on my local backup disks.

***Is RFC1459 supposed to be all inclusive or, as per your intentions, is it allowed to be extended as long as it is fully supported?***

RFC1459 was written to document the existing protocol at that time. Progress needs new features and extensions.

If some server implementations would no longer be compliant with RFC1459, I would prefer those servers to not be called IRC, unless those changes are very widely accepted in IRC community.

Progress needs to happen, so we shouldn't stick with the old designs, but fragmentation should also be avoided.

***In closing, what would you like to tell our readers?***

One thing that I would like to remind that even though social chatting over computer is much fun, don't take it too seriously so that it would jeopardise your studies, work, and/or real life social interaction.

---

A big thank you goes to Jarkko Oikarinen for taking the time to answer the questions so thoroughly!
