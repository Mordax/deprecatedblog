---
layout: post
title: "blockname"
description: ""
category: open source
tags: [telehash, blockname, DNS, encryption, mesh, networking, decentralized, Internet]
---
{% include JB/setup %}

 I've been interested in breaking up hierarchies in the Internet for a while now. 
 
 The amount of faith we put into the judicial system to keep the Internet decentralized and free is staggering. 
 Mad respect to [EFF](https://eff.org), but everytime we have a victory (such as taking down the [Clipper Chip in the 90s](https://en.wikipedia.org/wiki/Clipper_chip)), it comes 
 back **yet again** (see: [FBI vs Apple](https://en.wikipedia.org/wiki/FBI%E2%80%93Apple_encryption_dispute)).
 
 That's not even getting into the [2013 NSA disclosures](https://projects.propublica.org/nsa-grid/), that demonstrate whatever victories we claim, there are 
 people actively (and illegally) *incentivized* to ignore them. 
 
 The Internet follows DNS religiously. It's one of the few protocols that we can confidently say is equivalent to law online. 

 The problem is it's heavily centralized.

 There's a fascinating project that seems to try to combine Bitcoin's blockchain technology and Telehash's end-to-end mesh network into a DNS resolver that:

 * Removes Centralized authority (ICANN, root servers and registrars)
 * Makes end-to-end encryption default
 * If one path 

 This project is so named > [blockname](https://github.com/telehash/blockname)

 The project started back in 2014, and was updated a few weeks ago, however any last major commit was done in 2015. It's about three years old. It's written 100% in ```javascript```.

 It's currently being tested on a couple of websites, and is working on [Testnet](http://testnet.coinsecrets.org/?to=322562.000001).

 So far, there's been three issues, and none have been closed so far. If there are other communication mediums the (two) contributors are using, I haven't seen them just yet. There's around eleven forks but nothing interesting has yet been added by these people. Others are probably testing out the resolving chain.

 > Obviously I know what I'm doing over reading week. Which is trying to decipher the entirety of the project to the point that I'll actually have authority to comment on it.

 `Wish me luck!`


 
 
 
 
 
     What is it called?
	 blockname
    What is the project about? What problem does it solve?
	The project is an attempt to use bitcoin based architecture and telehash (a (link to mesh network 
	description) with end-to-end encryption) to create a new DNS resolver. 
	The problem it solves is eliminating any sort of centralized source that can abuse the DNS
	system.
    How old is it? When did it start?
	This project started back in 2014. It was updated half a month ago and the project is now 3 years old.
    Which websites are associated with it (e.g., does it have a separate site beyond Github?)
    What language(s) is it written in?
	It is written in JavaScript
    How many open Issues does it have?
	Currently, 3 Issues remain open. 
    How many people have contributed to the code?
	There are currently two contributors to the project.
    Who is using the project? What are they doing with it?
	There's a few people who have forked the project, but none of them has added anything to it.
	The others who are using it are setting up websites to test the DNS resolving. 

Your post doesn't have to be long--a few paragraphs is enough. It should serve as a gentle introduction to the project, and include links to get someone started who wants to learn more. 
