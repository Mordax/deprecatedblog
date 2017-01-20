---
layout: post
title: "blockname"
description: ""
category: open_source
tags: [telehash, blockname, DNS, encryption, mesh, networking, decentralized, Internet]
---
{% include JB/setup %}

 I've been interested in breaking up hierarchies in the Internet for a while now. 
 
 The amount of faith we put into the judicial system to keep the Internet decentralized and free is staggering. 
 Mad respect to [EFF](https://eff.org), but everytime we have a victory (such as taking down the [Clipper Chip in the 90s](https://en.wikipedia.org/wiki/Clipper_chip)), it comes 
 back **yet again** (see: [FBI vs Apple](https://en.wikipedia.org/wiki/FBI%E2%80%93Apple_encryption_dispute)).
 
 That's not even getting into the [2013 NSA disclosures](https://projects.propublica.org/nsa-grid/), that demonstrate whatever victories we claim, there are 
 people actively (and illegally) *incentivized* to ignore them. 
 
 The Internet, in its technicality, relies heavily on DNS and root servers.

 The problem is it's heavily centralized. ICANN has run into a lot of criticism, including it's close relationship with the U.S. government. 

 There's a fascinating project that seems to try to combine Bitcoin's blockchain technology and Telehash's end-to-end mesh network into a DNS resolver that:

 * Removes Centralized authority (ICANN, root servers and registrars)
 * Makes end-to-end encryption default
 * Uses Bitcoin technology and can be adjusted

 This project is so named *[blockname](https://github.com/telehash/blockname)*

 It started back in 2014, and was updated a few weeks ago, however any last major commit was done in 2015. It's about three years old. It's written 100% in ```javascript```.

 It's currently being tested on a couple of websites, and is working on [Testnet](http://testnet.coinsecrets.org/?to=322562.000001).

 So far, there's been three issues, and none have been closed. If there are other communication mediums the (two) contributors are using, I haven't seen them just yet. There's around eleven forks but nothing interesting has yet been added by these people. Others are probably testing out the resolving chain.

 `Deinitely a project to check out.`
