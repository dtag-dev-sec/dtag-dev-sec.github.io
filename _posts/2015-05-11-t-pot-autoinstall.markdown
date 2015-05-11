---
layout: post
title:  "Turn your existing Ubuntu into T-Pot, automatically."
date:   2015-05-11 14:34:25
categories: mediator feature
tags: featured
image: /assets/images/docker.jpg
---


You have a spare Ubuntu system in your datacenter and want to give it a reason to live? You decided that dedicating your CPU cycles to searching for extraterrestrial life is so 1990?

*Then why don't you contribute your idle system to making the internet a little bit more secure?*

In case you already have an Ubuntu 14.04.x running in your datacenter and are unable to [install from an ISO image](http://dtag-dev-sec.github.io/mediator/feature/2015/03/17/concept.html#prebuilt), we have created a [script](https://github.com/dtag-dev-sec/t-pot-autoinstall) that converts your Ubuntu base install into a full-fledged [T-Pot](http://dtag-dev-sec.github.io/mediator/feature/2015/03/17/concept.html) within just a couple of minutes.

Just check out the script from the [repository](https://github.com/dtag-dev-sec/t-pot-autoinstall)  and run it.

In case you have limited resources, you can choose to install a “*honeypot-only*”-version, which lacks the suricata and kibana dashboard (ELK) component but runs just fine on lower equipped machines with just 1GB of RAM.





