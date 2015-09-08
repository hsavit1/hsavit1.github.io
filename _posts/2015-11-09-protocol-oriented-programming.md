---
layout: post
title:  "Protocol Oriented Programming in Swift 2.0 with MVVM"
date:   2015-09-08 20:20:15
comments: true
---

Swift 2.0 opens up a programming paradigm unbeknown to objectve-c: Protocol Orientied Programming

As an example of a UITableViewController, a dataSource and a delegate each could comply to their own protocols. You can then add an Extension to each of the Protocols to create fill in your accessors/mutators with data values. This part can be done in the VM

(my own interpretation of this [post](http://natashatherobot.com/swift-2-0-protocol-oriented-mvvm/), definitely more to come on this!!


[A cool github library](https://github.com/matthewpalmer/Locksmith) 

A couple of awesome things emerge when you focus on protocols
- you can add functionality in new dimensions to existing types
- you can easily adapt a rapidly growing API
- you can decouple certain parts of your API for flexibility and testing

