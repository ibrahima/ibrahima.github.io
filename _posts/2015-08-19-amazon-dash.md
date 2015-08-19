---
layout: post
title: Amazon Dash hacking
category: hacks
tags: hacks iot devices smartdevices
---

[https://medium.com/@edwardbenson/how-i-hacked-amazon-s-5-wifi-button-to-track-baby-data-794214b0bdd8](In
this Medium post), Ted Benson describes how to repurpose an Amazon
Dash button to do arbitrary tasks. Basically, the Dash button wakes up
and connects to your wifi network each time you press the button, and
his script sniffs the network for ARP packets which signal that the
Dash button has connected to the network. Really neat idea, though one
drawback is that each time you press the button your Amazon app will
bother you about finishing the setup. Hopefully firmware hacks will
allow repurposing this device completely, but in the meantime this is
a totally viable way of using the Dash button to trigger some action
that you want to perform.
