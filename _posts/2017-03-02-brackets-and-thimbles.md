---
layout: post
title: "Brackets and Thimbles"
description: ""
category:open_source
tags: [brackets, Mozilla, Thimble, Vagrant, bug, issue]
---
{% include JB/setup %}

So as part of preparing for my first bug fix for my open source course, we had to install [Brackets](https://github.com/mozilla/brackets) and [Mozilla's Thimble](https://github.com/mozilla/thimble.mozilla.org).

Here's the snapshot of it working: 

![screenshot](../../../../images/brackets.png)

One reoccuring theme I've noticed with setting up Thimble is the inadvertent complexity of it. You have to clone both Brackets and Thimble (Brackets has to recursively be installed, Thimble doesn't), have them both running at the same time, have Vagrant installed, make sure they're updated correctly, etc. And often times, if you come back to work the next day, you might find Thimble not working.

I found that a lot of my time goes into debugging why Vagrant is not running correctly. I have learned that I need to be patient with the setup and maintenance, and make the most of the time I have when it is running smoothly.

I ended up choosing [Issue-1681](https://github.com/mozilla/thimble.mozilla.org/issues/1681) to work on - this is a multifaceted issue that concerns the z-index positioning of the Thimble overlay (in layman's terms: images and functions pop up when they shouldn't - particularly in fullscreen mode).
