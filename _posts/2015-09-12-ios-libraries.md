---
layout: post
title:  "The best iOS Libraries on Github (loooong post)"
date:   2015-09-12 19:20:15
categories: iOS UI Libraries
comments: true
---

Here I curate some notable iOS libraries. More to come!

- **[AFNetworking](https://github.com/AFNetworking/AFNetworking)**: Probably the most "starred" iOS project on Github, and for good reason. AFNetworking wraps most of the complicated NSURLSession / HTTP / Core Data into one easy to use library.
- **[ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa)**: If you haven't heard about this one, well, you're in for a serious treat. This lib makes your iOS code _Functional_ and _Reactive_. Find out more from their documentation on their github page or from their [website](http://reactivecocoa.io/)
- **[Mantle](https://github.com/Mantle/Mantle)**: A fantastic lib for creating Model objects in iOS. Normally, this requires a ton of boilerplate code. Now, it doesn't have to!
- **[GPUImage](https://github.com/BradLarson/GPUImage)**: The single best lib when it comes to editing images. 
- **[POP](https://github.com/facebook/pop)** Easily the best UI Lib ever built for iOS. Built by Facebook - it provides and alternative to working with the super obnoxious CoreAnimation and UIKitDynamics libs. Do cool spingy stuff!
- **[RESTKit](https://github.com/RestKit/RestKit)**: A fantastic library for making REST type requests in iOS with WEB services relatively painless. It provides a powerful object mapping engine that seamlessly integrates with Core Data and a simple set of networking primitives for mapping HTTP requests and responses built on top of AFNetworking. It has an elegant, carefully designed set of APIs that make accessing and modeling RESTful resources feel almost magical.
- **[MagicalRecord](https://github.com/magicalpanda/MagicalRecord)**: Inspired by Martin Fowler's ActiveRecord pattern, where data is stored in relational databases, Magical Record is a lib that simplifies all of your Core Data code. With MagicalRecord, database and object communication is made a heck of a lot easier. Which is great, because I personally get headaches wrapping my head around Core Data. Reminds me of R.O.R.'s ActiveRecord response to CRUD, using an NSFetchedResultsController
- **[Masonry](https://github.com/SnapKit/Masonry)**: You got autolayout issues? Don't like using storyboards? Hate autolyout code? (I know I do!) Use this library instead! 
- **[Objection](http://objection-framework.org/)**: Dependency Injection in objective-c made so much easier with this. A great great lib that fixes one of my least favorite parts of the ojective-c language.
- **[Typhoon](https://github.com/appsquickly/Typhoon)**: Another D.I. framework that people really really love
- **[Specta](https://github.com/specta/specta)**: A light-weight TDD / BDD framework for Objective-C & Cocoa. This makes testing your code a piece of cake
- **[Expecta](https://github.com/specta/expecta/)**: A matcher framework that works fantastically with Specta. expect(**expecta**).to.beAwesome() for testing your ReactiveCocoa code
- **[OCMock](http://ocmock.org/)**: Library for easy creation of mock objects
- **[KIF](https://github.com/kif-framework/KIF)**: Keep it functional with KIF. A great great lib for UI testing and continuous integration testing 
- **[PonyDebugger](https://github.com/square/PonyDebugger)**: Note- I added this because it looks awesome. But still testing and need to verify its awesomeness. Pretty much lets you monitor network activity with Chrome Developer Tools
- **[CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack)**: Note: see PonyDebugger. But looks easy to use and awesome. I've been using Aspects up to this point but will start looking in this direction! According to the docs, "In most cases it is an order of magnitude faster than NSLog."
- **[FLEX](https://github.com/Flipboard/FLEX)**: See PonyDebugger. FLEX looks like an ultra awesome UI debugging tool built by Flipboard. Possibly outdated? Will investigate
- **[CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket)**: Webscokets done right in iOS
- **[CanvasPod](https://github.com/CanvasPod/Canvas)**: Really cool addition to Xcode lets you animate your stuff in interface builder WITHOUT running your code! Saves a heck of a lot of time

% if page.comments %

<div id="disqus_thread"></div>
<script type="text/javascript">
    /* * * CONFIGURATION VARIABLES * * */
    // Required: on line below, replace text in quotes with your forum shortname
    var disqus_shortname = 'FORUM SHORTNAME GOES HERE';
    
    /* * * DON'T EDIT BELOW THIS LINE * * */
    (function() {
        var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
        dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
        (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript" rel="nofollow">comments powered by Disqus.</a></noscript>

% endif %
