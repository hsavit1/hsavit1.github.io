---
layout: post
title:  "Method Swizzling and Associated Objects in Objective C and their Swift equivalents"
date:   2015-10-08 20:20:15
comments: true
---

2 things that objective c developers should but hardly ever utilize


#**Associated Objects**

One thing that Swift doesn't have: you can't add a property to an existing class via an extension. Objective-C has a workaround with categories. 

Here's an example: say we wanted to add a property to view controllers in a project, called `descriptionName`

#**Method Swizzling**

Method swizzling lets you swap the implementations of two methods, essentially overriding an existing method with your own while keeping the original around. This is awesome in a few situations - unit testing and working around compiler bugs comes to mind. 

There are a few rules to method swizzling that you should know in swift: 
1. do it in `initialize` methods. Make sure you wrap it inside a `dispatch_once` and check it at execution time for type safety reasons 
2. do it in the `appDelegate` in the `application(_:didFinishLaunchingWithOptions:)` method. This is probably the easiest way to do it
3. don't do it in `+load`. You could pull this off in objective-c, however in Swift a `load` class method is never called by the runtime
