---
layout: default
title: About ircdocs.horse
---

<h1 id="logo">
	About
	<subtitle>
		ircdocs.horse
	</subtitle>
</h1>

So, why did I make ircdocs.horse, and what is it supposed to be?


## Mission Statement

ircdocs is supposed to capture what the IRC client and server protocols currently are. The goal of the different sites on ircdocs.horse is to make life simpler for implementers of IRC clients, servers, and everything inbetween.

Most importantly, ircdocs is a place where I can fuck around and hopefully build something useful to other people. It doesn't have mandates, a consistent upload schedule, or need any sort of approval from anyone except me. Judging by the feedback I've gotten so far, it's worked out pretty well.


## My Thoughts

So I've made a few sites on this domain, including this one you're on right now. Here's some rough thoughts about how they've gone and grown so far:


### [ircdocs.horse](https://ircdocs.horse/)

Initially, this site was just a place to hold my thoughts (and my irritation, annoyance and displeasure) in the [IRC specifications](https://ircdocs.horse/specs/) everyone was using day-to-day. But these days, I'm pretty happy with the sort of link-dump and history store it's become.

There are two parts of this site I want to build out further for sure: The History section, and a section that is an introduction to using IRC from both the client and the server side. Hell, the speccing side too if I can be bothered to write it up! I feel like there's still not something modern which tells people _"So, uh... here's how you can **actually** start using IRC, getting into the communities, etc,"_ and I think that'd be a good place to expand into.


### [modern.ircdocs.horse](https://modern.ircdocs.horse/)

I made the Modern docs site because I'd been writing a replacement to RFC 1459/2812 for a long while, but I hadn't been able to get it really going and off the ground. The Modern docs site represents a place where I can freely write specs not encumbered by pesky, useful things like reviews, approval between different groups, and similar.

The main goal of this site is to write and produce spec documents that describe how the IRC protocol (and related technologies) work today. That's it. The IRC client protocol, CTCP, formatting characters, the `irc(s)://` URl format, DCC. All of it, or at least as much as possible.

I feel like this has been one of the really positive parts about my work here. Especially with, for instance, the CTCP spec being submitted as an [Internet Draft](https://tools.ietf.org/html/draft-oakley-irc-ctcp-01), this is going in the right direction in my mind.


### [defs.ircdocs.horse](https://defs.ircdocs.horse/)

Lots of people are familiar with the [alien.net.au IRC definition lists](https://www.alien.net.au/irc/). Lots. They're very widely-used and referred to as the place to get numeric info.

However, they're also supremely out of date. Numerics they say aren't conflicting are, and ones they say are used aren't actually used. This was irritating to me, particularly since I wanted to refer to them for a document I was working on (that'd later become the Modern docs). So, I ended up forking them with the permission of the owner, and setup the IRC Defs site.

The goal of the defs page is to record numerics, tokens, and quite simply **useful information**. If it fits into a table and either servers or clients differ in their handling of them, then I'll try to record it there. For instance, these days along with numerics and ISUPPORT tokens, it also holds STATS characters (including conflicting, etc), EXTBANs, SNOMASKs, CTCP messages and other general client behaviour.

I'm really pleased with how this site's gone so far and the automated numeric scanner has really helped with this. I'm excited to keep moving it forward.


### [stats.ircdocs.horse](https://stats.ircdocs.horse/)

When writing Modern, I was faced with a simple question: What the fuck is actually being used out there in the real world?

Man, that's a hard question to answer. What on earth is out there and what are people actually using is... a really difficult question to answer. There's almost no real information out there that's actively useful to specification authors.

If I want to make a section about the ISUPPORT tokens that are actively used today, how do I know which ones I should mark as widely-used, universal, etc? If I'm writing a client, which IRCv3 capabilities should I expect to be in use, what sorts of example EXTBAN strings will I be parsing, etc?

I really wanted answers to these questions, so I made up that network statistics site. Basically, it scans a bunch of networks, then anonymises and throws the information onto that site. By 'anonymises', it removes the information that'd let people easily reconstruct the network list and all such as net names, specific IPs (which are exposed by individual ISUPPORT tokens), etc.

This site has been useful. But not as useful as it could be, definitely. I want to get the grabber open-sourced and allow much more flexibility when viewing the data, to let people come to their own conclusions about support out there for everything we measure. However, the information has let people come to me and ask, for instance, _"How many servers support NAMESX but not `userhost-in-names`?"_, and give them a useful answer.


<img src="img/logo-compressed.png" title="ircdocs.horse" alt="ircdocs.horse logo" class="img-block" />
