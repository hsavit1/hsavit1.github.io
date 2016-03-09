---
layout: post
title:  "Guide to Swift"
date:   2015-11-10 17:20:15
comments: true
---

# <img src="http://www.carlosicaza.com/wp-content/uploads/2014/07/Swift-logo.png" width="36"> Awesome-Swift-Education [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/hsavit1/Awesome-Swift-Education.svg?branch=master)](https://travis-ci.org/hsavit1/Awesome-Swift-Education)

> There is no royal road to Swift. —Euclid

##### [Key](#emoji-key)

## **Index**

- [Open Source Swift](#open-source-swift)
- [Swift Style](#swift-style)
- [In-Browser Swift Editors](#in-browser-swift-editors)
- [Quick References](#quick-references)
- [Great Learning Resources](#great-learning-resources)
- [Books](#books)
- [Video](#video)
- [Swift Community](#swift-community)
- [Programming with Swift](#programming-with-swift)
    + [Closures and Functions](#closures-and-functions)
    + [Collections / Sequences / Generators](#collections--sequences--generators)
    + [Command Line and Swift Scripting](#command-line-and-swift-scripting)
    + [Control Structures](#control-structures)
    + [Concurrency](#concurrency)
    + [Data Structures and Algorithms](#data-structures-and-algorithms)
    + [Date Programming](#date-programming)
    + [Design Patterns and AntiPatterns](#design-patterns-and-antipatterns)
    + [Development Paradigms](#development-paradigms)
    + [Enums and Pattern Matching](#enums-and-pattern-matching)
    + [Error Handling](#error-handling)
    + [Extensions](#extensions)
    + [File IO](#file-io)
    + [Functional Programming, Category and Type Theory](#functional-programming-category-and-type-theory)
    + [Functional Reactive Programming in Swift](#functional-reactive-programming-in-swift)
    + [Generics](#generics)
    + [Initializers, Properties, and Dependency Injection](#initializers-properties-and-dependency-injection)
    + [Interpolability](#interpolability-with-c-and-objective-c)
    + [Internals](#internals)
    + [Language Comparisons and Transitioning to Swift](#language-comparisons-and-transitioning-to-swift)
    + [Linux Development](#linux-development)
    + [Optionals and Types](#optionals-and-types)
    + [Problem Solving with Swift](#problem-solving-with-swift)
    + [Production Swift](#production-swift)
    + [Protocols](#protocols)
    + [Protocol Oriented Programming in Swift 2](#protocol-oriented-programming-in-swift-2)
    + [Security](#security)
    + [Server Side Swift](#server-side-swift)
    + [Strings and Regular Expressions](#strings-and-regular-expressions)
    + [Swift Language FAQs](#swift-language-faqs)
    + [Testing Swift Code](#testing-swift-code)
    + [Tools](#tools)
    + [Weird Swift](#weird-swift)
- [iOS Programming with Swift](#ios-programming-with-swift)
    + [Application Structure / Architecture](#application-structure--architecture)
    + [Core Data and Realm](#core-data-and-realm)
    + [JavaScript](#javascript)
    + [UI](#ui)
    + [Web Services, JSON, Routing, REST, and Networking](#web-services-json-routing-rest-and-networking)
    + [Xcode](#xcode)
- [Mac Programming with Swift](#mac-programming-with-swift)
- [watchOS Programming with Swift](#watchos-programming-with-swift)
- [tvOS Programming with Swift](#tvos-programming-with-swift)
- [xcode](#xcode)
- [Interview Questions](#interview-questions)
- [Shoutouts](#shoutouts)

## **Open Source Swift** 
- Apple Master Github Repository [:crown:](https://github.com/apple)
- Swift Master Repository [:pencil2:](https://github.com/apple/swift)
- Download Swift [:link:](https://swift.org/download/#latest-development-snapshots)
- Core Libs Unimplemented Parts [:pencil2:](https://github.com/apple/swift-corelibs-foundation/search?utf8=%E2%9C%93&q=NSUnimplemented)
- Swift Core Libs Foundation Repository [:pencil2:](https://github.com/apple/swift-corelibs-foundation)
- Swift Core Libs Dispatch Repository [:pencil2:](https://github.com/apple/swift-corelibs-libdispatch)
- Swift CommonMark parsing and rendering library in C [:pencil2:](https://github.com/apple/swift-cmark)
- Swift Clang Repositroy [:pencil2:](https://github.com/apple/swift-clang)
- Swift LLDB Repository [:pencil2:](https://github.com/apple/swift-lldb)
- Swift Packages [:pencil2:](https://github.com/donald-pinckney/swift-packages)
- Swift Compiler Crashes [:pencil2:](https://github.com/practicalswift/swift-compiler-crashes)

[:arrow_up:](#index)

## **Swift Style**
- No Single Swift Style [:page_facing_up:](https://jeremywsherman.com/blog/2014/10/24/no-single-swift-style/)
- Functional Swift Style Guide [:book:](https://github.com/CodaFi/functional-swift-style-guide)
- The Official Swift Language Docs [:book:](https://github.com/apple/swift/tree/master/docs)
- Swift Language Evolution [:book:](https://github.com/apple/swift-evolution) [:book:](https://github.com/apple/swift/blob/master/docs/LibraryEvolution.rst)
+ Swift Style Rules [:book:](http://ericasadun.com/2015/11/17/a-handful-of-swift-style-rules-swiftlang/)
+ SwiftLint [:book:](https://github.com/realm/SwiftLint)
+ Swift Don'ts [:book:](https://gist.github.com/erica/d91aef87e95f99c094c0)
- Swift Style [:book:](https://github.com/erica/SwiftStyle)
- Prolific Style Guide [:book:](https://github.com/prolificinteractive/swift-style-guide)

[:arrow_up:](#index)

## **In-Browser Swift Editors**
- IBM Swift Sandbox [:link:](http://swiftlang.ng.bluemix.net/?cm_mmc=developerWorks-_-dWdevcenter-_-swift-_-lp#/repl)
- SwiftStub [:link:](http://swiftstub.com/)
- Try Swift in the Browser [:link:](http://www.runswiftlang.com/learn)

[:arrow_up:](#index)

## **Quick References**
- Other Awesome Lists
    - :fire: Awesome Swift Playgrounds [:scroll:](https://github.com/uraimo/Awesome-Swift-Playgrounds)
    - :fire: Awesome iOS [:scroll:](https://github.com/vsouza/awesome-ios)
    - :fire: Awesome Swift [:scroll:](https://github.com/matteocrippa/awesome-swift)
    - :fire: Another Awesome Swift [:scroll:](https://github.com/Wolg/awesome-swift)
    + :fire: Awesome Functional Programming [:scroll:](https://github.com/xgrommx/awesome-functional-programming)
    - :fire: Awesome iOS Security [:link:](https://github.com/ashishb/osx-and-ios-security-awesome)
- Swift.org [:scroll:](https://swift.org/about/)
- Every Operator in Swift [:scroll:](http://nshipster.com/swift-operators/)
- That Thing In Swift [:scroll:](https://thatthinginswift.com/)
- SwiftDoc [:scroll:](http://swiftdoc.org/)
- iOS Cookies [:scroll:](http://www.ioscookies.com/)
- Pure Swift List [:scroll:](https://github.com/PureSwift/PureSwiftList)
- iOS Good Practices [:scroll:](https://github.com/futurice/ios-good-practices)
- Little Bites of Cocoa [:scroll:](https://littlebitesofcocoa.com/)
- Libraries used in the top 100 Apps [:scroll:](https://medium.com/ios-os-x-development/libraries-used-in-the-top-100-ios-apps-5b845ad927b7#.p76bo4ms9)
- Fucking Closure Syntax [:scroll:](http://fuckingclosuresyntax.com/)
- RAC Marbles [:scroll:](http://neilpa.me/rac-marbles/)
- Swift Knowledge Base [:scroll:](https://www.hackingwithswift.com/example-code/)
- Every Single Option and Swift Compiler Flag [:scroll:](https://gist.github.com/CodaFi/b1e0d0f37cd2890c07c5)
- Useful Swift .gitignores [:scroll:](https://github.com/github/gitignore/blob/master/Swift.gitignore)
- iOS Programming Library [:scroll:](https://developer.apple.com/library/ios/navigation/)

[:arrow_up:](#index)

## **Great Learning Resources**
- Official Swift Documentation [:pencil:](https://github.com/apple/swift/tree/master/docs) 
- Swift Education Community Repository [:pencil2:](https://github.com/swifteducation)
- iOS Swift Reference [:pencil2:](https://github.com/ricardorauber/iOS-Swift)
- Hacking With Swift [:mortar_board:](https://www.hackingwithswift.com/)
- A Better way to learn Swift [:mortar_board:](https://github.com/GoThinkster/swift/blob/master/a-better-way-to-learn-swift.mdown)
- Ray Wenderlich Tutorial Pages [:mortar_board:](http://www.raywenderlich.com/category/swift)
- Swift Education [:mortar_board:](http://swifteducation.github.io/)
- Play with Swift [:mortar_board:](http://brettbukowski.github.io/SwiftExamples/)
- CS193P: Developing iOS 8 Apps with Swift [:mortar_board:](https://itunes.apple.com/en/course/developing-ios-8-apps-swift/id961180099)
- Realm Roundup: 25 Realm Resources and Tutorials [:mortar_board:](https://realm.io/news/top-realm-resources/)
- Funcitonal Reactive Programming iOS Learning Resources [:mortar_board:](https://gist.github.com/JaviLorbada/4a7bd6129275ebefd5a6)
- Learn Core Data [:mortar_board:](http://www.learncoredata.com/)
- Udacity Swift Syntax Course [:mortar_board:](https://www.udacity.com/course/learn-swift-programming-syntax--ud902)
- Open Source iOS Apps [:pencil2:](https://github.com/dkhamsing/open-source-ios-apps)

[:arrow_up:](#index)

## **Books**
- Free Books
    - The Swift Programming Language 2.2 [:books:](https://swift.org/documentation/#the-swift-programming-language)
    - Learn Swift [:books:](http://books.aidanf.net/learn-swift)
    - Swift for Programmers [:books:](https://www.safaribooksonline.com/library/view/swifttm-for-programmers/9780134021584/)
    - iOS 9 Programming Fundamentals with Swift [:books:](http://www.apeth.com/swiftBook/index.html)
    - Swifter Tips [:books:](http://en.swifter.tips/)
- Not Free (but still awesome) Swift Books
    - Objc.io Book Series [:books:](https://www.objc.io/books/)
    - Ray Wenderlich Book Series [:books:](http://www.raywenderlich.com/store)
    - Packt Publishing Book Series [:books:](https://www.packtpub.com/tech/swift#) 
    - Apress Book Series [:books:](http://www.apress.com/swift)
    - Oreilly Book Series [:books:](http://search.oreilly.com/?q=swift&x=0&y=0)
    - Your First Swift App [:books:](https://leanpub.com/yourfirstswiftapp)
    - Teach Yourself Swift in 24 Hours, 2nd Ed [:books:](http://www.informit.com/store/swift-in-24-hours-sams-teach-yourself-9780672337659)
    
[:arrow_up:](#index)

## **Video**
+ Presentations
    + :fire: pomo.tv Presentations from all of the events [:microphone:](http://www.pomo.tv/events/) 
    + WWDC 2015 Presentations [:microphone:](https://developer.apple.com/search/?q=wwdc&type=Videos) [:pencil2:](https://developer.apple.com/sample-code/wwdc/2015/) [:pencil:](http://asciiwwdc.com/)
    - All the slides from Swift Summit London 2015 [:link:](https://speakerdeck.com/swiftsummit)
    + Some talks from Swift Summit SF 2015 [:microphone:](http://www.skilled.io/)  [:page_facing_up:](http://www.raywenderlich.com/120096/swift-summit-sf-2015-highlights) [:page_facing_up:](https://www.facebook.com/notes/austen-mcdonald/field-notes-from-swift-summit-sf-2015/10153133369935811)
    - All the Presentations from Swift Summit London [:video_camera:](https://realm.io/news/swift-summit/)
    - All Presentations from #Pragma Conference [:video_camera:](https://www.youtube.com/playlist?list=PLAVm70iJlMusekZaxufRPS4OjNOs7L7zi)
    - MobileKonf 2015 [:video_camera:]( https://www.youtube.com/channel/UCMMbKC1Jh5KirZc3rnem4kg/videos
    )
    - Functional Swift Conf 2014 [:video_camera:](https://www.youtube.com/channel/UCNFUO_7gsLBk4YTmZoSTk5g)
    - Functional Swift Conf 2015 [:video_camera:](http://2015.funswiftconf.com/)
    - CocoaConf Videos [:video_camera:](http://cocoaconf.com/videos)
    - All Presentations from 360iDev 2015 [:video_camera:](https://vimeopro.com/360conferences/360idev-2015)
    - NSSpain 2015 interviews [:video_camera:](https://www.youtube.com/playlist?list=PLKxa4AIfm4pU5xvPbQ1gaWkYXn7KANFz4)
+ Other Video
    - Cocoaheads.tv [:video_camera:](http://cocoaheads.tv/)
    - Swift Language Youtube Channel [:video_camera:](https://www.youtube.com/channel/UCml4lCH0xdl6Jm91RiPPIig)
    - Free Swift Lang Course [:video_camera:](https://www.youtube.com/playlist?list=PLxwBNxx9j4PW8bsVaXia9c20I87YEGNRu)
    - Swift tutorial Video Series [:video_camera:](https://www.youtube.com/playlist?list=PLfOZCUzRoPfKeOS_pwpiqbdviGcCOcTYb)

[:arrow_up:](#index)

## **Swift Community**
- Apps
    - Charter Swift Mailing List Client [:pencil2:](https://github.com/matthewpalmer/Charter)
- Blogs 
    - iOS at Artsy [:notebook:](https://github.com/orta/Swift-at-Artsy)
    - :raised_hands: Objc.io [:notebook:](https://www.objc.io/)
    - NSBlog with Mike Ash [:notebook:](https://www.mikeash.com/pyblog/)
    - Use Your Loaf [:notebook:](http://useyourloaf.com/blog/archives/)
    - Chris Eidhof [:notebook:](http://chris.eidhof.nl)
    - Ole Begemann [:notebook:](http://oleb.net/)
    - Alexandros Salazar [:notebook:](http://nomothetis.svbtle.com/)
    - Uramio [:notebook:](http://www.uraimo.com/archive.html)
    - Swift Weekly [:notebook:](https://github.com/vandadnp/swift-weekly)
    - Erica Sadun [:notebook:](http://ericasadun.com)
    - Appventure [:notebook:](http://appventure.me/)
    - MetalByExample.com [:notebook:](http://metalbyexample.com)
    - NSHipster [:notebook:](http://nshipster.com)
    - David Owens [:notebook:](http://owensd.io/posts/)
    - The iOS Times [:notebook:](http://theiostimes.com/)
    - Crunchy Development [:notebook:](http://alisoftware.github.io/)
    - iOS Blog [:notebook:](http://ios-blog.co.uk/)
    - iAchievedIt Blog [:notebook:](http://dev.iachieved.it/iachievedit/)
    - Coding Explorer Blog [:notebook:](http://www.codingexplorer.com/)
    - 100 Curated iOS Blogs [:link:](http://www.softwarehow.com/best-blogs-for-ios-developers/)
- Conferences
    - :fire: Awesome iOS Conferences [:pencil2:](https://github.com/Lascorbe/CocoaConferences)
    - 7 of the Best Mac & iOS Dev Conferences in 2016 [:page_facing_up:](https://dancounsell.com/articles/wwdc-guide-for-indies-2015-edition)
- Forums
    - r/swift [:link:](https://www.reddit.com/r/swift/)
    - Quora Page [:link:](https://www.quora.com/topic/Apple-Swift-programming-language)
    - Stack Overflow [:link:](http://stackoverflow.com/questions/tagged/swift)
- Jobs
    - iOS Dev Jobs [:link:](https://twitter.com/iosdevjob)
    - Swift Lang Jobs [:link:](https://twitter.com/swiftlangjobs)
    - r/SwiftJobs [:link:](https://www.reddit.com/r/SwiftJobs/)
    - LinkedIn [:link:](https://www.linkedin.com/jobs/swift-jobs)
    - Swift Jobs [:link:](https://www.natashatherobot.com/swift-jobs/)
- Meetups
    - Meetup.com Swift Meetups [:link:](http://swift.meetup.com/)
- Newsletters
    - This Week in Swift News [:newspaper:](https://swiftnews.curated.co/issues)
    - iOS Goodies [:newspaper:](http://ios-goodies.com/)
    - iOS Dev Weekly [:newspaper:](https://iosdevweekly.com/)
    - Swift Open Source Newsletter [:newspaper:](http://swiftsandbox.io/)
    - SwiftLang Website [:newspaper:](http://swiftlang.eu/)
    - Swift Weekly [:newspaper:](http://swiftweekly.com/issues)
    - Gettin' Swifty With It [:newspaper:](http://gettinswiftywithit.curated.co/)
    - Indie iOS Dev Weekly [:newspaper:](https://indieiosfocus.curated.co/)
    - Swift Dev Weekly [:newspaper:](http://swiftdevweekly.co/)
    - Thomas Hanning [:newspaper:](http://www.thomashanning.com/category/swift/)
- Podcasts
    - iOhYes [:radio:](http://iohyespodcast.com/)
    - NSBrief [:radio:](http://nsbrief.com/)
    - Ray Wenderlich [:radio:](http://www.raywenderlich.com/rwpodcast)
    - CocoaConf [:radio:](http://cocoaconf.com/podcast)
    - Unicorn Podcasts [:radio:](https://swift.unicorn.tv/podcasts)
- Repositories
    - Swift @IBM Community Repo [:pencil:](https://github.com/IBM-Swift)
    - SwiftGL Repo [:pencil:](https://github.com/SwiftGL)

[:arrow_up:](#index)

## **Programming with Swift**

#### **Closures and Functions**
- @autoclosure, @noescape
    + @autoclosure, @inline, @noescape, and @noreturn Keywords [:page_facing_up:](https://github.com/vandadnp/swift-weekly/blob/master/issue11/README.md)
    + How to use @noescape [:page_facing_up:](http://stackoverflow.com/questions/28427436/noescape-attribute-in-swift-1-2)
    + How to use @autoclosure [:page_facing_up:](http://stackoverflow.com/questions/24102617/how-to-use-swift-autoclosure?rq=1)
    - How to use @autoclosure parameter in an async block [:page_facing_up:](http://stackoverflow.com/questions/30385467/how-to-use-autoclosure-parameter-in-async-block-in-swift)
- Currying
    + Swift Function Currying [:page_facing_up:](http://www.russbishop.net/swift-function-currying) [:page_facing_up:](https://www.objc.io/blog/2014/11/10/functional-snippet-6-currying/) [:page_facing_up:](https://robots.thoughtbot.com/introduction-to-function-currying-in-swift) [:page_facing_up:](http://www.drewag.me/posts/practical-use-for-curried-functions-in-swift) [:page_facing_up:](http://justtesting.org/post/94325843216/what-is-currying-in-swift)
    - Coming Changes for the Function Currying Syntax in Swift 3.0 [:link:](https://github.com/apple/swift-evolution/blob/master/proposals/0002-remove-currying.md) [:page_facing_up:](http://ericasadun.com/2015/12/18/bidding-farewell-to-currying/)
    + Instance methods are Curried Functions in Swift [:page_facing_up:](http://oleb.net/blog/2014/07/swift-instance-methods-curried-functions/)
    - Partial Function Application [:pencil:](https://gist.github.com/kristopherjohnson/4ee565cfcdf912deacf6)
    - Why is n-arity currying not possible? [:link:](http://stackoverflow.com/questions/31499375/why-is-n-arity-currying-not-possible-in-swift)
- Closures
    - Swift Closures Cheatsheet [:page_facing_up:](http://limlab.io/swift/2016/02/13/swift-closures-cheatsheet.html)
    + Closures and Capturing Values in Swift [:page_facing_up:](http://www.codingexplorer.com/closures-capturing-values-swift/) [:page_facing_up](https://medium.com/swift-programming/swift-closures-everyday-gems-part-2-of-2-8607157b11c5#.aa8k67phd)
    + Using Local Closures with Swift [:page_facing_up:](http://www.thomashanning.com/swift-using-local-closures/)
    + Delaying Code Execution through Closures [:page_facing_up:](http://blog.matthewcheok.com/delaying-code-execution-in-swift/)
    + Can we please make a standard style for closures? [:page_facing_up:](https://bigonotetaking.wordpress.com/2015/08/04/ramblings-on-stylish-closures-currying-and-operators/)
    + Closures in API Design [:microphone:](https://realm.io/news/closures-api-design/)
    - Trailing Closure Syntax [:page_facing_up:](https://www.quora.com/Apple-Swift-programming-language/What-is-a-trailing-closure) [:page_facing_up:](https://www.codefellows.org/blog/writing-completion-blocks-with-closures-in-swift) [:page_facing_up:](http://freecake.angelodipaolo.org/trailing-closures-in-swift/) [:page_facing_up:](https://developer.apple.com/library/ios/documentation/Swift/Conceptual/Swift_Programming_Language/Closures.html#//apple_ref/doc/uid/TP40014097-CH11-ID102)
    - Type inference quirks of closures as parameters [:pencil:](https://github.com/hpique/Articles/blob/master/Swift/Type%20inference%20quirks%20of%20closure%20parameters/Type%20inference%20quirks%20of%20closure%20parameters.md)
    - Style guide for functions with closure parameters in Swift [:pencil:](https://github.com/hpique/Articles/blob/master/Swift/Style%20guide%20for%20functions%20with%20closure%20parameters/Style%20guide%20for%20functions%20with%20closure%20parameters.md)
    - Using Higher Order Methods Everywhere [:page_facing_up:](https://bigonotetaking.wordpress.com/2015/08/22/using-higher-order-methods-everywhere/)
    - Swift capture lists [:page_facing_up:](http://www.russbishop.net/swift-capture-lists)
    - Variable capture by closures in Swift and inout parameters [:page_facing_up:](http://stackoverflow.com/questions/28286777/variable-capture-by-closures-in-swift-and-inout-parameters)
- Functions
    - Swift functions Cheatsheet [:page_facing_up:](http://limlab.io/swift/2016/02/12/swift-functions-cheatsheet.html)
    - Operator Overloading in Swift Tutorial [:page_facing_up:](http://www.raywenderlich.com/80818/operator-overloading-in-swift-tutorial)
    - Functions = Closures [:page_facing_up:](http://swiftwala.com/functions-equals-closures/)
- Weak References
    + weak vs unowned [:page_facing_up:](http://krakendev.io/blog/weak-and-unowned-references-in-swift)
    + Swift weak references [:page_facing_up:](https://www.mikeash.com/pyblog/friday-qa-2015-12-11-swift-weak-references.html) [:page_facing_up:](https://www.quora.com/How-does-Swift-implement-weak-references)
    + Difference between weak self vs weak self() [:page_facing_up:](http://stackoverflow.com/questions/34305439/difference-between-weak-self-vs-weak-self)
    - What is the difference between a weak reference and an unowned reference? [:page_facing_up:](http://stackoverflow.com/questions/24011575/what-is-the-difference-between-a-weak-reference-and-an-unowned-reference)

[:arrow_up:](#index)

#### **Collections**
- Arrays
    - How arrays are implemented in Swift [:page_facing_up:](http://ankit.im/swift/2016/01/08/exploring-swift-array-implementation/) [:page_facing_up:](https://www.mikeash.com/pyblog/friday-qa-2015-04-17-lets-build-swiftarray.html) [:pencil:](https://gist.github.com/mikeash/63a791f2aec3318c7c5c)
    - Let's Build a Swift.Array [:page_facing_up:](https://www.mikeash.com/pyblog/friday-qa-2015-04-17-lets-build-swiftarray.html)
    - Array Structure Reference [:page_facing_up:](https://developer.apple.com/library/tvos/documentation/Swift/Reference/Swift_Array_Structure/index.html)
    - Swift Arrays and Dictionaries [:page_facing_up:](http://www.russbishop.net/swift-arrays-and-dictionaries)
    + An Array implemented in Swift by Mike Ash [:pencil:](https://gist.github.com/mikeash/63a791f2aec3318c7c5c)
    - Storing generic objects in Swift Array [:page_facing_up:](http://stackoverflow.com/questions/26395646/storing-generic-objects-in-swift-array)
- Collections
    + Swift Collections [:page_facing_up:](https://medium.com/swift-programming/swift-collections-e5fff3cd6759#.eq2hyxhqw)
    - Collection Indices, Slices, and Generics [:page_facing_up:](http://airspeedvelocity.net/2015/12/28/collection-indices-slices-and-generics/)
    - Generic Collections, SubSequences and Overloading [:page_facing_up:](http://airspeedvelocity.net/)
    - List Comprehension in Swift [:page_facing_up:](http://stackoverflow.com/questions/24003584/list-comprehension-in-swift)
    - Swift Collection Protocols [:page_facing_up:](http://nshipster.com/swift-collection-protocols/)
    - Creating a Swift Collection [:page_facing_up:](http://jimkubicek.com/blog/2015/02/16/creating-a-swift-collection/)
    - Swift Protocols and Protocols Extensions With CollectionType [:page_facing_up:](http://stackoverflow.com/questions/30968888/swift-protocols-and-protocols-extensions-with-collectiontype)
- Dictionaries
    - Dictionaries in Swift [:page_facing_up:](http://andybargh.com/2016/01/14/dictionaries-in-swift)
- Enumeration
    - for-in secrets [:page_facing_up:](http://ericasadun.com/2016/01/15/3-simple-for-in-iteration-tricks/)
    - Replacing Ranges in an Array [:page_facing_up:](http://sketchytech.blogspot.com/2016/01/swift-replace-range-of-values-in-array.html)
- SequenceType / GeneratorType
    + A quick guide to SequenceType [:page_facing_up:](https://medium.com/swift-programming/swift-sequences-ce22d76f120c#.edaemcmqc)
    + Sequences and Generators in Swift [:page_facing_up:](http://austinzheng.com/2015/01/24/swift-seq/)
    + Experimenting with Seqs and Generators [:page_facing_up:](http://www.uraimo.com/2015/11/12/experimenting-with-swift-2-sequencetype-generatortype/)
    - Sequence Conformance [:page_facing_up:](https://bigonotetaking.wordpress.com/2015/08/20/sequence-conformance/)
    + Truly Lazy Sequences [:page_facing_up:](http://www.obqo.de/blog/2015/11/25/true-lazy-sequences/) [:page_facing_up:](http://airspeedvelocity.net/tag/lazy-evaluation/) [:page_facing_up:](http://alisoftware.github.io/swift/2016/02/28/being-lazy/)
    + The Fibonacci SequenceType [:page_facing_up:](http://bandes-stor.ch/blog/2015/08/05/the-fibonacci-sequencetype/)
    - A Little Respect for AnySequence [:page_facing_up:](http://robnapier.net/erasure)
    - Swift Sequence Lib [:pencil2:](https://github.com/oisdk/SwiftSequence)
- Sets
    + Sets vs Dictionaries in Swift [:page_facing_up:](http://ericasadun.com/2015/10/19/sets-vs-dictionaries-smackdown-in-swiftlang/)
    - A better Hashable [:page_facing_up:](http://foxinswift.com/2016/01/03/trying-to-build-a-better-hashable/)
    - SINQ - Swift Integrated Query [:pencil2:](https://github.com/slazyk/SINQ)
- Slices
    - Array and ArraySlice [:page_facing_up:](http://sketchytech.blogspot.com/2016/03/swift-array-and-arrayslice-xcode-72.html)
    - What is a slice in Swift? [:page_facing_up:](http://stackoverflow.com/questions/24073269/what-is-a-slice-in-swift)
- Subscripting 
    - Custom Subscripts in Swift [:page_facing_up:](https://www.natashatherobot.com/custom-subscripts-swift/) [:page_facing_up:](http://www.codingexplorer.com/custom-subscripts-swift/)
    - AnyObject Subscript [:link:](http://stackoverflow.com/questions/34935538/swift-anyobjects-subscript-where-did-it-come-from)

[:arrow_up:](#index)

#### **Command Line and Swift Scripting**
+ Swift Scripting [:microphone:](https://realm.io/news/swift-scripting/) [:pencil2:](https://github.com/blakemerryman/Swift-Scripts)
+ Learn Swift by running Scripts [:page_facing_up:](https://medium.com/swift-programming/1-learn-swift-by-running-scripts-73fdf8507f4b)
+ Scripting in Swift is Pretty Awesome! [:page_facing_up:](http://krakendev.io/blog/scripting-in-swift)
+ How Swift Scripting was used to make iOS Cookies [:page_facing_up:](https://medium.com/@bardonadam/how-i-m-using-swift-scripting-to-create-newsletter-for-ios-cookies-93db5deca4c#.cwgws2399)
+ Writing an Xcode Plugin with Swift [:page_facing_up:](http://merowing.info/2015/12/writing-xcode-plugin-in-swift/)
+ Make Command Line Applications with Swiftline [:page_facing_up:](https://github.com/Swiftline/Swiftline)
- Swift Command Line Application Template [:pecnil2:](https://github.com/Zewo/Swift-Command-Line-Application-Template)
- Using Swift As General Purpose Scripting Language [:page_facing_up:](http://www.strathweb.com/2014/06/using-swift-general-purpose-scripting-language/)

[:arrow_up:](#index)

#### **Concurrency**
+ Basics of GCD [:page_facing_up:](https://littlebitesofcocoa.com/85-grand-central-dispatch-basics)
+ Methods of concurrency — GCD, agents, tasks and invocations [:page_facing_up:](http://overooped.com/post/41803252527/methods-of-concurrency)
+ Code at the end of the queue [:page_facing_up:](http://blog.krzyzanowskim.com/2015/11/25/code-at-the-end-of-the-queue/)
+ Actor Model Concurrency in Swift [:pencil2:](https://github.com/tomekc/SwiftActors)
+ Coroutines in Swift [:pencil:](https://gist.github.com/mikeash/454f3ba5c2f575d63cb3)
+ STM in Swift [:pencil2:](https://github.com/f-dz-v/SwiftSTM)
+ NSOperations and NSOperationQueues [:page_facing_up:](https://medium.com/@raulriera/nsoperations-nsoperationqueue-oh-my-88b707f9ba2e#.ugnvgw9w5)
+ Threading with Closures [:page_facing_up:](https://tetontech.wordpress.com/2014/06/30/swift-nsoperationqueues-and-threading/)
+ Building Responsive and Efficient Apps with GCD [:microphone:](https://developer.apple.com/videos/play/wwdc2015-718) [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2015/718b7aw9tq/718/718_building_responsive_and_efficient_apps_with_gcd.pdf?dl=1)
- Locking in Swift [:page_facing_up:](https://www.bignerdranch.com/blog/locking-in-swift-helping-protect-me-from-myself/)
- Custom Threading Operator in Swift [:page_facing_up:](http://ijoshsmith.com/2014/07/05/custom-threading-operator-in-swift/) [:page_facing_up:](https://github.com/ijoshsmith/swift-threading)
- Back to the main thread: dispatch_get_main_queue [:page_facing_up:](https://www.hackingwithswift.com/read/9/4/back-to-the-main-thread-dispatch_get_main_queue)

[:arrow_up:](#index)

#### **Control Structures**
- Swift Break and Continue Statements [:page_facing_up:](http://andybargh.com/break-and-continue/)
- Custom Control Structures in Swift [:page_facing_up:](https://hugotunius.se/2014/08/19/custom-control-structures-in-swift.html)

[:arrow_up:](#index)

#### **Data Structures and Algorithms**
+ Evolutionary/Genetic Programming in Swift [:pencil2:](https://github.com/NachoSoto/swift-genetics) [:pencil2:](https://github.com/saniul/Mendel)
+ Naive Bayes Classifier [:pencil2:](https://github.com/fcanas/Bayes)
+ Disjoint Sets [:pencil2:](https://github.com/antitypical/DisjointSet)
+ Metaprogrammable [:pencil2:](https://github.com/antitypical/Metaprogrammable)
+ SwiftGraph [:pencil2:](https://github.com/davecom/SwiftGraph)
+ Fisher-Yates Shuffle for Swift [:pencil:](https://gist.github.com/kballard/8738524e0243a93376ed)
- Either Types micro-framework [:pencil2:](https://github.com/robrix/Either)
- Arrays
    + Contiguous Arrays in Swift [:page_facing_up:](https://bigonotetaking.wordpress.com/2015/08/09/yet-another-root-of-all-evil/)
    + NSArrays are implemente with Circular Buffers [:page_facing_up:](https://en.wikipedia.org/wiki/Circular_buffer)
    + Open sourced CFArray [:link:](http://opensource.apple.com/source/CF/CF-855.11/CFArray.c)
- Data Strucutres
    + Commonly used data structures and algorithms [:pencil2:](https://github.com/waynewbishop/SwiftStructures) [:pencil2:](https://github.com/karan/Swift-Algorithms)
- Lists 
    + Deques, Queues, and Lists in Swift with indirect [:page_facing_up:](https://bigonotetaking.wordpress.com/2015/07/29/deques-queues-and-lists-in-swift-with-indirect/) [:link:](https://github.com/oisdk/Deques-Queues-and-Lists-in-Swift-with-indirect) 
    + Linked Lists are really slow [:page_facing_up:](http://airspeedvelocity.net/2015/08/03/arrays-linked-lists-and-performance/)
    + Linked Lists, Enums, Value Types [:page_facing_up:](http://airspeedvelocity.net/2015/07/26/linked-lists-enums-value-types-and-identity/)
    + Singly Linked List [:pencil:](https://gist.github.com/airspeedswift/7e233e723e458b1eacfe) 
- Learning
    + Deep learning with Swift [:pencil2:](https://github.com/DeepLearningKit/DeepLearningKit)
    + Neural Networks in Swift [:pencil2:](https://github.com/vlall/Swift-Brain)
    + Swift AI [:pencil2:](https://github.com/collinhundley/Swift-AI)
- Math
    + Swift Matrix Math Library [:pencil2:](http://scottsievert.com/swix/) [:pencil2:](https://github.com/mattt/Surge)
    + Tensor Methods in Swift [:pencil2:](https://github.com/aleph7/Upsurge)
    + Abstract Algebraic Structures in Swift 2 [:pencil2:](https://github.com/typelift/Algebra)
    - SwiftGL Math Library [:pencil2:](https://github.com/SwiftGL/Math)
- Solutions
    - Swift Algorithm Club [:pencil2:](https://github.com/hollance/swift-algorithm-club)
    - Algorithms by CosmicMind [:pencil2:](https://github.com/CosmicMind/Algorithm#sortedmultidictionary)
    + HackerRank Solutions in Swift [:pencil2:](https://github.com/jindulys/HackerRankSolutions)
- Sorts
    - Write a Generic Stable Sort [:pencil2:](http://airspeedvelocity.net/2016/01/10/writing-a-generic-stable-sort/)
    + Sort Utils [:pencil2:](https://github.com/dsmatter/SwiftSortUtils)
- Stacks / Queues
    + SwiftPriorityQueue [:pencil2:](https://github.com/davecom/SwiftPriorityQueue)
    + Generic Stack in Swift [:pencil:](https://gist.github.com/aciidb0mb3r/fd147c8c6b1728664fdb) [:page_facing_up:](http://ankit.im/swift/2016/01/02/creating-value-type-generic-stack-in-swift-with-pointers-and-copy-on-write/)
    + Deques [:pencil2:](https://github.com/lorentey/Deque)
- Trees
    + Finger Trees in Swift [:pencil2:](https://github.com/lazytype/FingerTree/tree/master)
    + Trees [:pencil:](https://gist.github.com/CodaFi/73bd0d67c8c7dc25b9af)
    - Calkin–Wilf tree in Swift [:page_facing_up:](http://tel.github.io/posts/calkin-wilf-in-swift/)
    - In Memory BTrees [:page_facing_up:](https://github.com/lorentey/BTree)
    + Rose Tree in Swift [:pencil:](https://github.com/typelift/SwiftCheck/blob/master/SwiftCheck/Rose.swift)
    + Binary Tree [:pencil2:](https://github.com/antitypical/BinaryTree)
    + Abstract Binding Trees [:pencil:](https://gist.github.com/CodaFi/453f369a8790a070d9e2)
    + Red Black Tree [:pencil:](https://gist.github.com/airspeedswift/8fd42496679c51b34859) 
    + A persistent tree using indirect enums [:page_facing_up:](http://airspeedvelocity.net/2015/07/22/a-persistent-tree-using-indirect-enums-in-swift/)
    + Patricia/Radix trees for Swift [:pencil2:](https://github.com/haveahennessy/Patrician)
    + A Trie [:page_facing_up:](https://bigonotetaking.wordpress.com/2015/08/11/a-trie-in-swift/)

[:arrow_up:](#index)

#### **Date Programming**
- Swiftly getting a human-readable date with NSDateFormatter [:page_facing_up:](http://www.codingexplorer.com/swiftly-getting-human-readable-date-nsdateformatter/)
- Swift Date [:pencil2:](https://github.com/malcommac/SwiftDate)
- NSDateFormatter.com [:link:](https://github.com/subdigital/nsdateformatter.com)
- Date.Swift [:pencil2:](https://github.com/devxoul/Date.swift)

[:arrow_up:](#index)

#### **Design Patterns and AntiPatterns**
- AntiPatterns
    - Avoid Partial Functions [:page_facing_up:](http://cocoawithlove.com/blog/2016/01/25/partial-functions-part-one-avoidance.html) [:page_facing_up:](http://www.cocoawithlove.com/blog/2016/02/02/partial-functions-part-two-catching-precondition-failures.html)
    - Avoid 7 Swift Snares [:page_facing_up:](http://blog.davidungar.net/2016/01/02/how-to-avoid-seven-swift-snares-2/)
    - Singleton AntiPattern [:page_facing_up:](http://krakendev.io/blog/antipatterns-singletons)
- Design Patterns
    - Swift Design Patterns [:floppy_disk:](http://www.slideshare.net/micheletitolo/cocoa-design-patterns-in-swift?qid=7d2c3760-f640-49be-b204-25d086da4e78&v=qf1&b=&from_search=7) [:page_facing_up:](http://www.raywenderlich.com/86053/intermediate-design-patterns-in-swift)
    + Template Method Pattern in Swift [:page_facing_up:](http://stackoverflow.com/questions/31757514/swift-how-to-support-template-method-design-pattern-since-swift-doesnt-have)
    - Strategy Pattern in Swift [:page_facing_up:](http://jangorman.github.io/blog/2014/11/09/design-patterns-in-swift-strategy/)
    + Design Patterns Library in Swift [:page_facing_up:](https://github.com/ochococo/Design-Patterns-In-Swift)
    - Command Pattern in Swift [:page_facing_up:](http://jangorman.github.io/blog/2014/11/17/design-patterns-in-swift-command/)
    - Adapter Pattern in Swift [:page_facing_up:](http://jangorman.github.io/blog/2014/12/01/design-patterns-in-swift-adapter-pattern/)
    - Lazy Properties + Builder Pattern [:page_facing_up:](https://medium.com/ios-os-x-development/combining-swifts-lazy-properties-with-the-builder-pattern-211aabff1b40#.whauwyase)
    + Creating a Cocoa Bindings Observable Pattern in Swift [:page_facing_up:](http://colindrake.me/2015/10/01/an-observable-pattern-implementation-in-swift/)
    + Observer Pattern in Swift [:page_facing_up:](http://masteringswift.blogspot.com/2015/05/swift-and-observer-design-pattern.html)
    + The Sin of Singletons [:page_facing_up:](https://sandofsky.com/blog/singletons.html) 
    + The Null Object Pattern [:page_facing_up:](https://medium.com/swift-programming/null-object-pattern-in-swift-1b96e03b2756)
    + Segues > Delegation [:page_facing_up:](http://useyourloaf.com/blog/unwind-segues-as-an-alternative-to-delegation.html)
    + Functions as Factories [:page_facing_up:](http://cocoa.tumblr.com/post/123737170023/functions-as-factories?is_related_post=1)
    + Conform to Objective C Protocols in Swift [:page_facing_up:](http://cocoa.tumblr.com/post/128293810968/conforming-to-objective-c-protocols-with-custom?is_related_post=1)
    + Optional Protocol Methods [:page_facing_up:](http://useyourloaf.com/blog/swift-optional-protocol-methods.html)
    + The Builder Pattern and Fluent Interface [:page_facing_up:](https://github.com/vandadnp/swift-weekly/blob/master/issue05/README.md)
    + A Better NSNotificationCenter Observer Pattern [:page_facing_up:](http://blog.matthewcheok.com/a-better-nsnotificationcenter/)
    + Key Value Coding in Swift [:page_facing_up:](http://owensd.io/2015/07/14/key-value-coding-in-swift.html) [:pencil2:](https://github.com/bradhilton/SwiftKVC)
    + Exploring KVO Alternatives in Swift [:page_facing_up:](http://blog.scottlogic.com/2015/02/11/swift-kvo-alternatives.html) [:page_facing_up:](http://www.splinter.com.au/2015/07/23/swift-kvo-alternative/) [:pencil2:](https://github.com/slazyk/Observable-Swift) [:pencil2:](https://github.com/postmates/PMKVObserver) [:pencil:](https://gist.github.com/correia/001923bc420b942f9865)
    + Facade Functions [:page_facing_up:](https://tetontech.wordpress.com/2014/06/25/swift-facades-and-objects-with-collection-type-properties/)
    + Swift Singleton [:pencil2:](https://github.com/hpique/SwiftSingleton)
    + SOLID Design in Swift [:pencil2:](https://github.com/ochococo/OOD-Principles-In-Swift)
    + Decorator Pattern through composing functions in Swift [:page_facing_up:](http://railsware.com/blog/2014/06/17/composing-functions-in-swift/)
    + Target Action Pattern [:page_facing_up:](https://www.mikeash.com/pyblog/friday-qa-2015-12-25-swifty-targetaction.html)
    + Typed Notification Observers [:page_facing_up:](https://www.objc.io/blog/2015/01/19/functional-snippet-16-typed-notification-observers/)
    - Functional Notification Pattern [:page_facing_up:](http://www.jessesquires.com/functional-notifications/)
    - Calling a Swift class factory method with leading dot notation? [:link:](http://stackoverflow.com/questions/28794089/calling-a-swift-class-factory-method-with-leading-dot-notation)
    - Making Abstract Classes in Swift [:page_facing_up:](http://bartjacobs.com/how-to-create-an-abstract-class-in-swift/)
    - Allergies and Dependency Inversion [:page_facing_up:](http://www.theswiftlearner.com/2015/05/17/dependency-inversion/)
    - The Law of Demeter and the 9th Circle of Hell [:page_facing_up:](http://www.theswiftlearner.com/2015/03/05/the-law-of-demeter-and-the-9th-circle-of-hell/)

[:arrow_up:](#index)

#### **Development Paradigms**
+ Type Driven Development [:microphone:](https://vimeopro.com/user20904333/nslondon/video/121126581) [:floppy_disk:](https://speakerdeck.com/johannesweiss/type-driven-development-in-swift)
+ Result Driven Development [:floppy_disk:](https://speakerdeck.com/brianpartridge/result-driven-development)
- Library Oriented Programming [:microphone:](https://realm.io/news/justin-spahr-summers-library-oriented-programming/)
- * Oriented Programming [:microphone:](https://realm.io/news/pragma-graham-lee-oriented-programming-paradigms/)
- Hole Driven Development [:page_facing_up:](http://oleb.net/blog/2015/07/swift-type-system/)
- Entering a New Codebase [:floppy_disk:](https://speakerdeck.com/dbgrandi/how-to-understand-other-peoples-code)
- Railway Oriented Programming in Swift [:page_facing_up:](http://ulrikdamm.logdown.com/posts/247219) [:microphone:](http://fsharpforfunandprofit.com/rop/)
- Enum Oriented vs Protocol Oriented Programming [:pencil2:](https://github.com/alskipp/Swift-Diagram-Playgrounds)
- Swift in Practice [:microphone:](https://developer.apple.com/videos/play/wwdc2015-411) [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2015/4119flfsnsgmlfy/411/411_swift_in_practice.pdf?dl=1)
- Denotational Design [:floppy_disk:](http://conal.net/talks/denotational-design-lambdajam-2015.pdf)
- Building Frameworks in Swift [:page_facing_up:](https://github.com/hpique/Talks/blob/master/Building%20Swift%20frameworks/Building%20Swift%20frameworks.md)
- Object Oriented Functional Programming [:microphone:](https://realm.io/news/altconf-saul-mora-object-orientated-functional-programming/)
- Intro to Object-Oriented Design in Swift [:page_facing_up:](http://www.raywenderlich.com/81952/intro-object-oriented-design-swift-part-1) [:page_facing_up:](http://www.raywenderlich.com/81953/intro-object-oriented-design-swift-part-2)

[:arrow_up:](#index)

#### **Enums and Pattern Matching**
+ Enums
    + Enums in Swift [:link:](http://austinzheng.com/2014/12/16/swift-enums/)
    + Advanced and Practical Enum Usage in Swift [:page_facing_up:](http://appventure.me/2015/10/17/advanced-practical-enum-examples/) 
    + Enumerating Tuple Values in Swift [:page_facing_up:](http://design.featherless.software/enumerating-tuple-values-swift/)
    + Simplfied Login with Swift Enums [:page_facing_up:](https://realm.io/news/david-east-simplifying-login-swift-enums/)
    + Testing of Enums made easy [:page_facing_up:](http://www.obqo.de/blog/2015/10/31/testing-enumerations-made-easy/)
    + How to compare Enums with Equatable [:page_facing_up:](http://www.jessesquires.com/swift-enumerations-and-equatable/)
    + Raw representable enumeration [:page_facing_up:](http://blog.krzyzanowskim.com/2015/03/12/swift-raw-not-representable-enum/)
    + Enums with Associated Data vs Structs [:page_facing_up:](http://owensd.io/2015/09/13/enums-with-associated-data-vs-structs.html)
    + The Sum Types are here [:page_facing_up:](http://chadaustin.me/2015/07/sum-types/)
    + Algebraic Data Types in Swift [:page_facing_up:](http://thepurecoder.com/algebraic-data-types-in-swift/)
    + Handling Enums with Raw Values [:page_facing_up:](http://kostiakoval.github.io/posts/enum-with-raw-value/) [:floppy_disk:](https://speakerdeck.com/johannesweiss/finding-the-algebra-in-algebraic-data-types)
    + Using Enums as Constants [:page_facing_up:](http://alisoftware.github.io/swift/enum/constants/2015/07/19/enums-as-constants/)
    + Enums instead of Booleans [:page_facing_up:](https://www.objc.io/blog/2014/12/22/functional-snippet-12-enums-instead-of-booleans/)
    + Enum vs String Type [:page_facing_up:](https://www.quora.com/Why-should-I-use-enum-instead-of-string-type-data-in-programming)
    + Enum Driven View Controllers [:page_facing_up:](http://www.splinter.com.au/2016/01/03/enum-driven-viewcontrollers/)
    + Swift Enums: Initialization with Associated Values from a Server Response [:page_facing_up:](http://www.tekramer.com/swift-enums-custom-initialization-with-associated-values/)
    - Sad State of Enums [:page_facing_up:](http://owensd.io/blog/sad-state-of-enums/)
    - Swift Algebraic Data Types [:page_facing_up:](http://dduan.net/post/2015/07/swift-algebraic-data-types/)
    - Create an enum with rawvalue type of closures [:page_fcaing_up:](http://stackoverflow.com/questions/30422718/is-it-possible-to-create-a-enum-in-swift-with-raw-values-type-of-a-closure)
    - Immutable Enumeration in Swift [:page_facing_up:](http://tel.github.io/posts/immutable_enumeration_in_swift/)
    - The Types of Data in Swift [:page_facing_up:](http://tel.github.io/posts/types_of_data_in_swift/)
    - Discriminated Unions in Swift [:page_facing_up:](http://vperi.com/2014/06/06/discriminated-unions-in-swift/)
+ Pattern Matching
    + Official Docs [:pencil:](https://github.com/apple/swift/blob/master/docs/Pattern%20Matching.rst)
    + Swift's pattern-matching switch statement [:page_facing_up:](http://austinzheng.com/2014/12/16/swift-pattern-matching-switch/) [:page_facing_up:](http://andybargh.com/pattern-matching-in-swift/)
    + Custom pattern matching in Swift [:page_facing_up:](http://austinzheng.com/2014/12/17/custom-pattern-matching/)
    + Advanced Swift Pattern Matching in Detail [:page_facing_up:](http://appventure.me/2015/08/20/swift-pattern-matching-in-detail/)
    + Control Flow & Pattern Matching [:page_facing_up:](http://austinzheng.com/2015/09/23/pmatch-control-flow/)
    + Ranges and Intervals in Swift [:page_facing_up:](http://oleb.net/blog/2015/09/swift-ranges-and-intervals/)
    + More Pattern Matching Examples [:page_facing_up:](http://oleb.net/blog/2015/09/more-pattern-matching-examples/) [:page_facing_up:](https://www.objc.io/blog/2015/01/12/functional-snippet-15-combined-pattern-matching/)
    + What is a variadic parameter? [:page_facing_up:](https://www.quora.com/Apple-Swift-programming-language/What-is-a-variadic-parameter)
    + Pattern Matching in Swift [:page_facing_up:](http://oleb.net/blog/2015/09/swift-pattern-matching/)
    + Pattern Matching with an *if case* [:page_facing_up:](http://natashatherobot.com/swift-2-pattern-matching-with-if-case/)
    + Pattern Matching with Recursive Values in Swift [:page_facing_up:](http://antitypical.com/swift/2015/07/01/pattern-matching-over-recursive-values-in-swift/) [:pencil:](https://gist.github.com/robrix/4696ec3c117aac97ef0b)
    + What is value binding? [:page_facing_up:](https://www.quora.com/Apple-Swift-programming-language/What-is-value-binding)
    - The Switch Statement in Swift [:page_facing_up:](http://andybargh.com/2016/02/17/switch-statement-in-swift/)

[:arrow_up:](#index)

#### **Error Handling**
- Guard 
    + The Value of Guard [:page_facing_up:](http://www.iosinsight.com/the-value-of-guard-in-swift/) [:page_facing_up:](http://natashatherobot.com/swift-guard-better-than-if/)
    + Guard and Defer [:page_facing_up:](http://nshipster.com/guard-and-defer/)
    + Defer in Swift [:page_facing_up:](https://sideeffects.xyz/2015/defer-in-swift/)
    + When to (not) use guard [:page_facing_up:](http://radex.io/swift/guard/) [:page_facing_up:](https://medium.com/swift-programming/why-swift-guard-should-be-avoided-484cfc2603c5#.bg4hxwop2) RE [:page_facing_up:](http://owensd.io/blog/re-why-swift-guard-should-be-avoided/)
- Throw
    + Let it Throw! [:page_facing_up:](http://alisoftware.github.io/2015/12/17/let-it-throw/)
    - Throws is like an Either Type [:link:](https://twitter.com/al_skipp/status/688672127873085442)
    - Throwing vs failing vs crashing vs bool [:page_facing_up:](http://sketchytech.blogspot.com/2015/07/swift-20-throwing-vs-failing-vs.html)
    - Using Swift Throws with Completion Callbacks [:page_facing_up:](https://jeremywsherman.com/blog/2015/06/17/using-swift-throws-with-completion-callbacks/)
    - Rethrows in Swift 2 [:page_facing_up:](http://sketchytech.blogspot.com/2015/06/closures-that-throw-rethrows-in-swift-20.html) [:page_facing_up:](http://christiantietze.de/posts/2016/02/rethrows/)
- try / catch
    + try/catch with asynchronous closures [:page_facing_up:](http://appventure.me/2015/06/19/swift-try-catch-asynchronous-closures/)
    - 'do' or die [:page_facing_up:](https://harlanhaskins.com/2015/06/29/swift-and-haskell-do-or-die.html)
    - try, catch, do and throw [:page_facing_up:](https://www.hackingwithswift.com/new-syntax-swift-2-error-handling-try-catch)
- asserts
    + Using the *assert()* keyword [:page_facing_up:](http://blog.krzyzanowskim.com/2015/03/09/swift-asserts-the-missing-manual/)
- Other
    + Easy Error Handing [:page_facing_up:](https://littlebitesofcocoa.com/108-error-handling)
    + Swift 2 Error Handling [:page_facing_up:](http://austinzheng.com/2015/06/08/swift-2-control-flow/) [:page_facing_up:](https://www.bignerdranch.com/blog/swift-2-error-handling/) [:page_facing_up:](http://austinzheng.com/2015/09/23/pmatch-control-flow/) [:pencil:](https://gist.github.com/nicklockwood/21495c2015fd2dda56cf)
    + Unmanaged Type [:page_facing_up:](http://nshipster.com/unmanaged/)
    + Result: Swift type modelling the success/failure of arbitrary operations [:pencil2:](https://github.com/antitypical/Result)
    + Error Styling in Swift [:pencil:](https://gist.github.com/erica/b203a13b0b71db430801)
    + Magic Methods in Swift [:page_facing_up:](https://developer.apple.com/swift/blog/?id=15)
    - Testing Swift's ErrorType [:microphone:](https://realm.io/news/testing-swift-error-type/)
    - Async Error Handling [:page_facing_up:](http://alisoftware.github.io/swift/async/error/2016/02/06/async-errors/) [:floppy_disk:](https://speakerdeck.com/javisoto/ios-conf-singapore-october-2015)

[:arrow_up:](#index)

#### **Extensions**
- Swift Extensions [:page_facing_up:](http://www.codingexplorer.com/swift-extensions/)
+ ExSwift [:pencil2:](https://github.com/pNre/ExSwift) 
+ Useful Swift Extensions [:pencil2:](https://github.com/yingogobot/Swift-Useful-Extensions)
+ EZSwiftExtensions [:pencil2:](https://github.com/goktugyil/EZSwiftExtensions)
+ Public Extension [:notebook:](https://twitter.com/publicextension)
+ Adding Class Properties via Extension [:page_facing_up:](https://tetontech.wordpress.com/2015/11/12/adding-custom-class-properties-with-swift-extensions/)
+ Type Constrained Extensions in Swift [:page_facing_up:](http://www.cimgf.com/2015/12/14/swift-type-constrained-extensions-express-yourself/)
+ Generic type extension by retrofitting protocols in Swift 2 [:page_facing_up:](https://medium.com/swift-programming/generic-type-extension-by-retrofitting-protocols-in-swift-2-79fb0e0e2ebe#.gk9q2751q)
+ Type extensions with generic type parameters [:page_facing_up:](http://sketchytech.blogspot.com/2015/06/empowering-extensions-in-swift-2.html)
+ OptionalExtensions [:pencil2:](https://github.com/RuiAAPeres/OptionalExtensions)
- String extensions [:pencil2:](https://github.com/amayne/SwiftString)
- Swift primitive value extension [:page_facing_up:](https://hugotunius.se/2016/01/30/swift-primitive-value-extension.html)

[:arrow_up:](#index)

#### **File IO**
- Basic File Reading and Writing Using Swift [:page_facing_up:](http://peterwitham.com/swift/intermediate/basic-file-reading-and-writing-in-ios-8/)

[:arrow_up:](#index)

#### **Functional Programming, Category and Type Theory**
- Category and Type Theory
    - Key terms in Category Theory [:page_facing_up:](https://www.quora.com/What-are-the-key-terms-of-category-theory)
    - Category Theory for Programmers [:book:](http://bartoszmilewski.com/2014/10/28/category-theory-for-programmers-the-preface/)
    + Cheat Sheet For Typeclasses and Monads in Haskell [:scroll:](https://github.com/rudymatela/ultimate-cheat-sheets/releases/download/haskell-tc-v0.2/haskell-tc-ucs-0.2.pdf) [:scroll:](http://fundeps.com/tables/FromSemigroupToMonads.pdf) [:page_facing_up:](https://wiki.haskell.org/Typeclassopedia)
    + Category Theory For Beginners [:floppy_disk:](http://www.slideshare.net/kenbot/your-data-structures-are-made-of-maths?related=1) [:floppy_disk:](http://www.slideshare.net/kenbot/category-theory-for-beginners)
    + Category Theory and Progamming [:microphone:](http://yogsototh.github.io/Category-Theory-Presentation/categories.html) 
    + Awesome Math/Category Theory [:pencil:](https://github.com/rossant/awesome-math#category-theory)
    + Category Theory in Haskell [:page_facing_up:](https://en.wikibooks.org/wiki/Haskell/Category_theory)
    + The Category Design Pattern [:page_facing_up:](http://www.haskellforall.com/2012/08/the-category-design-pattern.html)
    + Type Theory vs Category Theory [:page_facing_up:](https://ncatlab.org/nlab/show/relation+between+type+theory+and+category+theory)  [:page_facing_up:](http://cs.stackexchange.com/questions/3028/is-category-theory-useful-for-learning-functional-programming/3256#3256)
    + MIT Category Theory Class [:link:](http://ocw.mit.edu/courses/mathematics/18-s996-category-theory-for-scientists-spring-2013/) 
    - Functional Programming, Abstraction, and Naming Things [:page_facing_up:](http://www.stephendiehl.com/posts/abstraction.html)
    - Most amazing def of monads [:link:](http://stackoverflow.com/questions/3870088/a-monad-is-just-a-monoid-in-the-category-of-endofunctors-whats-the-problem?rq=1)
    - Fantasy Land Specification [:pencil2:](https://github.com/fantasyland/fantasy-land)
- Functional Programming in Swift
    - Declarative Programming
        - What is Functional Programming in Swift? [:floppy_disk:](http://media.monkey-robot.com/docs/thoughtworks-swift.pdf) [:page_facing_up:](http://harlankellaway.com/blog/2015/08/10/swift-functional-programming-intro/) [:page_facing_up:](http://jamesonquave.com/blog/functional-programming-in-swift/) [:floppy_disk:](https://speakerdeck.com/saloievgen/think-functionally-in-swift) [:microphone:](https://realm.io/news/pragma-hannes-verlinde-statelessness-react-native/)
        - Make Swift More Functional [:floppy_disk:](http://www.slideshare.net/jarsen7/7-habits-for-a-more-functional-swift?qid=8a7611e7-4c08-4e2f-9f81-99b67c6f4390&v=default&b=&from_search=3)
        - Introduction to Functional Programming in Swift [:page_facing_up:](http://www.raywenderlich.com/114456/introduction-functional-programming-swift)  [:floppy_disk:](http://www.slideshare.net/alexis_gallagher/swift-functional-programming-and-the-future-of-obj-c?qid=8a7611e7-4c08-4e2f-9f81-99b67c6f4390&v=default&b=&from_search=1)
        - Functional Programming in Swift Talks [:microphone:](https://vimeo.com/107419503) [:microphone:](https://realm.io/news/altconf-chris-eidhof-functional-programming-in-swift/) [:floppy_disk:](http://www.slideshare.net/natashatherobot/funcitonal-swift-conference-the-functional-way?qid=8a7611e7-4c08-4e2f-9f81-99b67c6f4390&v=default&b=&from_search=4) [:microphone:](https://www.youtube.com/watch?v=rJosPrqBqrA) [:microphone:](https://www.youtube.com/watch?v=estNbh2TF3E)
        + Proof in Functions [:page_facing_up:](http://www.fewbutripe.com/swift/math/2015/01/06/proof-in-functions.html) [:page_facing_up:](https://www.reddit.com/r/programming/comments/2rjnou/proof_in_functions_curryhoward_explained_through/) [:page_facing_up:](https://jeremywsherman.com/blog/2015/10/02/when-is-proof-not-proof/)
        + Functional Thinking [:floppy_disk:](https://prezi.com/pgqshla_nuoe/functional-thinking/)
        + 6 Killer Functional Swift Features [:page_facing_up:](http://ericasadun.com/2015/05/21/swift-six-killer-features/)
        + Functional Programming in the Swift Language [:page_facing_up:](https://medium.com/swift-programming/2-functional-swift-c98be9533183)
        + Writing Compelling Functional Code with BananaKit [:microphone:](https://realm.io/news/compelling-code/)
        - Practical Declarative [:floppy_disk:](https://speakerdeck.com/kylef/practical-declarative-programming-360-idev-2015) and Functional [:floppy_disk:](https://speakerdeck.com/kylef/practical-functional-programming-dotswift-2015) Swift
        + 7 Habits for more functional Swift [:floppy_disk:](http://www.slideshare.net/jarsen7/7-habits-for-a-more-functional-swift) [:pencil:](https://gist.github.com/sketchytech/0ba6dfe2b197f188c64b)
        - Writing Pipe operators in Swift [:page_facing_up:](http://gilesvangruisen.com/writing-a-pipeline-operator-in-swift/) 
        - Reccomended Functional Operators in Swift [:pencil:](https://github.com/typelift/Operadics) [:page_facing_up:](http://sketchytech.blogspot.com/2015/06/functional-programming-understanding.html) [:pencil:](https://gist.github.com/sketchytech/c02adc1b68fb1080ffc3)
        - Point-Free Style Swift [:page_facing_up:](https://www.quora.com/Why-should-or-shouldnt-I-use-Swift-to-write-OS-X-or-iOS-apps-the-Functional-Programming-way)
    - Immutable State
        - Embrace Immutability [:microphone:](https://realm.io/news/slug-keith-smiley-embrace-immutability/)
        + Immutable Swift [:page_facing_up:](http://nomothetis.svbtle.com/immutable-swift)
        - Dodging State [:page_facing_up:](https://jeremywsherman.com/blog/2015/07/15/dodging-state/)
    - Map / Filter / Reduce
        - Reduce all the things [:page_facing_up:](http://appventure.me/2015/11/30/reduce-all-the-things/)
        + Map and FlatMap demystified [:page_facing_up:](http://www.uraimo.com/2015/10/08/Swift2-map-flatmap-demystified/) [:page_facing_up:](http://robnapier.net/maps)
        + Understanding Reduce in Swift [:page_facing_up:](http://ijoshsmith.com/2014/06/25/understanding-swifts-reduce-method/)
        + Deriving higher order functions in Swift [:page_facing_up:](http://ijoshsmith.com/2015/12/09/higher-order-functions-in-swift/) 
        - Reduction in Force [:page_facing_up:](http://robnapier.net/reduction-in-force)
    - Recursion and Infinite Streams
        - Does Swift implement tail call optimization? and in mutual recursion case? [:link:](http://stackoverflow.com/questions/24023580/does-swift-implement-tail-call-optimization-and-in-mutual-recursion-case) [:link:](https://devforums.apple.com/thread/247371?start=0&tstart=0)
        + Thunks in Swift [:page_facing_up:](https://plus.google.com/+ShriramKrishnamurthi/posts/dXd71hueSvH) [:page_facing_up:](https://www.reddit.com/r/swift/comments/2umog0/what_does_an_abstraction_thunk_helper_do/) [:pencil:](https://github.com/apple/swift/blob/master/test/DebugInfo/thunks.swift)
        - (Tail)Recursion with nested functions in Swift 2.0 [:page_facing_up:](http://danielnagy.hu/?p=119) [:page_facing_up:](http://natashatherobot.com/functional-swift-tail-recursion/) [:pencil:](https://gist.github.com/marcelofabri/4b41adb87a09ce86ff40)
        + Continuation Passing Style in Swift [:page_facing_up:](https://github.com/mbrandonw/mbrandonw.github.io/blob/master/_drafts/continuation-passing-in-swift.markdown) [:page_facing_up:](https://medium.com/swift-programming/continuation-passing-style-in-swift-e4d825962803#.o41p6fw4j)
        + Tying the Knot in Swift [:link:](http://stackoverflow.com/a/24026196/2855836)
        + FizzBuzz with infinite streams [:page_facing_up:](http://cutting.io/posts/completely-overengineering-fizzbuzz-with-infinite-streams/)
        + Functional Memoization in Swift [:page_facing_up:](http://blog.scottlogic.com/2014/09/22/swift-memoization.html) [:page_facing_up:](http://www.matthewsessions.com/memoize-in-swift/) [:pencil:](http://stackoverflow.com/questions/31129211/need-detailed-explanation-for-memoize-implementation-in-swift-wwdc-14-session)
        + Aquifier Functional streaming abstractions in Swift [:pencil2:](https://github.com/typelift/Aquifer) 
        + Lazy infinite streams [:pencil2:](https://github.com/antitypical/Stream)
        + Better Recursion with Swift [:microphone:](https://vimeo.com/138092644) [:floppy_disk:](https://speakerdeck.com/ontherocks/better-recursion-with-swift)
        - Memoization in Swift [:link:](http://stackoverflow.com/questions/31129211/need-detailed-explanation-for-memoize-implementation-in-swift-wwdc-14-session)
        - Does swift have a protocol for writing a stream of bytes? [:page_facing_up:](http://stackoverflow.com/questions/24184429/does-swift-have-a-protocol-for-writing-a-stream-of-bytes)
    - Lambda Calculus
        + Church Encoding [:pencil:](https://gist.github.com/CodaFi/b9ca5bcee6d7ea9ff158)
        + Lambda Calculus in Swift 2 [:pencil:](https://gist.github.com/bellbind/6ffb0add23990eb5bef4)
        - Programming is Mathematics [:page_facing_up:](http://xn--wxak1a.com/blog/FP-In-Swift-Intro.html)
        + Llama Calculus [:floppy_disk:](https://github.com/rnapier/llama-calculus)
    - Functors and Applicatives
        + Functor and Monad in Swift [:page_facing_up:](http://www.javiersoto.me/post/106875422394) [:pencil:](https://gist.github.com/harlanhaskins/dd31095330b4889a741c) [:pencil:](https://gist.github.com/mbrandonw/42651182eddf53ca3991)
        - Various Functors in Swift [:page_facing_up:](http://qiita.com/335g/items/81af12f9be8f7f8112c7)
        - Are true functors possible in Swift? [:link:](https://www.reddit.com/r/swift/comments/2d6mpo/are_functors_possible_in_swift/) [:link:](http://stackoverflow.com/questions/25233594/recreating-the-functor-type-in-swift)
        + Functors, Applicatives, and Monads in Swift [:page_facing_up:](http://www.mokacoding.com/blog/functor-applicative-monads-in-pictures/) [:link:](https://lists.swift.org/pipermail/swift-evolution/Week-of-Mon-20151214/002739.html)
        + Functional JSON Parsing [:page_facing_up:](http://chris.eidhof.nl/posts/json-parsing-in-swift.html)  [:page_facing_up:](http://radex.io/swift/json/)
        - No Real Functors [:page_facing_up:](http://nomothetis.svbtle.com/smashing-swift)
        - Functor & Friends: Protocol + Tests [:page_facing_up:](https://jeremywsherman.com/blog/2015/03/08/functors-and-friends-interface-plus-tests/)
        - How I learned to stop worrying and love the functor [:microphone:](https://vimeo.com/132657092) [:floppy_disk:](https://github.com/gfontenot/talks/tree/master/Functors)
        - The Missing Apply Function in Swift [:page_facing_up:](https://www.drivenbycode.com/the-missing-apply-function-in-swift/)
    - Arrows
        + Arrows in Swift [:pencil:](https://github.com/typelift/Swiftz/blob/master/Swiftz/Arrow.swift)
    - Monads 
        - What is a Monad? [:page_facing_up:](http://codeplease.io/2015/08/05/monads/) [:pencil:](https://gist.github.com/RuiAAPeres/0b317796f810839fe706)
        + What are Monads [:page_facing_up:](http://xn--wxak1a.com/blog/Monards.html)
        + Reader Monad in Swift [:pencil:](https://gist.github.com/tLewisII/bfee33f69ddb8e03b379) [:pencil:](https://github.com/typelift/Swiftz/blob/master/Swiftz/Reader.swift)
        + Writer Monad in Swift [:pencil:](https://gist.github.com/tLewisII/987d7c0f4ecd873b89a7) [:pencil:](https://github.com/typelift/Swiftz/blob/master/Swiftz/Writer.swift)
        + State Monads in Swift [:pencil2:](https://github.com/sharplet/State?files=1)
        + Applicatives in Swift [:pencil:](https://github.com/typelift/Swiftz/blob/master/Swiftz/Applicative.swift) [:pencil2:](https://github.com/koher/ApplicativeSwift) [:page_facing_up:](https://www.objc.io/blog/2014/11/17/functional-snippet-7-applicative-functors/)
        - Continuation Monad [:pencil:](https://gist.github.com/CodaFi/2186a73bdfb9fff79c26) [:pencil:](https://gist.github.com/robrix/dd2a65bbc8b44d7a670b) [:pencil:](https://gist.github.com/sjoerdvisscher/a56a286ccfabce40e424)
        - Monad laws [:page_facing_up:](http://nomothetis.svbtle.com/third-monad-law-derivation)
        + infix Operators for Monadic Functions in Swift [:pencil2:](https://github.com/thoughtbot/Runes)
        + Monads & C# Tasks in Swift [:page_facing_up:](https://realm.io/news/swift-tasks-nevyn-bengtsson/)
        - The monad among us [:floppy_disk:](https://speakerdeck.com/swiftsummit/al-skipp-the-monad-among-us) [:page_facing_up:](http://khanlou.com/2015/09/what-the-heck-is-a-monad/)
        + Swift Adventures in Monad Land [:pencil2:](https://github.com/alskipp/Swift-Adventures-In-Monad-Land)
        + Paragons Of Perfunctory Programs [:page_facing_up:](http://xn--wxak1a.com/blog/Monadic-Computering.html) 
        - Networking with Monads and into to Transformers [:microphone:](https://www.youtube.com/watch?v=LqwrUmuodyY)
        - "var" is the State monad [:page_facing_up:](https://twitter.com/jckarter/status/510582940158291969)
    - Monoids
        + Simple Monoid Example [:pencil:](https://gist.github.com/drexin/e3022674f6ddf6fdb65f) [:pencil:](https://gist.github.com/jhaberstro/9aa326e3762f91abbe8f)
        - Monoid Library [:pencil2:](https://github.com/alskipp/Monoid)
        - Swift's lack of Monoids [:page_facing_up:](https://www.reddit.com/r/swift/comments/2xm80a/swifts_lack_of_monads/)
        - Monoid with Dual and Writer [:pencil:](https://gist.github.com/tLewisII/c44a70a560488edea29a)
    - Folds, Zippers, and Lazy Lists
        + Array to Zipper [:pencil2:](https://github.com/rnapier/array-zipper)
        + Folds in Swift [:page_facing_up:](http://thepurecoder.com/functional-swift-fold-it-baby/) [:page_facing_up:](http://thepurecoder.com/more-on-fold/) [:pencil:](https://gist.github.com/HenningBrandt/fd9a46d5abbc3b39a35e) [:pencil:](https://gist.github.com/HenningBrandt/f44a0f59c716e7fe4689) [:pencil:](https://gist.github.com/davidpdrsn/3afcee0327285be77fbd) [:pencil:](https://gist.github.com/sonsongithub/fde90049cda3c4a2d05c) [:pencil:](https://gist.github.com/curtclifton/2ac04e88e186f52f2239)
        - Custom Zip Function [:page_facing_up:](http://flexmonkey.blogspot.com/2015/05/a-test-driven-custom-swift-zip-function.html)
        - zipWith [:pencil:](https://gist.github.com/kristopherjohnson/7419ed4444a0ad9bb2ea)
        - Lazy Haskell like Lists [:page_facing_up:](https://github.com/dankogai/swift-lazylist) [:page_facing_up:](http://matt.might.net/articles/implementing-laziness/)
        - Making flatMap lazy [:page_facing_up:](https://bigonotetaking.wordpress.com/2015/07/19/making-flatmap-lazy/)
        - How are swift lazy collections implemented [:page_facing_up:](https://medium.com/@NSomar/lazy-collection-cb4903a36ff7#.7izheiih6)
    - Promises / Futures
        - FutureKit Repostory [:pencil2:](https://github.com/FutureKit/FutureKit)
        - A simple Promise in Swift [:pencil:](https://gist.github.com/robrix/5f3dc201988fb0f5f584)
        - PromiseKit Promise Library [:pencil2:](https://github.com/mxcl/PromiseKit) [:link:](http://promisekit.org/)
        - BrightFutures Repository [:pencil2:](https://github.com/Thomvis/BrightFutures)
        + Back to the Futures with Swift [:microphone:](https://realm.io/news/swift-summit-javier-soto-futures/) [:floppy_disk:](https://speakerdeck.com/javisoto/back-to-the-futures)
        + Futures and Latency as an effect in Swift [:page_facing_up:](https://sideeffects.xyz/2015/latency-as-effect-in-swift/) [:floppy_disk:](http://www.bubblefoundry.com/blog/2014/10/future-shock/)
        - Binds and Promises with Forbind [:page_facing_up:](http://ulrikdamm.logdown.com/posts/277995) [:pencil2:](https://github.com/ulrikdamm/Forbind)
        - Futures and monads [:link:](https://lists.swift.org/pipermail/swift-evolution/Week-of-Mon-20151214/002995.html)
        - Promise + progress + pause + cancel + retry [:pencil2:](https://github.com/ReactKit/SwiftTask)
    - Combinators 
        + Y Combinators in Swift [:pencil:](https://gist.github.com/kongtomorrow/e95bea13162ca0e29d4b#file-gistfile1-swift)
        + Combinators [:page_facing_up:](http://xn--wxak1a.com/blog/Combinators.html) [:pencil:](https://gist.github.com/CodaFi/10afdd77e42bb8ad18ab)
        + Parser combinators, for Swift [:page_facing_up:](http://blog.nottoobadsoftware.com/footlessparser/) [:pencil2:](https://github.com/kareman/FootlessParser) [:pencil2:](https://github.com/hlian/jiffy) 
        - Monadic Parser Combinator [:pencil2:](https://github.com/inamiy/TryParsec)
    - Lenses, Transducers, Reducers
        + Lenses in Swift [:page_facing_up:](http://chris.eidhof.nl/posts/lenses-in-swift.html) [:pencil:](https://gist.github.com/mbrandonw/4acd26ab01bb6140af69) [:pencil2:](https://github.com/robb/Monocle/blob/master/Monocle/Lens.swift) [:pencil:](https://gist.github.com/mbrandonw/48ea2b3de9dc308907d9)
        + Lenses, Prisms, Isos in Swift 2 [:pencil2:](https://github.com/typelift/Focus)
        - Functional Programming with Bananas, Lenses, Envelopes, and Barbed Wire [:pencil:](https://gist.github.com/CodaFi/bbedc25a318a1565e4c1)
        + Transducers and Reducers in Swift 2 [:pencil2:](https://gist.github.com/rjchatfield/14e2869b0c572696ea3c) [:page_facing_up:](http://stackoverflow.com/questions/32082320/transducers-in-swift) [:link:](http://stackoverflow.com/questions/32082320/transducers-in-swift) [:link:](http://stackoverflow.com/questions/26311327/transducers-and-swift-porting-javascript-code-to-swift-code) [:pencil:](https://gist.github.com/mbrandonw/429f84f46b2818338f8e)
        - Lenses in Swift, or how to change parts of immutable objects [:page_facing_up:](http://narf.pl/posts/lenses-in-swift)
        - Lenso [:pencil2:](https://github.com/narfdotpl/lenso)
        + Covariance and Contravariance in Swift 2.1 [:page_facing_up:](http://www.uraimo.com/2015/09/29/Swift2.1-Function-Types-Conversion-Covariance-Contravariance/) [:page_facing_up:](https://mikeash.com/pyblog/friday-qa-2015-11-20-covariance-and-contravariance.html)
    - Categories
        + From Category Theory to Swift [:page_facing_up:](http://karumiblog-env.elasticbeanstalk.com/monad/) [:pencil2:](https://github.com/mbrandonw/naturally-swift)
        + Categories in Swift [:pencil:](https://gist.github.com/CodaFi/4d0ce6a3cc0cb1085720)
        - Yoneda Embedding [:pencil:](https://gist.github.com/CodaFi/d4efd98697130bd35f5c)
    - Other
        + :raised_hands: Swiftz Functional Programming Library [:pencil2:](http://www.stackbuilders.com/news/swiftz-the-power-of-liftz)
        + Second Bridge Swift Functional Framework [:pencil2:](https://github.com/47deg/second-bridge)
        + Swiftx Functional Data Types [:pencil2:](https://github.com/typelift/Swiftx)
        + Basis Pure Declarative Programming in Swift [:pencil2:](https://github.com/typelift/Basis)
        + Functional Concurrency Primitives [:pencil2:](https://github.com/typelift/Concurrent)
        + Prelude Library [:page_facing_up:](https://github.com/robrix/Prelude)
        + Funky Functional Programming Tools and Experiements [:pencil2:](https://github.com/brynbellomy/Funky)
        + Dollar.Swift Functional Toolkit like Lodash and Underscore [:pencil2:](https://github.com/ankurp/Dollar.swift)
        - SwiftLand MicroFramework [:pencil2:](https://github.com/AlexanderKaraberov/SwiftLand)

[:arrow_up:](#index)

#### **Functional Reactive Programming in Swift**
+ FRP
    - Why FRP [:page_facing_up:](http://codeplease.io/2016/01/08/why-frp/)
    - FRP in Swift 2.0 [:microphone:](https://realm.io/news/agnes-vasarhelyi-beer-app-frp-swift-2/)
    - Functional Reactive Programming in an Imperative World [:microphone:](https://realm.io/news/nacho-soto-functional-reactive-programming/)
    - FRP is a forbidden term [:page_facing_up:](https://medium.com/@andrestaltz/why-i-cannot-say-frp-but-i-just-did-d5ffaa23973b#.te52wjpxq) [:page_facing_up:](https://sideeffects.xyz/2015/the-functional-reactive-misconception/)
    - What is FRP? On StackOverflow [:page_facing_up:](http://stackoverflow.com/questions/1028250/what-is-functional-reactive-programming/1030631#1030631)
    - State, Promises, and Reactive Programming [:microphone:](https://realm.io/news/state-promises-reactive-programming/) [:pencil2:](https://github.com/ReactKit/ReactKit)
    - Functional Reactive Programming on iOS [:floppy_disk:](https://speakerdeck.com/benjamin_encz/functional-reactive-programming-on-ios)
    - Delta Library for managing state [:page_facing_up:](https://github.com/thoughtbot/Delta)
    - Functional Reactive Intuition [:page_facing_up:](http://itchingpixels.com/blog/functional-reactive-intuition-swift/)
+ MVVM
    + MVVM + FRP [:page_facing_up:](http://www.sprynthesis.com/2014/12/06/reactivecocoa-mvvm-introduction/)
    - Modern application architectures (Reactive programming, MVVM and beyond) [:page_facing_up:](https://slack-files.com/T051G5Y6D-F0HABHKDK-8e9141e191)
+ RAC
    + Introduction [:page_facing_up:](http://nomothetis.svbtle.com/an-introduction-to-reactivecocoa)
    + Reacting to Events [:page_facing_up:](http://nomothetis.svbtle.com/reactivecocoa-ii-reacting-to-signals) 
    + ReactiveCocoa 4.0 Info [:link:](https://blog.alltheflow.com/reactivecocoa-4-0-with-swift-2-0/)
    - RAC 3 with Ash Furrow [:floppy_disk:](http://www.slideshare.net/colineberhardt/reactivecocoa-and-swift-better-together?qid=8a7611e7-4c08-4e2f-9f81-99b67c6f4390&v=default&b=&from_search=10), and some other nice [:floppy_disk:](https://speakerdeck.com/romainpouclet/taking-a-peak-at-reactivecocoa-3-dot-0)
    - FRP with RAC in Swift [:floppy_disk:](https://speakerdeck.com/ashfurrow/functional-reactive-programming-in-swift)
    - MVVM + Rac 4 [:pencil2:](https://github.com/richeterre/SwiftGoal)
    - RAC Schedulers [:page_facing_up:](http://codeplease.io/2015/11/30/schedulers/)
    - RACNest: RAC + MVVM Examples [:pencil2:](https://github.com/RuiAAPeres/RACNest)
+ Rx
    + Simple RxSwift [:page_facing_up:](https://littlebitesofcocoa.com/162-reacting-with-rxswift) [:page_facing_up:](https://littlebitesofcocoa.com/163-creating-observables-with-rxswift)
    - Functional Rective Programming with RxSwift [:floppy_disk:](https://speakerdeck.com/realm/functional-reactive-programming-with-rxswift)
    + MVVM + RxSwift [:microphone:](https://realm.io/news/slug-max-alexander-functional-reactive-rxswift/) [:pencil2:](https://github.com/RxSwiftCommunity/RxViewModel), [:page_facing_up:](https://medium.com/@marinbenc/implementing-mvvm-in-ios-with-rxswift-458a2d47c33d#.k901myr5x), [:page_facing_up:](http://tailec.com/blog/reactive-recipe-2)
    - The Difference between RxSwift and ReactiveCocoa [:page_facing_up:](http://stackoverflow.com/questions/32542846/reactivecocoa-vs-rxswift-pros-and-cons) [:page_facing_up:](https://ashfurrow.com/blog/reactivecocoa-vs-rxswift/) [:page_facing_up:](https://sideeffects.xyz/2015/from-rac-to-rxswift-the-survival-guide/)
    - Learning RxSwift [:link:](https://github.com/pepaslabs/LearningRxSwift)
    - Upgrading to RxSwift [:page_facing_up:](http://artsy.github.io/blog/2015/12/08/reactive-cocoa-to-rxswift/)
    - RxSwift Community Webpage [:link:](http://community.rxswift.org/)
     - Split laps timer with RxSwift and RxCocoa [:page_facing_up:](http://rx-marin.com/post/rxswift-rxcocoa-sample-split-laps-timer/) [:page_facing_up:](http://rx-marin.com/)

[:arrow_up:](#index)

#### **Generics** 
- Covariance 
    + Covariant and contravariant generic type parameters [:link:](https://forums.developer.apple.com/thread/5056)
- Protocol Generics
    + The shortcomings of generic protocols [:page_facing_up:](http://krakendev.io/blog/generic-protocols-and-their-shortcomings)
    + Generic Protocols [:page_facing_up:](http://milen.me/writings/swift-generic-protocols/)
    - Protocol Generics Self [:pencil:](https://gist.github.com/AliSoftware/e6b931c1731f016e41fb)
+ Generic Arrays in Swift 2.0 [:page_facing_up:](http://blog.krzyzanowskim.com/2015/10/07/generic-array-uint8/)
+ Generics in Swift, Part 1 [:page_facing_up:](http://austinzheng.com/2015/01/02/swift-generics-pt-1/), Part 2 [:page_facing_up:](http://austinzheng.com/2015/09/29/swift-generics-pt-2/)
+ Official Docs [:pencil:](https://github.com/apple/swift/blob/master/docs/Generics.rst)
+ Partial Function Application with Generics [:link:](http://stackoverflow.com/questions/28353539/swift-partial-function-application-with-generics)
+ Generic Constructors [:link:](http://stackoverflow.com/a/30857172/2855836) and factories [:link:](http://stackoverflow.com/questions/24341061/how-to-write-generic-factory-method-in-swift)
+ Parametric Polymorphism in Swift [:page_facing_up:](http://nsomar.com/parametric-compile-time-polymorphism-in-swift/) [:page_facing_up:](http://rosettacode.org/wiki/Parametric_polymorphism) [:page_facing_up:](http://cs.stackexchange.com/questions/26389/why-isnt-the-swift-programming-language-type-inference-more-aggressive)
- Template Metaprogramming Swift [:page_facing_up:](http://stackoverflow.com/questions/26939354/metaprogramming-in-swift)
- Generic Typealias in Swift [:page_facing_up:](http://stackoverflow.com/questions/27084586/generic-typealias-in-swift)
- Swift “where” keyword [:link:](http://stackoverflow.com/questions/25336079/swift-where-key-word/25336571#25336571)

[:arrow_up:](#index)

#### **Initializers, Properties, and Dependency Injection**
+ Initializers
    + Swift Initializers [:page_facing_up:](http://ashfurrow.com/blog/swift-initializers/)
    + Be Mindful of Your Filters [:page_facing_up:](http://owensd.io/blog/be-mindful-of-your-filters/)
    + Swift Initialization and the Pain of Optionals [:page_facing_up:](http://blog.scottlogic.com/2014/11/20/swift-initialisation.html)
    + initializers for Structs [:page_facing_up:](http://www.codingexplorer.com/structures-swift/)
    + Swift init() [:page_facing_up:](http://merowing.info/2015/11/swift-init/)
    + Public Getter, Private Setter [:page_facing_up:](https://www.natashatherobot.com/swift-magic-public-getter-private-setter/)
    - What are get and set? [:page_facing_up:](http://stackoverflow.com/questions/24699327/swift-what-are-get-and-set)
    - Why is the convenience keyword needed in Swift? [:link:](http://stackoverflow.com/questions/30896231/why-convenience-keyword-is-even-needed-in-swift)
    - When should I use deinit? [:link:](http://stackoverflow.com/questions/24018758/when-should-i-use-deinit)
    - Designated and Convenience initializers in Swift [:page_facing_up:](http://www.codingexplorer.com/designated-initializers-convenience-initializers-swift/)
    - Writing Class Initalizers [:page_facing_up:](http://www.codingexplorer.com/class-initializers/)
    + Swift Failiable Initializers [:page_facing_up:](http://www.jessesquires.com/swift-failable-initializers-revisited/)
    - Designated Initializer Basics [:page_facing_up:](https://littlebitesofcocoa.com/204-swift-designated-initializer-basics)
+ Properties
    + Stored Properties
        + Class Properties in Swift [:page_facing_up:](http://stackoverflow.com/questions/24087936/how-do-i-make-class-methods-properties-in-swift)
        + Stored Properties [:page_facing_up:](https://www.quora.com/Apple-Swift-programming-language/What-is-a-stored-property)
        - The Importance of Being Final [:page_facing_up:](http://blog.human-friendly.com/the-importance-of-being-final)
    - Named Parameters
        - Named Parameters [:page_facing_up:](http://owensd.io/blog/named-parameters/)
        - Intuition behind the Swift external/local parameter system [:page_facing_up:](https://jeremywsherman.com/blog/2014/06/05/intuition-behind-swift-external-local-parameter-system/)
        - Swift named parameters [:page_facing_up:](http://useyourloaf.com/blog/swift-named-parameters.html)
    - Property Observers
        - Property Observers and Lazy Properties [:page_facing_up:](https://littlebitesofcocoa.com/179-swift-tricks-properties)
        + Property Observers [:page_facing_up:](https://www.quora.com/Apple-Swift-programming-language/What-is-a-property-observer)
        - Swift Property Observers [:page_facing_up:](http://www.codingexplorer.com/swift-property-observers/)
        + IBOutlet Style in Swift [:page_facing_up:](http://natashatherobot.com/ios-a-beautiful-way-of-styling-iboutlets-in-swift/)
    - Computed Properties
        - Beware of Computed Properties [:page_facing_up:](https://www.natashatherobot.com/swift-computed-properties/)
        - How to use swift computed properties [:page_facing_up:](http://adamdelong.com/how-to-use-swift-computed-properties-to-create-a-simple-goal-tracker-class/)
        - Computed Properties and Initializers [](http://www.codingexplorer.com/swift-extensions/)
        - Static Vars are Lazy in Swift [:link:](https://developer.apple.com/swift/blog/?id=7)
        + Lazy Properties in Structs [:page_facing_up:](http://oleb.net/blog/2015/12/lazy-properties-in-structs-swift/)
+ Dependency Injection
    - Swift Injection Wesite [:link:](https://yoichitgy.github.io/)
    + You Used To Inject Me In Your Constructor [:floppy_disk:](https://speakerdeck.com/mathonsunday/you-used-to-inject-me-in-your-constructor)
    + Swift Inject Dependency Injection [:pencil2:](https://github.com/Swinject/Swinject)
    - How to Dependency Inject on iOS [:microphone:](https://www.youtube.com/watch?v=384rumYOs-g)
    - Dependency Injection in Swift [:page_facing_up:](https://medium.com/ios-os-x-development/dependency-injection-in-swift-a959c6eee0ab#.r2gq9cjv7) [:page_facing_up:](http://natashatherobot.com/ios-unit-testing-dependency-injection-with-structs-in-swift/) [:page_facing_up:](https://medium.com/ios-os-x-development/dependency-injection-in-view-controllers-9fd7d2c77e55#.wxwnwtqmo)
    + Dependency Injection with a Custom Initializer [:page_facing_up:](https://www.natashatherobot.com/swift-dependency-injection-with-a-custom-initializer/)
    - Dependency Injection Container [:pencil2:](https://github.com/AliSoftware/Dip) [:pencil2:](https://github.com/AliSoftware/Dip-UI)

[:arrow_up:](#index)

#### **Interpolability with C and Objective-C**
- C
    + Swift and C [:microphone:](https://realm.io/news/pragma-chris-eidhof-swift-c/)
    - Why C is not always safe Swift [:page_facing_up:](http://www.cocoawithlove.com/blog/2016/02/16/use_it_or_lose_it_why_safe_c_is_sometimes_unsafe_swift.html)
    + Wrapping a C library in a Swift Framework [:page_facing_up:](http://colindrake.me/2015/10/05/wrapping-a-c-library-in-a-swift-framework/)
    + Mapping Swift Types to C Pointers [:page_facing_up:](https://tetontech.wordpress.com/2014/10/22/swift-c-libraries-and-mapping-swift-types-to-c-pointer-types/)
    - Swift Interop [:microphone:](https://www.skilled.io/chriseidhof/swift-interop)
    - char ** in Swift [:page_facing_up:](http://dduan.net/post/2015/11/char-star-star-in-swift/)
    - C Pointer Memory [:page_facing_up:](http://en.swifter.tips/pointer-memory/)
- Objective-C
    + Swift & the ObjC Runtime [:page_facing_up:](http://nshipster.com/swift-objc-runtime/)
    + How is Swift Faster than Objective-C? [:page_facing_up:](https://www.quora.com/How-is-Swift-faster-than-Objective-C)
    + How are NSDictionaries implemented in-memory? [:page_facing_up:](http://ciechanowski.me/blog/2014/04/08/exposing-nsdictionary/#comment-1345004966)
    + Exposing NSMutableArray [:page_facing_up:](http://ciechanowski.me/blog/2014/03/05/exposing-nsmutablearray/)
    + Source-Code for the Objective-C Runtime [:pencil2:](http://opensource.apple.com/source/objc4/objc4-551.1/)
    - C Callbacks in Swift [:page_facing_up:](http://oleb.net/blog/2015/06/c-callbacks-in-swift/)
    - Wrapping Objc Frameworks in Swift [:floppy_disk:](https://speakerdeck.com/jpsim/wrapping-objective-c-frameworks-in-swift)
    - Casting Swift objects to Objective-C types [:page_facing_up:](https://plus.google.com/+AndreyTarantsov/posts/AZmU5c3nJwc)

[:arrow_up:](#index)

#### **Internals** 
- ARC
    - ARC + Swift [:page_facing_up:](https://medium.com/the-traveled-ios-developers-guide/arc-swift-d323535baecb#.td8gy7jid)
    + Swift Manual Retain/Release [:page_facing_up:](http://www.russbishop.net/swift-manual-retain-release)
    - ARC in depth [:page_facing_up:](https://sectionfive.net/blog/2015/03/31/arc-in-depth-part-i/) [:page_facing_up:](https://sectionfive.net/blog/2015/06/12/arc-in-depth-part-ii/)
    - ARC + Swift [:page_facing_up:](https://medium.com/the-traveled-ios-developers-guide/arc-swift-d323535baecb#.31lclj25s)
    - ARC Exploration and pitfalls [:page_facing_up:](https://sectionfive.net/blog/2014/11/24/arc-exploration-and-pitfalls/)
- LLVM Compiler
    - WWDC 2014: What's new in LLVM [:microphone:](http://devstreaming.apple.com/videos/wwdc/2014/417xx2zsyyp8zcs/417/417_whats_new_in_llvm.pdf) [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2014/417xx2zsyyp8zcs/417/417_whats_new_in_llvm.pdf)
    + LLVM by Chris Lattner [:page_facing_up:](http://aosabook.org/en/llvm.html)
    + Swift Intermediate Language [:floppy_disk:](http://llvm.org/devmtg/2015-10/slides/GroffLattner-SILHighLevelIR.pdf)
    + Using the LLVM API With Swift [:page_facing_up:](http://lowlevelbits.org/how-to-use-llvm-api-with-swift/)
    - LLVM and Swift [:microphone:](https://www.youtube.com/watch?v=Ntj8ab-5cvE)
    - LLVM in Swift: Setup [:page_facing_up:](http://dduan.net/post/2015/10/lets-play-llvm-in-swift-setup/)
    - Kaleidoscope: Implementing a Parser and AST in LLVM [:page_facing_up:](http://llvm.org/docs/tutorial/LangImpl1.html) [:pencil2:](https://github.com/matthewcheok/Kaleidoscope)
    - Swift Object Name Demangling [:page_facing_up:](https://www.securify.nl/blog/SFY20150302/hooking_swift_methods_for_fun_and_profit.html)
    - How to use LLVM API with Swift [:page_facing_up:](http://lowlevelbits.org/how-to-use-llvm-api-with-swift/) [:page_facing_up:](http://lowlevelbits.org/how-to-use-llvm-api-with-swift-addendum/)
    - Swift Compiler [:page_facing_up:](https://www.accelebrate.com/blog/thinking-swift-part-ii/)
    - Parsing Mach-O files [:page_facing_up:](http://lowlevelbits.org/parse-mach-o-files/)
    - How to use LLVM C API with Swift [:page_facing_up:](https://fosdem.org/2016/schedule/event/llvm_c_swift/) [:page_facing_up:](https://github.com/AlexDenisov/swift_llvm)
- Memory
    - Exploring Swift's Dictionary Implementation [:page_facing_up:](http://ankit.im/swift/2016/01/20/exploring-swift-dictionary-implementation/)
    - Swift Memory Layout [:page_facing_up:](https://www.mikeash.com/pyblog/friday-qa-2014-07-18-exploring-swift-memory-layout.html)
    - Swift Struct Storage [:page_facing_up:](https://www.mikeash.com/pyblog/friday-qa-2016-01-29-swift-struct-storage.html)
    - Bitcode Demystified [:page_facing_up:](http://lowlevelbits.org/bitcode-demystified/)
- Optimizations
    - Switch Statement Optimizations [:link:](http://stackoverflow.com/questions/25284522/switch-statement-optimization-swift)
    - Swift Whole Module Optimization [:page_facing_up:](http://useyourloaf.com/blog/swift-whole-module-optimization/)
    - Increasing Performance by Reducing Dynamic Dispatch [:microphone:](https://developer.apple.com/swift/blog/?id=27)
    - Dynamic Dispatch and Whole Module Optimization [:page_facing_up:](http://useyourloaf.com/blog/dynamic-dispatch-and-whole-module-optimization/)
    - How Swift uses introSort [:page_facing_up:](http://stackoverflow.com/questions/27677026/swift-sorting-algorithm-implementation)
    - Opimizing Swift Performance [:microphone:](https://developer.apple.com/videos/play/wwdc2015-409/)
- Performance
    - Swift Performance [:floppy_disk:](http://blog.human-friendly.com/swift-performance-iosdevuk) [:page_facing_up:](http://www.swift-studies.com/blog/2014/7/8/learning-about-swift-performance)
    - Swift 2 Under the Hood [:floppy_disk:](https://speakerdeck.com/alblue/swift-2-under-the-hood-gotober-2015)
    - Swift Compiler Diagnostics [:page_facing_up:](http://oleb.net/blog/2015/08/swift-compiler-diagnostics/)
    - Swift: Performance of Inline Code versus Instance Methods versus Class Methods [:page_facing_up:](http://flexmonkey.blogspot.com/2014/09/swift-performance-of-inline-code-versus.html)
    - Simple Swift.String Performance Test [:pencil2:](https://github.com/bnickel/Simple-Swift.String-Performance-Test)
    - Secret of Swift Performance [:page_facing_up:](https://medium.com/swift-programming/secret-of-swift-performance-fcc5d2a437a8#.q0cnnqxat) [:page_facing_up:](https://medium.com/swift-programming/secret-of-swift-performance-a8ee86060843#.i6p6554gk)
- SIL and swiftc
    - Explorign SIL and swiftc [:page_facing_up:](http://swiftc.io/)
    - swift vs swiftc [:page_facing_up:](http://owensd.io/2015/01/14/swift-vs-swiftc.html)
    - SIMD (Single Instruction Multiple Data) [:page_facing_up:](http://www.russbishop.net/swift-2-simd)
    - @convention [:page_facing_up:](http://stackoverflow.com/questions/30740560/new-conventionc-in-swift-2-how-can-i-use-it)
    - Introspecting Swift [:floppy_disk:](https://speakerdeck.com/jpsim/introspecting-swift)
    - Unsafe Swift [:floppy_disk:](https://speakerdeck.com/realm/unsafe-swift)
    + Type Introspection [:page_facing_up:](http://ericasadun.com/2014/06/16/swift-more-than-you-probably-want-to-know-about-type-introspection/)
    - The mysterious builtin module [:page_facing_up:](http://ankit.im/swift/2016/01/12/swift-mysterious-builtin-module/)

[:arrow_up:](#index)

#### **Language Comparisons and Transitioning to Swift**
+ Language Comparisons
    - Haskell Overlords [:page_facing_up:](http://robnapier.net/haskell-overlords)
    + Comparing Swift and Javascript [:page_facing_up:](http://www.mircozeiss.com/swift-for-javascript-developers/)
    + C++ Advice to Swift Devs [:page_facing_up:](http://airspeedvelocity.net/2014/06/10/rundown-of-how-each-effective-c-item-relates-to-swift/)
    + Swift Protocols vs Java 8 Interfaces [:page_facing_up:](http://stackoverflow.com/questions/30859334/compare-protocol-in-swift-vs-interface-in-java)
    - Learning Swift from Haskell [:floppy_disk:](https://speakerdeck.com/abizern/what-haskell-teaches-me-about-writing-swift) and corresponding [:microphone:](https://realm.io/news/altconf-abizer-nasir-what-haskell-teaches-me-about-swift/) 
    - Functional Programming like Haskell [:floppy_disk:](https://speakerdeck.com/mchakravarty/functional-programming-in-a-stateful-world) [:microphone:](https://yow.eventer.com/yow-lambda-jam-2015-1305/functional-programming-in-a-stateful-world-by-manuel-chakravarty-1883)
    - Swift vs Golang [:floppy_disk:](http://go-talks.appspot.com/github.com/wangkuiyi/swiftgo/swiftgo.slide#1)
    - Swift 2.0 Protocol Extensions vs Java Abstract Classes [:link:](http://stackoverflow.com/questions/30943209/is-there-a-difference-between-swift-2-0-protocol-extensions-and-java-c-abstract)
    + What do Haskell developers think of Swift? [:link:](https://www.quora.com/What-do-Haskell-developers-think-of-Swift)
    + A Swift intoduction to Haskell [:floppy_disk:](https://speakerdeck.com/johannesweiss/swift-london-meetup-introduction-to-haskell)
    + Swift For Rubyists [:microphone:](https://realm.io/news/swift-for-rubyists/)
    + Swift vs Scala [:floppy_disk:](https://www.reddit.com/r/programming/comments/27dmsb/swift_vs_scala/)
    + OCaml's Deferred in Swift [:page_facing_up:](https://github.com/bignerdranch/Deferred)
    - Pythonic Swift [:pencil2:](https://github.com/practicalswift/Pythonic.swift)
    - Hindley-Milner languages [:link:](http://qr.ae/Rg3rFd)
    - Is Swift a viable alternative to C++ for performance critical code? [:page_facing_up:](https://www.quora.com/Is-Swift-a-viable-alternative-to-C++-for-performance-critical-code?srid=xrLC&share=abc6caeb)
    - Swift vs C speed test [:page_facing_up:](http://stackoverflow.com/questions/24101718/swift-performance-sorting-arrays) [:page_facing_up:](https://www.quora.com/Is-Swift-programming-language-faster-than-C-or-C++-and-if-yes-why) [:page_facing_up:](https://medium.com/swift-programming/swifth-vs-c-5be7d0398f4f#.6ume737mt)
    - Swift vs Java Performance [:page_facing_up:](https://www.quora.com/In-terms-of-performance-speed-is-Swift-faster-than-Java)
    - Go vs Node vs Rust vs Swift [:page_facing_up:](https://grigio.org/go-vs-node-vs-rust-vs-swift/)
+ Transitioning from ObjC
    + Method Swizzling in Swift [:page_facing_up:](http://www.uraimo.com/2015/10/23/effective-method-swizzling-with-swift/)
    + How to Method Swizzle in Swift [:page_facing_up:](http://kostiakoval.github.io/posts/methods-swizzling-in-swift/)
    - A Eulogy for Objective C [:microphone:](https://realm.io/news/altconf-aaron-hillegass-eulogy-for-objective-c/)
    - The best of Obj-C to Swift [:microphone:](https://realm.io/news/altconf-jaim-zuber-the-stylish-objective-c-developer-s-guide-to-swift/) [:page_facing_up:](https://www.quora.com/What-are-the-best-code-examples-to-illustrate-the-benefits-of-Swift)

[:arrow_up:](#index)

#### **Linux Development**
- Intro to Swift Dev on Linux [:page_facing_up:](http://www.raywenderlich.com/122189/introduction-to-open-source-swift-on-linux) [:page_facing_up:](https://www.twilio.com/blog/2015/12/getting-started-with-swift-on-linux.html)
- Dynamic Swift Framework Without Xcode [:page_facing_up:](http://dduan.net/post/2015/07/dynamic-swift-framework-without-xcode/)
- Foundation on Linux [:page_facing_up:](http://dev.iachieved.it/iachievedit/foundation-on-linux/)
- NSLinux Strings [:pencil2:](https://github.com/johnno1962/NSLinux)
- interact with Linux GPIO/SPI on ARM [:pencil2:](https://github.com/uraimo/SwiftyGPIO)

[:arrow_up:](#index)

#### **Optionals and Types** 
+ Optionals
    + How I handle Optionals in Swift [:page_facing_up:](http://blog.human-friendly.com/how-i-handle-optionals-in-swift)
    + How to unwrap an optional in 9 different ways [:page_facing_up:](https://twitter.com/Kametrixom/status/636187970509406209)
    + Optional Protocol Methods in Pure Swift [:page_facing_up:](http://blog.stablekernel.com/optional-protocol-methods-in-pure-swift)
    + Swift Optionals Made Simple [:page_facing_up:](http://appventure.me/2014/06/13/swift-optionals-made-simple/)
    + Every Kind of Optional [:page_facing_up:](http://www.fantageek.com/blog/2015/12/04/optional-in-swift/)  
    - Pervasive use of Optional in Swift is penance for nil [:page_facing_up:](https://jeremywsherman.com/blog/2014/07/09/pervasive-use-of-optional-in-swift-is-penance-for-nil/)
    - Optionals under the hood [:page_facing_up:](https://littlebitesofcocoa.com/173-swift-optionals-under-the-hood)
    - Nil coalescing operator [:page_facing_up:](http://www.codingexplorer.com/nil-coalescing-swift/)
    + Understanding Optional Chaining [:page_facing_up:](http://nomothetis.svbtle.com/understanding-optional-chaining)
+ Types
    + Reference Types 
        + Class or Struct? [:page_facing_up:](http://faq.sealedabstract.com/structs_or_classes/) [:page_facing_up:](http://owensd.io/2015/07/05/re-struct-or-class.html) [:page_facing_up:](https://www.mikeash.com/pyblog/friday-qa-2015-07-17-when-to-use-swift-structs-and-classes.html)
        + let vs var [:page_facing_up:](http://stackoverflow.com/questions/24002092/what-is-the-difference-between-let-and-var-in-swift)
        - Weak, Strong, Unowned [:floppy_disk:](https://speakerdeck.com/realm/weak-strong-unowned-hector-matos)
        - Is Swift Pass By Value or Pass By Reference [:link:](http://stackoverflow.com/questions/27364117/is-swift-pass-by-value-or-pass-by-reference/27366050#27366050)
        - How can I make a weak protocol reference in 'pure' Swift (w/o @objc) [:link:](http://stackoverflow.com/questions/24066304/how-can-i-make-a-weak-protocol-reference-in-pure-swift-w-o-objc)
        - When to use weak pointers with delgates [:link:](http://stackoverflow.com/questions/30056526/swift-delegation-when-to-use-weak-pointer-on-delegate)
        - Instance methods and type methods in Swift [:page_facing_up:](http://www.codingexplorer.com/instance-methods-and-type-methods-in-swift/)
    + Value Types
        + Every Swift Value Type Should be Equatable [:page_facing_up:](https://www.andrewcbancroft.com/2015/07/01/every-swift-value-type-should-be-equatable/)
        - How can I make a container with copy-on-write semantics? [:page_facing_up:](http://stackoverflow.com/questions/32984258/how-can-i-make-a-container-with-copy-on-write-semantics-swift)
        - When to use mutating functions in swift structs [:page_facing_up:](https://www.natashatherobot.com/when-to-use-mutating-functions-in-swift-structs/)
        - Mutating Funcs in Swift Structs [:page_facing_up:](http://natashatherobot.com/mutating-functions-swift-structs/)
        - Making Friends with Value Types [:microphone:](https://realm.io/news/andy-matuschak-controlling-complexity/)
        + Make all Value Types Equatable [:microphone:](https://developer.apple.com/videos/wwdc/2015/?id=414)
        + Safer Swift Code With Value Types [:microphone:](https://realm.io/news/altconf-benjamin-encz-safer-swift-code-with-value-types/) [:page_facing_up:](https://gist.github.com/rbobbins/596bb6896141dca5934d)
        - Swift copy-on-write behaviour for a struct using HeapBuffer [:pencil:](https://gist.github.com/airspeedswift/71f15d1eb866be9e5ac7)
        - Swift pass struct by reference? [:page_facing_up:](http://stackoverflow.com/questions/31495431/swift-pass-struct-by-reference)
    + Abstract Types
        - Understanding Swift’s Abstract Types (Swift 2.2 & above) [:page_facing_up:](http://blog.davidungar.net/2016/02/29/understanding-swifts-abstract-types-swift-2-2-above/)
        - Understanding Abstract Types [:page_facing_up:](http://blog.davidungar.net/2016/01/10/understanding-swifts-abstract-types-2#fn6)
    + Wrapper Types
        + Wrapper Types [:page_facing_up:](https://www.objc.io/blog/2014/11/24/functional-snippet-8-wrapper-types/)
        + Type-Erased Wrappers in Swift [:microphone:](https://realm.io/news/type-erased-wrappers-in-swift/)
    + Phantom Types
        - What are Phantom Types good for? [:page_facing_up:](https://angelovillegas.com/swift-phantom-types/)
        + Phantom Types in Swift [:page_facing_up:](https://www.objc.io/blog/2014/12/29/functional-snippet-13-phantom-types/) [:microphone:](https://realm.io/news/swift-summit-johannes-weiss-leveraging-the-type-system/)
    + Dependent Types
        + Dependent Types in Swift [:page_facing_up:](https://sectionfive.net/blog/2015/08/11/building-almost-dependent-types-in-swift/) and why they matter [:page_facing_up:](https://jeremywsherman.com/blog/2015/08/26/read-why-dependent-types-matter/)
        + Can Swift have Dependent Types? [:pencil:](https://github.com/oisdk/ConstArray/blob/master/Playground.playground/Contents.swift) [:page_facing_up:](https://github.com/oisdk/PretendDependSwift)
        + More Misunderstanding of Dependent Types [:page_facing_up:](https://bigonotetaking.wordpress.com/2015/09/06/yet-more-misunderstanding-of-dependent-types/)
        - An implementation of a dependently-typed intermediate language [:pencil2:](https://github.com/antitypical/Manifold)
        - Dependent Types: I'm missing something [:page_facing_up:](http://owensd.io/blog/dependent-types-im-missing-something/)
        - Backwards Dependent Types [:page_facing_up:](https://jeremywsherman.com/blog/2015/10/02/what-if-you-get-your-dependent-type-backwards/)
        - Type-Level Assertions (or, almost-dependent types) [:pencil:](https://gist.github.com/JadenGeller/f39130616846f9bf9879)
        - Validated: A Swift μ-Library for Somewhat Dependent Types [:page_facing_up:](http://blog.benjamin-encz.de/validated-a-swift-m-library-for-somewhat-dependent-types/)
    + Dynamic Types
        - DynamicType and MultiMethods [:page_facing_up:](http://en.swifter.tips/multi-method/)
    + Nested Types
        - Lazy Nested Types [:page_facing_up:](https://littlebitesofcocoa.com/)
        - Using a nested type in Swift [:page_facing_up:](http://www.codingexplorer.com/using-nested-type-swift/)
    + Type Reflection and Casting
        + Simple Reflection in Swift [:page_facing_up:](http://freecake.angelodipaolo.org/simple-reflection-in-swift/)
        + Understanding Reflection in Swift and how to use it [:page_facing_up:](http://appventure.me/2015/10/24/swift-reflection-api-what-you-can-do/)
        + Typecasting and the Swift Runtime [:page_facing_up:](https://github.com/vandadnp/swift-weekly/blob/master/issue08/README.md)
        - Advanced Type Safety in Swift [:floppy_disk:](https://github.com/jspahrsummers/correct-behavior-through-type-safety/blob/master/Correct%20Behavior%20Through%20Type%20Safety.pdf), and corresponding [:microphone:](https://realm.io/news/altconf-justin-spahr-summers-type-safety/)
        + Why doesn't Swift have implicit type conversion? [:page_facing_up:](https://www.quora.com/Why-does-Swift-not-allow-implicit-type-conversion)
        + as? vs as! [:page_facing_up:](http://stackoverflow.com/questions/25708649/downcasting-optionals-in-swift-as-type-or-as-type)  
        + Understanding Downcasting Operators in Swift [:page_facing_up:](http://stackoverflow.com/questions/25708649/downcasting-optionals-in-swift-as-type-or-as-type) 
        - Type check with switch statements [:page_facing_up:](http://www.tekramer.com/using-switch-statements-for-type-checking-in-swift/)
    + Associated Types
        + Protocols with Associated Types and how they got that way [:floppy_disk:](https://speakerdeck.com/algal/protocols-with-associated-types-and-how-they-got-that-way) [:microphone:](https://www.youtube.com/watch?v=XWoNjiSPqI8)
        + Associated Types in Swift Explained [:page_facing_up:](http://www.russbishop.net/swift-associated-types) [:page_facing_up:](http://www.natashatherobot.com/swift-protocols-with-associated-types/)
        + Illuminating Forum Post [:page_facing_up:](https://forums.developer.apple.com/message/18038)
        + How to make Generic Protocols in Swift [:page_facing_up:](http://milen.me/writings/swift-generic-protocols/)
        + Associated Enum Data As Types [:page_facing_up:](http://owensd.io/2015/09/15/associated-enum-cases-as-types.html)
        + Typesafe Associated Objects [:pencil2:](https://github.com/kballard/swift-tsao)
    + Metatypes
        + Types and Metatypes in Swift [:page_facing_up:](https://medium.com/@NSomar/types-and-meta-types-in-swift-9cd59ba92295#.1o9z1ikpc)
        + Higher Kinded Types [:pencil:](https://gist.github.com/adamkuipers/bb7bdb9cc425de8905c7) [:page_facing_up:](https://lists.swift.org/pipermail/swift-evolution/Week-of-Mon-20151214/003122.html) [:page_facing_up:](https://www.quora.com/What-language-features-can-make-Swift-even-better) [:link:](https://github.com/typelift/swift/issues/1)
        + Swift MetaTypes [:page_facing_up:](http://jasdev.me/lets-get-meta)
        + Typeclasses in Swift and Scala [:page_facing_up:](http://brainyandbrawny.com/article/Typeclass_in_Swift_and_Scala)
        + Creating new Types in Swift [:page_facing_up:](https://developer.apple.com/swift/blog/?id=8)
        - What is ExistentialMetatype in Swift [:page_facing_up:](http://stackoverflow.com/questions/25342832/what-is-existentialmetatype-in-swift)
    + Typeclasses
        + Typeclasses in Swift, Haskell and Scala [:page_facing_up:](http://siejkowski.net/typeclasses-in-swift/)
    + Type Inference
        - Implicit Member Expression [:page_facing_up:](http://ericasadun.com/2015/04/21/swift-occams-code-razor/)
        - Referential Transparency [:link:](https://www.reddit.com/r/swift/comments/2ffk7z/what_is_swift_imperative_functional/) 
    + Type Variance
        - Type Variance in Swift [:page_facing_up:](http://nomothetis.svbtle.com/type-variance-in-swift)
    + Other
        + Swift's Type System [:page_facing_up:](http://oleb.net/blog/2015/07/swift-type-system/)
        + The Natural Numbers Encoded as Types [:page_facing_up:](https://forums.developer.apple.com/thread/19942)
        + Return Type Polymorphism in Swift [:page_facing_up:](http://www.figure.ink/blog/2015/1/25/polymorphism-with-return-types) [:link:](https://news.ycombinator.com/item?id=8826422)

[:arrow_up:](#index)

#### **Problem Solving with Swift**
- FizzBuzz on steroids with Swift [:floppy_disk:](https://speakerdeck.com/abizern/fizz-buzz-in-swift)
- Learning Swift the Euler Way [:microphone:](https://vimeo.com/136059613)
+ Swift in Practice [:microphone:](https://developer.apple.com/videos/wwdc/2015/?id=411)
+ Make a DSL in Swift [:page_facing_up:](http://colindrake.me/2015/10/28/implementing-a-small-dsl-in-swift/) [:floppy_disk:](https://speakerdeck.com/kylef/dsls-in-swift) [:floppy_disk:](https://speakerdeck.com/luisobo/techniques-to-write-dsls-in-swift) [:microphone:](https://www.youtube.com/watch?v=a3rR5XVA22w)
+ Implementing goto in Swift [:page_facing_up:](https://harlanhaskins.com/2016/01/09/goto-in-swift.html)
+ Functional ASCII Art [:page_facing_up:](https://github.com/ijoshsmith/swift-ascii-art)
+ Writing 2048 in Swift [:page_facing_up:](https://realm.io/news/swift-2048/)
- FlappySwift [:pencil2:](https://github.com/fullstackio/FlappySwift)
- Parallel Mandelbrot Set in Swift [:page_facing_up:](http://blog.scottlogic.com/2014/10/29/concurrent-functional-swift.html)

[:arrow_up:](#index)

#### **Production Swift**
- How Carthage works [:floppy_disk:](https://speakerdeck.com/jspahrsummers/ruthlessly-simple-dependency-management-with-carthage) [:floppy_disk:]((https://speakerdeck.com/abizern/carthage))
- Bottom Up Programming in Swift [:microphone:](https://realm.io/news/altconf-airspeed-velocity-bottom-up-programming-in-swift/)
- Make a Cocoapods Framework [:microphone:](https://realm.io/news/altconf-billy-tobon-brew-your-own-cocoa-framework/)
- Lessons from Production Swift [:floppy_disk:](https://speakerdeck.com/ashfurrow/lessons-from-production-swift)
- Using the Swift Package Manager [:page_facing_up:](http://kostiakoval.github.io/posts/swift-package-manager/) [:page_facing_up:](https://honzadvorsky.com/articles/2016-02-25-14-00-3_steps_to_marry_xcode_with_swift_package_manager/)
- IBM Swift Package Catalog [:link:](https://swiftpkgs.ng.bluemix.net/)
- Exclude folders in the SPM [:page_facing_up:](http://kostiakoval.github.io/posts/exclude-folders---new-feature-in-swift-package-manager/)
- Swift, Frameworks & Modules, Learnings from CocoaPods [:page_facing_up:](https://speakerdeck.com/realm/swift-frameworks-and-modules-learnings-from-cocoapods)
- BuddyBuild Continuous Integration [:link:](http://buddybuild.com/)
- Swift Package Manager [:floppy_disk:](https://speakerdeck.com/neonichu/swift-package-manager)
- Naming assets [:pencil:](https://github.com/dkhamsing/ios-asset-names)
- Xcode Snippets [:pencil2:](https://github.com/burczyk/XcodeSwiftSnippets)

[:arrow_up:](#index)

#### **Protocols**
+ Swift Comparison Protocols [:page_facing_up:](http://nshipster.com/swift-comparison-protocols/)
- Protocols in Swift [:page_facing_up:](http://www.codingexplorer.com/protocols-swift/)

[:arrow_up:](#index)

#### **Protocol Oriented Programming in Swift 2**
+ :raised_hands: Protocol-Oriented Programming in Swift [:microphone:](https://developer.apple.com/videos/wwdc/2015/?id=408) [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2015/408509vyudbqvts/408/408_protocoloriented_programming_in_swift.pdf?dl=1) [:pencil:](https://gist.github.com/rbobbins/de5c75cf709f0109ee95) [:page_facing_up:](https://medium.com/swift-programming/protocol-oriented-programming-a3e192f6e8f2#.b3vmjxbzy)
+ Protocols in Swift [:page_facing_up:](http://austinzheng.com/2014/12/24/protocols-in-swift/)
+ POP is OOP Thesis [:page_facing_up:](http://blog.metaobject.com/2015/06/protocol-oriented-programming-is-object.html)
+ Standard Template Protocols [:pencil2:](https://github.com/cconeil/Standard-Template-Protocols)
+ Protocol Oriented MVVM [:page_facing_up:](http://natashatherobot.com/swift-2-0-protocol-oriented-mvvm/), [:floppy_disk:](http://www.slideshare.net/natashatherobot/protocoloriented-mvvm-extended-edition)
+ Functional thinking via Protocol Extensions [:page_facing_up:](http://kelan.io/2015/approachable-functional-thinking-using-protocol-extensions/)
+ Protocol Extensions vs Type Extensions [:page_facing_up:](https://gist.github.com/hsavit1/3337f80d9fe1396c44ce)
+ What are the advantages? [:page_facing_up:](http://www.infoq.com/news/2015/06/protocol-oriented-swift)
+ Another look into the concept of P.O.P.  [:page_facing_up:](http://willowtreeapps.com/blog/protocol-oriented-programming/)
+ If you're subclassing, you're doing it wrong. POP and VOP explained [:page_facing_up:](http://krakendev.io/blog/subclassing-can-suck-and-heres-why)
+ Protocol Oriented Programming through UIKit [:page_facing_up:](http://www.captechconsulting.com/blogs/ios-9-tutorial-series-protocol-oriented-programming-with-uikit)
+ Protocols in Swift [:page_facing_up:](http://ashfurrow.com/blog/protocols-and-swift/)
+ Ray Wenderlich intro to POP [:page_facing_up:](http://www.raywenderlich.com/109156/introducing-protocol-oriented-programming-in-swift-2)
+ Protocol Extensions and the death of the Pipe forward operator [:page_facing_up:](http://airspeedvelocity.net/2015/06/23/protocol-extensions-and-the-death-of-the-pipe-forward-operator/)
+ How Protocol Oriented Programming could still improve [:page_facing_up:](https://bigonotetaking.wordpress.com/2015/07/17/swift-protocols-a-strategy/)
+ The Swift Protocol Proposal [:page_facing_up:](http://kickingbear.com/blog/archives/521)
+ Swift Default Protocol Implementations [:page_facing_up:](http://nshipster.com/swift-default-protocol-implementations/)
+ :raised_hands: Mixins and Traits in Swift 2.0 [:page_facing_up:](http://matthijshollemans.com/2015/07/22/mixins-and-traits-in-swift-2/)
+ Minimal Swift 2.1 Protocol Coformance [:page_facing_up:](http://softwaredesign.jeffverkoeyen.com/minimal-swift-protocol-conformance/)
+ Favor Mixins over inheritance [:page_facing_up:](http://alisoftware.github.io/swift/protocol/2015/11/08/mixins-over-inheritance/)
+ Use Protocol Composition [:page_facing_up:](http://natashatherobot.com/swift-protocol-composition/)
- 55 Standard Library Swift Protocols [:floppy_disk:](https://speakerdeck.com/gregheo/what-i-learned-from-55-star-swift-standard-library-protocols) [:page_facing_up:](http://swiftunboxed.com/protocols/swift-standard-library-protocols-lessons/) [:microphone:](http://www.skilled.io/gregheo/what-the-55-swift-standard-library-protocols-taught-me)
- Current Recommmended Protocol Usage [:page_facing_up:](http://owensd.io/2015/08/06/protocols.html)
- POP in Swift vs ObjC and C++ [:page_facing_up:](http://owensd.io/2015/06/16/protocol-oriented-programming.html)
- POP Utility Belt [:pencil2:](https://github.com/tptee/Oriole)
- Typesafe and Composable Data Sources in Swift [:page_facing_up:](http://www.jessesquires.com/building-data-sources-in-swift/)
- Protocol Extension Method Dispatch [:page_facing_up:](https://medium.com/ios-os-x-development/swift-protocol-extension-method-dispatch-6a6bf270ba94#.xsrtw75qp)
- The Genius of Protocols [:page_facing_up:](https://www.wooji-juice.com/blog/swift-genius-of-protocols.html)
+ Properties of Types Conforming to Protocols [:page_facing_up:](http://ilya.puchka.me/properties-of-types-conforming-to-protocols-in-swift/)

[:arrow_up:](#index)

#### **Security** 
- Encryptor / Decryptor Data Format [:pencil2:](https://github.com/RNCryptor/RNCryptor)
- CommonCrypto in Swift [:microphone:](https://realm.io/news/danny-keogan-swift-cryptography/)
- Ceaser Cipher in Swift [:page_facing_up:](https://www.objc.io/blog/2015/01/26/functional-snippet-17-caesar-ciphers/) [:page_facing_up:](http://ijoshsmith.com/2015/04/14/caesar-cipher-in-swift/)
- Swift-ly secure [:microphone:](https://realm.io/news/seth-law-swift-security/)
- Common Crypto [:page_facing_up:](http://sketchytech.blogspot.com/2016/02/resurrecting-commoncrypto-in-swift-for.html)
- Reverse Engineering iOS Apps [:microphone:](https://realm.io/news/conrad-kramer-reverse-engineering-ios-apps-lyft/)
- Security and Your Apps [:microphone:](https://developer.apple.com/videos/play/wwdc2015/706/)

[:arrow_up:](#index)

#### **Server Side Swift**
- Hello Server Side Swift [:page_facing_up:](https://medium.com/@LogMaestro/server-side-swift-c965b7ebe6e7#.vitoriti4)
- Vapor Swift Web Framework [:pencil2:](https://github.com/tannernelson/vapor)
- Kitura Web Framework and HTTP Server [:pencil2:](https://github.com/IBM-Swift/Kitura) [:pencil2:](https://github.com/IBM-Swift/Kitura-BluePic)
- Swift Redis [:pencil2:](https://github.com/swizzlr/swift-redis)
- TCP Sockets in Swift [:pencil2:](http://dev.iachieved.it/iachievedit/tcp-sockets-with-swift-on-linux/)
- Zevo Server Side Swift Community [:link:](https://github.com/Zewo)
- Venice based HTTP server for Swift 2.2 on Linux [:pencil2:](https://github.com/Zewo/Epoch)
- Swift HTTP Servers [:pencil2:](https://github.com/paulofaria/SwiftHTTPServer) [:pencil2:](https://github.com/kylef/Curassow) [:pencil2:](https://github.com/glock45/swifter) [:pencil2:](https://github.com/elliottminns/blackfish)
- Swift Server IO [:pencil2:](https://github.com/LoganWright/swift-server-io)
- Swift on Rails [:pencil2:](https://github.com/necolt/Swifton)
- Swift Website Example [:pencil2:](https://github.com/kylef/Curassow-example-helloworld)
- Swift Express - a simple unopinionated web application server [:pencil2:](https://github.com/crossroadlabs/Express)

[:arrow_up:](#index)

#### **Strings and Regular Expressions**
+ Strings
    + Swift String Cheat Sheet [:page_facing_up:](http://useyourloaf.com/blog/swift-string-cheat-sheet.html) [:pencil:](https://gist.github.com/kharrison/08d1db4169d70a88b194)
    + How is the String type implemented? [:page_facing_up:](https://www.quora.com/Apple-Swift-programming-language/How-is-the-String-type-implemented)
    + Useful String Library [:pencil2:](https://github.com/erica/SwiftString)
    - Symbology in Swift [:page_facing_up:](http://ericasadun.com/2016/01/13/a-few-thoughts-on-swift-symbologygist/)
    - Functional String Ranges [:page_facing_up:](https://www.natashatherobot.com/swift-string-ranges-the-functional/)
    - ICU Text Transforms in Cocoa [:page_facing_up:](http://oleb.net/blog/2016/01/icu-text-transforms/)
    - Swift Substrings [:page_facing_up:](http://vluxe.io/swift-sub-strings.html)
+ Lexing and Parsing
    - Abstract Syntax Tree [:page_facing_up:](http://ankit.im/swift/2016/02/29/swift-abstract-syntax-tree/)
    + Creating a Lexer in Swift [:page_facing_up:](http://blog.matthewcheok.com/writing-a-lexer-in-swift/)
    + Creating an Abstract Syntax Tree Parser in Swift [:page_facing_up:](http://blog.matthewcheok.com/writing-a-parser-in-swift/) [:page_facing_up:](http://blog.matthewcheok.com/writing-a-parser-in-swift-part-2/)
    + String to Number Parser [:pencil2:](https://github.com/davedelong/DDMathParser)
    + Madness: Parsing strings in simple context-free grammars [:pencil2:](https://github.com/robrix/Madness)
+ Regular Expressions
    + RegularExpressions in Swift [:page_facing_up:](https://littlebitesofcocoa.com/121-swiftier-regular-expressions-with-regex) [:page_facing_up:](http://en.swifter.tips/regex/) [:page_facing_up:](http://benscheirman.com/2014/06/regex-in-swift/)
    + NSRegularExpression Cheat Sheet [:page_facing_up:](http://www.raywenderlich.com/86205/nsregularexpression-swift-tutorial)
    + Clean Regular Expressions in Swift [:page_facing_up:](http://nomothetis.svbtle.com/clean-regular-expressions-using-conversions)
    + Simple Regex [:pencil:](https://gist.github.com/mattt/3f12f56d72b8d2ebbe62)
    + Verbal Expressions style RegEx [:pencil2:](https://github.com/VerbalExpressions/SwiftVerbalExpressions)
    
[:arrow_up:](#index)

#### **Swift Language FAQs**
- About Swift 
    - Switching your brain to Swift [:page_facing_up:](https://gregheo.com/blog/switching-your-brain-to-swift/#value-types)
    - Short Circuit Evaluation [:page_facing_up:](https://en.wikipedia.org/wiki/Short-circuit_evaluation)
    - How Swift makes your life better [:page_facing_up:](http://bandes-stor.ch/blog/2015/11/28/help-yourself-to-some-swift/)
    - Emerging best practices in Swift [:microphone:](https://realm.io/news/gotocph-ash-furrow-best-practices-swift/)
    - Swift Thinking [:microphone:](https://realm.io/news/altconf-natasha-murashev-swift-thinking/)
    - Hidden Gems in Swift [:microphone:](https://netguru.co/blog/hidden-gems-swift)
    - Catching up with Swift [:floppy_disk:](https://speakerdeck.com/ashfurrow/catching-up-with-swift)
    - Idiomatic Swift [:floppy_disk:](https://speakerdeck.com/ashfurrow/solving-problems-the-swift-way)
    - Swiftly Methods [:page_facing_up:](http://radex.io/swift/methods/)
    + Improving your Existing Apps with Swift [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2015/403l7ohdidhmnkgx/403/403_improving_your_existing_apps_with_swift.pdf?dl=1)
    + How Swift makes clean code [:page_facing_up:](http://ulrikdamm.logdown.com/posts/246079)
    - % of top 100 apps using Swift [:page_facing_up:](https://medium.com/@ryanolsonk/are-the-top-apps-using-swift-42e880e7727f#.jgaol4shg)
    - 10 Swift One Liners To Impress Your Friends [:page_facing_up:](https://www.uraimo.com/2016/01/06/10-Swift-One-Liners-To-Impress-Your-Friends/)
- Open Source Swift
    + Swift Brief [:notebook:](http://swiftweekly.github.io/)
    + Booleans [:page_facing_up:](http://swiftunboxed.com/open-source/Bool/)
    + Swift Open Source Overview [:page_facing_up:](http://www.jessesquires.com/swift-open-source/)
    + Open Source Swift 3.0 Roadmap [:page_facing_up:](https://realm.io/news/swift-opensource/)
    - Building for Open Source [:floppy_disk:](https://speakerdeck.com/kylef/building-for-open-source)
    - Swift Android [:pencil2:](https://github.com/SwiftAndroid/swift)
    - Swift Version Manager [:pencil2:](https://github.com/kylef/swiftenv)
    - Properly Typed Selectors in Xcode 7.3 beta 4 [:page_facing_up:](http://flexmonkey.blogspot.co.uk/2016/02/properly-typed-selectors-in-xcode-73.html)
+ Opinions about Swift
    + Wishlist for Swift 3.0 [:page_facing_up:](https://realm.io/news/swift-3-wishlist/)
    + The Death of Cocoa [:page_facing_up:](http://nshipster.com/the-death-of-cocoa/)
    + Swift is _not_ functional [:page_facing_up:](https://www.reddit.com/r/swift/comments/281jqe/rob_napier_swift_is_not_functional/) [:page_facing_up:](http://robnapier.net/swift-is-not-functional)
    + Which features overcomplicate Swift? What should be removed? [:page_facing_up:](https://www.quora.com/Which-features-overcomplicate-Swift-What-should-be-removed)
    + Does Apple Swift have enough functional features to be considered as a functional language? Why? [:page_facing_up:](https://www.quora.com/Does-Apple-Swift-have-enough-functional-features-to-be-considered-as-a-functional-language-Why)
    + What is the bare minimum you need to learn Swift? [:page_facing_up:](https://www.quora.com/What-should-you-know-before-you-try-to-learn-Swift)
    + How flexible is Swift? [:page_facing_up:](https://www.quora.com/How-flexible-is-Swift)
    - Top 10 iOS Swift libraries every iOS developer should know about [:page_facing_up:](https://infinum.co/the-capsized-eight/articles/top-10-ios-swift-libraries-every-ios-developer-should-know-about)
+ Swift Versions
    - What's new in Swift 2 [:microphone:](https://developer.apple.com/videos/play/wwdc2015-106) [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2015/106z3yjwpfymnauri96m/106/106_whats_new_in_swift.pdf?dl=1)
    - Diving into Swift 2 [:page_facing_up:](http://www.fantageek.com/blog/2015/12/18/a-dive-into-swift-2/)
    - Best of Swift 2 [:page_facing_up:](https://www.mikeash.com/pyblog/friday-qa-2015-06-19-the-best-of-whats-new-in-swift.html)
    - New Features in Swift 2 [:page_facing_up:](https://www.hackingwithswift.com/new-features-swift-2)
    - @available [:page_facing_up:](http://www.klundberg.com/blog/Swift-2-and-@available-properties/) [:pencil:](https://www.bignerdranch.com/blog/hi-im-available/)

[:arrow_up:](#index)

#### **Testing Swift Code**
- Unit Testing
    - Testing in Xcode 6 [:microphone:](https://developer.apple.com/videos/play/wwdc2014/414/)
    - Better Unit Testing with Swift [:page_facing_up:](http://masilotti.com/better-swift-unit-testing/)
    - Unit Testing in Swift [:page_facing_up:](https://bendyworks.com/unit-testing-in-swift/) [:page_facing_up:](http://nshipster.com/xctestcase/)
    - Unit Testing with @testable in Xcode 7 [:page_facing_up:](http://natashatherobot.com/swift-2-xcode-7-unit-testing-access/) [:page_facing_up:](http://mr-v.github.io/xcode-7-swift-2-unit-testing-setup/)
    - Understanding testability in Swift 2 [:page_facing_up:](http://www.captechconsulting.com/blogs/ios-9-tutorial-series-testability-by-example-making-unit-testing-easier-in-swift-20-and-xcode-7)
    - The good parts of XCTest [:page_facing_up:](http://modocache.io/xctest-the-good-parts)
    - QuickCheck made in Swift [:page_facing_up:](http://chris.eidhof.nl/posts/quickcheck-in-swift.html)
    - Test callbacks with XCTests [:page_facing_up:](http://www.mokacoding.com/blog/testing-callbacks-in-swift-with-xctest/)
- TDD
    - TDD with Swift [:page_facing_up:](http://swiftandpainless.com/category/tdd/)
    - TDD By Controlling Dependencies in Swift [:microphone:](https://www.youtube.com/watch?v=qYpURmZcCKs&index=47&list=PLEx5khR4g7PL0fDNJkI2dHhqeckQTAbes), [:microphone:](http://gotocon.com/dl/goto-cph-2015/slides/JorgeD.OrtizFuentes_TestDrivenDevelopmentbyControllingDependencies.pdf)
    - TDD on iOS [:microphone:](https://realm.io/news/altconf-glen-tregoning-paul-zabelin-successful-test-driven-development-on-ios/)
    - How to TDD in Swift [:page_facing_up:](http://roadfiresoftware.com/2015/09/how-you-can-do-tdd-with-swift/)
    - TDD Swift Playground [:page_facing_up:](http://initwithstyle.net/2015/11/tdd-in-swift-playgrounds/)
    - Swift version of Graham Lee's "Test-Driven iOS Development" [:pencil2:](https://github.com/SixFiveSoftware/BrowseOverflowSwift)
- BDD
    - BDD Testing with Swift [:page_facing_up:](http://railsware.com/blog/2014/07/04/bdd-style-testing-in-swift-with-sleipnir/)
    - SwiftTest BDD Testing Framework [:pencil2:](https://github.com/bppr/Swiftest)
    - Intro to Quick and Nimble [:page_facing_up:](http://theiostimes.com/advent-calendar/quick-nimble.html)
    - Testing in Swift with Quick [:microphone:](https://realm.io/news/testing-in-swift/) [:microphone:](https://realm.io/news/rachel-bobbins-testing-view-controllers-quick/)
    - Quick Testing Framework [:pencil2:](https://github.com/Quick/Quick) [:page_facing_up:](http://blog.benjamin-encz.de/how-i-write-swift-specs-with-quick/)
    - Nimble Matcher Framework [:pencil2:](https://github.com/Quick/Nimble)
- UI Testing
    - UI Testing Cheat Sheet [:page_facing_up:](http://masilotti.com/ui-testing-cheat-sheet/) [:page_facing_up:](http://www.runtimecrash.com/tag/xcuielementquery/)
    + UI Testing in Xcode [:microphone:](https://developer.apple.com/videos/wwdc/2015/?id=406) [:page_facing_up:](http://www.runtimecrash.com/tag/xcuielementquery/) [:page_facing_up:](http://www.mokacoding.com/blog/xcode-7-ui-testing/) [:page_facing_up:](https://www.bignerdranch.com/blog/ui-testing-in-xcode-7-part-1-ui-testing-gotchas/) [:page_facing_up:](http://masilotti.com/ui-testing-xcode-7/) [:pencil:](https://gist.github.com/rbobbins/f8f23916c741379bbd66)
    - Replacing KIF with XCUI Tests [:page_facing_up:](http://www.catehuston.com/blog/2015/11/11/replacing-kif-tests-with-xcui-tests/)
    - Three Ways UI Testing Just Made TDD Better [:page_facing_up:](http://masilotti.com/ui-testing-tdd/)
    - Unit and UI tests with code coverage [:page_facing_up:](https://speakerdeck.com/ugocastro/unit-and-ui-tests-with-code-coverage-on-xcode-7-using-swift-2)
    - UI or Unit tests? [:page_facing_up:](http://christiantietze.de/posts/2016/02/unit-or-integrated-tests/)
- Debugging
    - Debugging Xcode 6 [:microphone:](https://developer.apple.com/videos/play/enterprise-413/)
    - View Debugging in Xcode [:page_facing_up:](http://www.raywenderlich.com/98356/view-debugging-in-xcode-6)
    - WWDC 2014: Introduction to LLDB and Swift REPL [:microphone:](https://developer.apple.com/videos/play/wwdc2014-409/)
    - Swift Debugging Tips [:page_facing_up:](https://www.natashatherobot.com/swift-debugging/)
    - WWDC 2014: Advanced Swift Debugging with LLDB [:microphone:](https://developer.apple.com/videos/play/wwdc2014-410/) [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2014/410xx1s19e83i5z/410/410_advanced_swift_debugging_in_lldb.pdf)
    - Chisel LLVM Debugging [:pencil2:](https://github.com/facebook/chisel)
    - Swift Name Mangling [:page_facing_up:](https://www.mikeash.com/pyblog/friday-qa-2014-08-15-swift-name-mangling.html)
    - Assertions in Swift [:page_facing_up:](http://stackoverflow.com/questions/28394173/assertions-in-swift)
    - Debugging with stack traces in Swift [:page_facing_up:](http://www.cocoawithlove.com/blog/2016/02/28/stack-traces-in-swift.html)
- Network Testing
    - Network Testing in Swift and DVR [:microphone:](https://realm.io/news/soffes-swift-network-testing-dvr/) [:page_facing_up:](https://blog.soff.es/network-testing-in-swift-with-dvr)
    - Unit Testing Core Data Model Layers [:page_facing_up:](http://www.andrewcbancroft.com/2015/01/13/unit-testing-model-layer-core-data-swift/)
- Snapshot Testing
    - iOS Snapshot Test Cases [:pencil2:](https://github.com/facebook/ios-snapshot-test-case)
- Profiling
    - Profiling in Depth [:microphone:](https://developer.apple.com/videos/play/wwdc2015-412) [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2015/412rhea5amj6iaf/412/412_profiling_in_depth.pdf?dl=1)
    - WWDC 2014: Improving you app with instruments [:microphone:](https://developer.apple.com/videos/play/wwdc2014-418/) [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2014/418xxtihju1a7v4/418/418_improving_your_app_with_instruments.pdf)
    - Finding memory leaks with instruments [:page_facing_up:](http://spin.atomicobject.com/2016/01/25/ios-memory-leak-xcode/#.VqaGcF_w1AE.hackernews)
    - What every iOS Developer should be doing with Instruments [:page_facing_up:](https://medium.com/@kazmiekr/what-every-ios-developer-should-be-doing-with-instruments-d1661eeaf64f#.961cmlvx3)
    - Xcode Instruments Documentation [:link:](https://developer.apple.com/library/prerelease/ios/documentation/DeveloperTools/Conceptual/InstrumentsUserGuide/index.html#//apple_ref/doc/uid/TP40004652-CH3-SW1)
- Functional Testing
    - SwiftCheck: QuickCheck for Swift [:pencil2:](https://github.com/typelift/SwiftCheck)
    - More functional testing [:page_facing_up:](http://www.thinkandbuild.it/ios-functional-testing-with-user-stories-uitest-and-local-server/)
- Other
    - Mocking Objects in Swift [:page_facing_up:](http://www.raywenderlich.com/101306/unit-testing-tutorial-mocking-objects)
    - The state of iOS testing in 2015 [:page_facing_up:](http://www.mokacoding.com/blog/ios-testing-in-2015/)
    - How to configure Travis CI for iOS Testing [:page_facing_up:](http://www.mokacoding.com/blog/travis-ci-ios-testing/)
    - Setting up KIF for iOS Acceptance Testing [:page_facing_up:](http://www.mokacoding.com/blog/setting-up-kif-for-ios-acceptance-testing/)
    
[:arrow_up:](#index)

#### **Tools**
- Analyzers
    - Use the static analyzer sith Swift [:page_facing_up:](http://stackoverflow.com/questions/29326036/is-it-not-possible-to-use-analyze-with-swift)
    - Can you use Clang static analyzer with Swift [:page_facing_up:](http://stackoverflow.com/questions/30712090/can-clang-static-analyzer-be-used-with-swift)
- Benchmarking
    - Practicing Swift Benchmarks [:pencil2:](https://github.com/vsco/swift-benchmarks)
- Continuous Integration
    - Using Xcode Bots [:page_facing_up:](http://mjtsai.com/blog/2016/02/11/using-xcode-bots/)
    - Continuous Integration for Xcode 6 [:microphone:](https://developer.apple.com/videos/play/wwdc2014/415/)
- Code Coverage
    - Swift Code Coverage [:pencil2:](https://github.com/realm/SwiftCov)
    - Continuous Integration and Code Coverage In Xcode [:pencil:](https://gist.github.com/rbobbins/92e2fd3736f842d4ccee)
    - Code Coverage Xcode 7 [:page_facing_up:](http://mgrebenets.github.io/mobile%20ci/2015/09/21/code-coverage-for-ios-xcode-7/)
- Debugging Tools
    - Profiling Swift Tool [:page_facing_up:](http://irace.me/swift-profiling/)
    - Profiler formatter xcpretty [:pencil2:](https://github.com/larslockefeer/xcpretty-profiler-formatter)
    - Atom Swift Debugger [:pencil2:](https://github.com/aciidb0mb3r/atom-swift-debugger)
- Delivery Tools
    - Continuous Delivery with Fastlane [:microphone:](https://vimeo.com/146505670)
    - Ship C code with Swift packages using Swift package manager [:page_facing_up:](http://ankit.im/swift/2015/12/27/ship-c-code-with-swift-packages-using-swift-package-manager/)
    - Codeship iOS [:pencil2:](https://github.com/beanieboi/codeship-ios)
- Development Tools
    - Jazzy Docs [:page_facing_up:](https://github.com/realm/jazzy) [:floppy_disk:](https://speakerdeck.com/jpsim/overview-of-jazzy-soulful-docs-for-swift)
- Docker Tools
    - How to run Swift within a Docker container [:page_facing_up:](https://developer.ibm.com/swift/2015/12/15/running-swift-within-docker/)
    - Docker Swift [:pencil2:](https://github.com/swiftdocker/docker-swift)
    - A Swift 2.2+ & Blackfish Docker [:pencil2:](https://github.com/boostcode/docker-swift-git)
- Server Tools
    - Heroku Buildpack for Swift [:pencil2:](https://github.com/kylef/heroku-buildpack-swift)
- Swift Tools
    - Exploring Graph Theory with OmniGraffle and Swift [:page_facing_up:](http://www.mattrajca.com/2015/05/22/exploring-graph-theory-with-omnigraffle-and-swift.html)
    - Swift Environment [:pencil2:](https://github.com/kylef/swiftenv)
- Xcode Tools
    - Alcatraz Master Repository [:pencil2:](https://github.com/alcatraz/Alcatraz)
    - Cocoa Layout Instrument [:page_facing_up:](https://www.bignerdranch.com/blog/inpecting-auto-layout-with-the-cocoa-layout-instrument/)
    - IBAnimatable [:pencil2:](https://github.com/JakeLin/IBAnimatable)
    - Draw in Interface Builder [:pencil2:](https://github.com/ipraba/EPShapes)
    - VVDocumenter [:pencil2:](https://github.com/onevcat/VVDocumenter-Xcode)
    - Analytics workflow in Swift [:pencil2:](https://github.com/brianmichel/Swift-Analysis-Workflow)
    - Anarchy Swift Build Tools [:pencil2:](https://github.com/AnarchyTools)
    - Refractor Swift Code with Refractorer [:pencil2:](https://github.com/johnno1962/Refactorator)
    - xcbuild Build Tool [:pencil2:](https://github.com/facebook/xcbuild)

[:arrow_up:](#index)

#### **Weird Swift**
- WWDC 2014: Advanced Swift [:microphone:](https://developer.apple.com/videos/play/wwdc2014-404/) [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2014/404xxdxsstkaqjb/404/404_advanced_swift.pdf)
+ Other Swift Attributes you may not have heard of [:page_facing_up:](http://www.russbishop.net/more-swift-attributes)
- Hipster Swift [:page_facing_up:](http://krakendev.io/blog/hipster-swift)
- Namespaces in Swift [:page_facing_up:](http://andybargh.com/2016/01/21/lifetime-scope-and-namespaces-in-swift/)
- Swift Literal Convertibles [:page_facing_up:](http://nshipster.com/swift-literal-convertible/)
- What is the difference in Swift between 'unowned(safe)' and 'unowned(unsafe)'? [:page_facing_up:](http://stackoverflow.com/questions/26553924/what-is-the-difference-in-swift-between-unownedsafe-and-unownedunsafe)
- UnsafePointer [:page_facing_up:](http://en.swifter.tips/unsafe/)
- UnsafeMutablePointer [:page_facing_up:](http://sketchytech.blogspot.com/2014/10/becoming-less-afraid-of-unsafe-mutable.html)
- COPaquePointer and CFunctionPointer [:page_facing_up:](http://en.swifter.tips/opaque-function-pointer/)
- How to Dereference an Unsafe Mutable Pointer in Swift [:page_facing_up:](http://useyourloaf.com/blog/how-to-dereference-an-unsafe-mutable-pointer-in-swift/)
- Pointers, Pointer Arithmetic, and Raw Data in Swift [:page_facing_up:](http://stackoverflow.com/questions/24067085/pointers-pointer-arithmetic-and-raw-data-in-swift)
- Swift Method Dispatching [:page_facing_up:](http://allegro.tech/2014/12/swift-method-dispatching.html)
- Global variables in Swift are not variables [:page_facing_up:](http://railsware.com/blog/2014/06/11/global-variables-in-swift-are-not-variables/)
- Raw​Option​Set​Type [:page_facing_up:](http://nshipster.com/rawoptionsettype/)

[:arrow_up:](#index)

## **iOS Programming with Swift**

#### **Application Structure / Architecture**
- Elm Like Architecture
    - Elmification of Swift [:page_facing_up:](https://medium.com/design-x-code/elmification-of-swift-af14b7f92b30#.k1njpy7sn)
    - Simple model for elm-like composable programs [:pencil2:](https://github.com/davidcairns/AppComponents)
    - Swift Elm [:pencil2:](https://github.com/momentumworks/swift-elm)
- Functional
    + Functional View Controllers [:page_facing_up:](http://chris.eidhof.nl/posts/functional-view-controllers.html) [:pencil:](https://gist.github.com/chriseidhof/244f1a9c8a39a4c809f9)
- Massive View Controllers
    - Refractor the Mega Controller [:microphone:](https://realm.io/news/andy-matuschak-refactor-mega-controller/)
    - Preventing Massive View Controllers [:microphone:](https://www.youtube.com/watch?v=dgOdsh1Bq10&feature=youtu.be&list=PLy2fR8K1ngurocVMEL0qHn0ik2MDYewLJ) 
    - Destroying Massive View Controllers [:page_facing_up:](http://khanlou.com/2015/12/massive-view-controller/) with patterns [:page_facing_up:](https://medium.com/ios-os-x-development/humble-object-pattern-in-swift-de5efe8fe05a#.iyh62t857)
    - Lighter View Controllers in Swift [:page_facing_up:](https://www.codefellows.org/blog/tech-tip-clean-up-your-code-with-lighter-view-controllers-in-swift) [:pencil:](https://gist.github.com/lostincode/38e6b0a612a3b33f6f7b)
    - View Controller Thinning [:page_facing_up:](http://puchka.me/view-controller-thinning/) via Dependency Injection [:page_facing_up:](http://puchka.me/view-controller-thinning-dependency-injection/) 
    - Consistent, Thin, & Dumb: Redesigning the Spotify iOS App [:microphone:](https://realm.io/news/mbltdev-hector-zarate-consistent-thin-dumb-spotify/)
- Model Layer and Caching
    - How to cache view controllers in iOS [:page_facing_up:](https://medium.com/@gitter/how-to-cache-view-controllers-in-ios-854be6734062#.lownd94t5)
    - Awesome Cache [:pencil2:](https://github.com/aschuch/AwesomeCache)
    - SwiftyDB [:pencil2:](https://github.com/Oyvindkg/swiftydb)
    - A Structy Model Layer [:page_facing_up:](http://khanlou.com/2015/12/a-structy-model-layer/)
- Model View Whatever
    - iOS Architecture Patterns [:page_facing_up:](https://medium.com/the-traveled-ios-developers-guide/architecture-patterns-in-ios-part-1-8d4ad146c266#.wexkb2ofi) [:page_facing_up:](https://medium.com/the-traveled-ios-developers-guide/architecture-patterns-in-ios-part-2-fac1180e0251#.f0ckrnpxp) [:page_facing_up:](https://medium.com/the-traveled-ios-developers-guide/architecture-patterns-in-ios-part-3-231f82cbb781#.kbuhsnk3t)
    - Clean Architecture in Swift [:pencil2:](https://github.com/marcinkuptel/clean-architecture)
    - Demystifying iOS Architecture Patterns [:page_facing_up:](https://medium.com/ios-os-x-development/ios-architecture-patterns-ecba4c38de52#.5zn7t5oh2)
    + MVVM in Swift [:page_facing_up:](http://artsy.github.io/blog/2015/09/24/mvvm-in-swift/) [:page_facing_up:](http://khanlou.com/2015/12/mvvm-is-not-very-good/) [:page_facing_up:](https://ashfurrow.com/blog/mvvm-is-exceptionally-ok/) [:page_facing_up:](http://gilesvangruisen.com/mvvm-swift/)
    - Stateful View Controller [:pencil2:](https://github.com/aschuch/StatefulViewController)
    - An MVP Framework [:pencil2:](https://github.com/Karumi/BothamUI)
    - Designing App Infrastructure [:page_facing_up:](https://medium.com/@gitdoapp/gitdo-designing-the-app-infrastructure-3b7710c0fd81#.mf5kc58vj)
- Viper
    - 250 Days of using VIPER Architecture with Swift [:microphone:](https://realm.io/news/altconf-brice-pollock-250-days-shipping-with-swift-and-viper/)
    - Safer with VIPER [:page_facing_up:](https://medium.com/ios-os-x-development/safer-uiviewcontroller-creation-when-using-storyboards-1915ac2b2c80#.bynj7y4gd)
- Unidirectional Data Flow
    - Ziggurat iOS App Architecture [:page_facing_up:](https://corner.squareup.com/2015/12/ziggurat-ios-app-architecture.html) 
    - One Way Data Flow Architecture in Swift [:microphone:](https://www.youtube.com/watch?v=4cP1p5VOrSI)
    - Unidirectional Dataflow Architecture with Swift-Flow [:microphone:](https://realm.io/news/benji-encz-unidirectional-data-flow-swift/) [:pencil2:](https://github.com/Swift-Flow/Swift-Flow) [:floppy_disk:](https://speakerdeck.com/benjamin_encz/unidirectional-data-flow-in-swift)
    - ReSwift Unidirectional Data Flow [:pencil2:](https://github.com/ReSwift) [:page_facing_up:](http://christiantietze.de/posts/2016/01/reswift-level-indirection/)
    - CocoaFlow Architecture [:page_facing_up:](http://www.skilled.io/paulyoung/cocoaflow)
    - Improve your iOS Architecture with FlowControllers [:page_facing_up:](http://merowing.info/2016/01/improve-your-ios-architecture-with-flowcontrollers/)
    - Explaining Flux data flow in Swift [:pencil:](https://gist.github.com/rjchatfield/d78cca1bf7b02323bad9)
    - ReduxKit is a predictable state container for Swift apps [:page_facing_up:](https://github.com/ReduxKit/ReduxKit) [:pencil:](https://gist.github.com/rjchatfield/27e3d8ef2249a4298046#file-statereduce-swift) [:pencil2:](https://github.com/ReduxKit)
    - State Machines in Swift [:pencil2:](https://github.com/ReactKit/SwiftState) [:floppy_disk:](https://github.com/tangphillip/state-machine-talk)
    + Uber Jetstream [:pencil2:](https://github.com/uber/jetstream-ios)
    - Building a Unidirectional Data Flow app with Realm [:page_facing_up:](https://realm.io/news/unidirectional-data-flow-in-swift/)

[:arrow_up:](#index)

#### **Core Data and Realm**
- Core Data
    - What's New in Core Data [:microphone:](https://developer.apple.com/videos/play/wwdc2015-220) [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2015/220lgx5lvphj2/220/220_whats_new_in_core_data.pdf?dl=1)
    - Pragmatic Core Data [:microphone:](https://vimeo.com/146505672)
    - Getting Started with Core Data [:page_facing_up:](http://www.raywenderlich.com/115695/getting-started-with-core-data-tutorial)
    - Core Competencies [:page_facing_up:](https://developer.apple.com/library/ios/documentation/DataManagement/Devpedia-CoreData/coreDataStack.html#//apple_ref/doc/uid/TP40010398-CH25-SW1)
    + A Swift Into To Core Data [:page_facing_up:](https://github.com/andyshep/CoreDataPlayground)
    + Moving from ObjC to Swift with Core Data [:page_facing_up:](http://martiancraft.com/blog/2015/07/objective-c-swift-core-data/)
    + What, if any, ACID gurantees does Core Data Make? [:page_facing_up:](http://stackoverflow.com/questions/6634731/what-if-any-acid-guarantees-can-core-data-provide-on-ios)
    + Core Data Libraries and NSKeyedArchiver [:page_facing_up:](http://nshipster.com/core-data-libraries-and-utilities/)
    - Ditching Core Data for Something else [:page_facing_up:](https://medium.com/the-way-north/ditching-core-data-865c1bb5564c#.24t5a9t8t)
    - Comparing Core Data Stacks [:page_facing_up:](http://floriankugler.com/2013/04/29/concurrent-core-data-stack-performance-shootout/)
    - Using Core Data with Swift [:microphone:](https://realm.io/news/jesse-squires-core-data-swift/)
    - Better Core Data Models with Swift [:page_facing_up:](http://www.jessesquires.com/better-coredata-models-in-swift/)
    - Core Data in 2015 and Magical Record in Swift [:microphone:](https://www.youtube.com/watch?v=1jSuXbeIKuk&list=PLEx5khR4g7PL0fDNJkI2dHhqeckQTAbes&index=46)
    - Core Data Threading Demystified [:microphone:](https://realm.io/news/marcus-zarra-core-data-threading/)
    - My Core Data Stack [:page_facing_up:](http://martiancraft.com/blog/2015/03/core-data-stack/) [:pencil:](https://gist.github.com/Ben-G/54f363482303b984574b)
    - Core Data Tutorial Series [:link:](http://code.tutsplus.com/series/core-data-and-swift)
    - Core Data Fundamentals: Exploring the Core Data Stack [:page_facing_up:](http://bartjacobs.com/core-data-fundamentals-core-data-stack/)
    - Pragmatic Core Data [:microphone:](https://realm.io/news/cocoaheads-florian-kugler-pragmatic-core-data/)
    - Core Data Migrations Tutorial [:page_facing_up:](http://www.raywenderlich.com/114084/core-data-migrations-tutorial-lightweight-migrations)
    - Multiple Managed Object Contexts [:page_facing_up:](http://www.raywenderlich.com/113489/core-data-tutorial-multiple-managed-object-contexts)
- Realm
    - Super simple Realm Intro [:page_facing_up:](https://littlebitesofcocoa.com/49-realm-basics) [:floppy_disk:](https://speakerdeck.com/jpsim/realm-in-swift) [:page_facing_up:](http://theiostimes.com/advent-calendar/realm.html)
    - Why Realm over Core Data? [:page_facing_up:](https://www.quora.com/Why-would-you-use-Realm-over-Core-Data) [:floppy_disk:](https://speakerdeck.com/realm/why-realm)
    - Official Realm Introduction [:page_facing_up:](https://realm.io/news/introducing-realm/)
    - Realm Tutorial [:page_facing_up:](http://www.raywenderlich.com/81615/introduction-to-realm)
    - Why Realm is great and why we're not going to use it [:page_facing_up:](http://bsktapp.com/blog/why-is-realm-great-and-why-are-we-not-using-it/)
    - Realm Best Practices [:page_facing_up:](http://stackoverflow.com/questions/31590717/proper-realm-usage-patterns-best-practices)
    - Realm Repo [:page_facing_up:](https://github.com/realm/realm-cocoa)
    - Reddit Thread [:page_facing_up:](https://www.reddit.com/r/iOSProgramming/comments/2vmbv2/realm_or_coredata/)
    - A look into Realm's Core DB Engine [:microphone:](https://realm.io/news/jp-simard-realm-core-database-engine/)
    - Working with Realm [:page_facing_up:](http://blog.matthewcheok.com/working-with-realm/)
    - Testing Realm Apps [:page_facing_up:](http://www.mokacoding.com/blog/testing-realm-apps/)
    - Looking at Realm's Core DB Engine [:floppy_disk:](https://speakerdeck.com/jpsim/a-look-into-realms-core-db-engine)
    - Realm Incremental Store [:pencil2:](https://github.com/eure/RealmIncrementalStore)

[:arrow_up:](#index)

#### **UI**
- Animations
    - AdaptiveUI Animations [:microphone:](https://realm.io/news/gotocph-sam-davies-adaptive-ui-ios/)
    - Animating VCs [:page_facing_up:](http://www.raywenderlich.com/110536/custom-uiviewcontroller-transitions)
    - Transition Treasury Lib [:pencil2:](http://transitiontreasury.com/)
    - Animations with CAReplicationLayer [:page_facing_up:](http://www.ios-animations-by-emails.com/posts/2015-march)
    - Building a hamburger button transition [:page_facing_up:](http://robb.is/working-on/a-hamburger-button-transition/)
    - Advanced Graphics and Animations for iOS Apps [:page_facing_up:](https://developer.apple.com/videos/play/enterprise-419/)
- Autolayout
    - iOS Animations with AutoLayout [:microphone:](https://realm.io/news/gotocph-marin-todorov-auto-layout-animations-ios/) and [:pencil2:](https://github.com/sammyd/AdaptiveUI-GOTOConf) [:page_facing_up:](https://littlebitesofcocoa.com/9-animating-constraints)
    - Cartography Autolayout DSL [:pencil2:](https://github.com/robb/Cartography)
    - How to configure a UIScrollView with Auto Layout in Interface Builder [:page_facing_up:](http://mokagio.github.io/tech-journal/2015/06/24/ios-scroll-view-and-interface-builder.html)
- CollectionViews
    - What's new in Table and Collection Views [:microphone:](https://developer.apple.com/videos/play/enterprise-226/)
    - Advanced Collection Views [:microphone:](http://devstreaming.apple.com/videos/wwdc/2014/232xxz8gxpbstio/232/232_advanced_user_interfaces_with_collection_views.pdf)
- Core Graphics
    - Core Graphics Tutorial [:page_facing_up:](http://www.raywenderlich.com/90690/modern-core-graphics-with-swift-part-1)
- Core Image
    - Core Image Blog [:notebook:](http://flexmonkey.blogspot.com/)
- Presenting
    - Swifty View Controller Presenters [:microphone:](https://realm.io/news/slug-jesse-squires-swifty-view-controller-presenters/)
- TableViews
    - Advanced UITableViews [:microphone:](https://realm.io/news/altconf-mason-glidden-advanced-uitableviews-for-fun-and-profit/) [:page_facing_up:](http://www.martinrichter.net/blog/2015/12/30/animating-table-row-changes-using-changesets-with-mvvm/)
    - UITableView Configuration Values [:page_facing_up:](https://www.objc.io/blog/2015/02/16/functional-snippet-20-configuration-values/)
    - Typed TableViewControllers [:page_facing_up:](https://www.objc.io/blog/2015/02/23/functional-snippet-21-typed-table-view-controllers/) [:page_facing_up:](https://www.objc.io/blog/2015/03/02/functional-snippet-22-typed-table-view-controllers-redux/) [:pencil:](https://gist.github.com/chriseidhof/892c1a574d1f3975c697) [:page_facing_up:](http://holko.pl/2016/01/05/typed-table-view-controller/)
    - Using Generators for UITableView Pagination Purposes [:page_facing_up:](http://blog.krzyzanowskim.com/2015/06/26/paging/)
- SpriteKit and Metal
    + Mixing SpriteKit with UIKit in iOS 9 [:page_facing_up:](https://littlebitesofcocoa.com/8-mixing-spritekit-into-uikit)
    - SpriteKit as an intro to SceneKit [:floppy_disk:](https://speakerdeck.com/bklnswift/joseph-mcmahon-spritekit-as-an-intro-to-scenekit-and-metal)
    - Metal and Swift [:microphone:](https://realm.io/news/swift-summit-simon-gladman-metal/)
    - Why use SpriteKit? [:page_facing_up:](https://www.quora.com/Which-tools-are-you-using-with-SpriteKit)
    - 3D Graphics with Metal in Swift [:microphone:](https://realm.io/news/3d-graphics-metal-swift/)
- UIKit
    - UIKit for the Mac, rewritten in Swift [:pencil2:](https://github.com/unifiedh/Chameleon-Swift)
    - Did Apple implement UIKit and Cocoa classes "Obj-C on Swift" [:page_facing_up:](https://www.quora.com/Did-Apple-implement-UIKit-and-Cocoa-classes-Obj-C-on-Swift-or-Swift-on-Obj-C-or-did-they-write-the-whole-thing-twice?srid=xrLC&share=59c4c728)
    - Cocoa Touch Best Practices [:pencil:](https://gist.github.com/rbobbins/236b2160ab9621f3f8e7)
    - How Do You Do UIView<SomeProtocol> in Swift? [:page_facing_up:](http://nearthespeedoflight.com/article/2016_02_18_how_do_you_do_uiview_someprotocol__in_swift)

[:arrow_up:](#index)

#### **Web Services, JSON, Routing, REST, and Networking**
+ Networking
    - AlamoFire Tutorial [:page_facing_up:](http://www.raywenderlich.com/121540/alamofire-tutorial-getting-started)
    + SwiftHTTPStatusCodes [:pencil:](https://github.com/rhodgkins/SwiftHTTPStatusCodes)
    + Calling a REST Api in Swift [:page_facing_up:](http://stackoverflow.com/questions/24321165/make-rest-api-call-in-swift)
    + How to Make REST API Calls and Parse JSON with Swift [:page_facing_up:](http://devdactic.com/rest-api-parse-json-swift/)
    + HTTP in Swift [:page_facing_up:](https://medium.com/swift-programming/http-in-swift-693b3a7bf086)
    + Reachability Library [:page_facing_up:](https://github.com/ashleymills/Reachability.swift)
    - NSURLSession Basics [:page_facing_up:](https://littlebitesofcocoa.com/78-nsurlsession-basics) [:page_facing_up:](http://www.splinter.com.au/2015/06/12/swift-nsurlsession-wrapper/) [:page_facing_up:](http://www.raywenderlich.com/110458/nsurlsession-tutorial-getting-started)
    - Background Downloads [:page_facing_up:](https://littlebitesofcocoa.com/77-background-downloads)
    - An introduction to using Alamofire [:page_facing_up:](http://nshipster.com/alamofire/)
    - Moya: Network Abstraction Layer written in Swift [:pencil2:](https://github.com/Moya/Moya)
    - Network data as a Struct [:page_facing_up:](http://chris.eidhof.nl/posts/struct-semantics-in-swift.html)
    - Your app and next generation networks [:microphone:](https://developer.apple.com/videos/play/wwdc2015/719/)
- JSON 
    - Functional JSON Parsing with Tyro [:pencil2:](https://github.com/typelift/Tyro)
    - { JSON, Swift, and Type Safety } [:floppy_disk:](https://speakerdeck.com/swiftsummit/anthony-levings-json-swift-and-type-safety-its-a-wrap)
    - JSON in Swift [:page_facing_up:](http://blog.matthewcheok.com/json-and-swift/)
    - Functional JSON Parsing [:page_facing_up:](http://owensd.io/2014/08/06/functional-json.html)
    + Swift and JSON: Are we doing it right? [:microphone:](https://skillsmatter.com/skillscasts/6202-swift-and-json-are-we-doing-it-right)
    + Calling APIs and Parsing JSON with Swift [:page_facing_up:](https://www.topcoder.com/blog/calling-apis-parsing-json-with-swift/) [:page_facing_up:](http://www.raywenderlich.com/82706/working-with-json-in-swift-tutorial)
    + Parsing Embedded JSON and Arrays in Swift [:page_facing_up:](https://robots.thoughtbot.com/parsing-embedded-json-and-arrays-in-swift)
    + Real World JSON Parsing [:page_facing_up:](https://robots.thoughtbot.com/real-world-json-parsing-with-swift)
    + Efficient JSON Parsing with Functional Concepts [:page_facing_up:](https://robots.thoughtbot.com/efficient-json-in-swift-with-functional-concepts-and-generics)
    - Operator Overloading and JSON Parsing in Swift [:page_facing_up:](https://realm.io/news/swift-thinking/)
    - Swift JSON [:pencil2:](https://github.com/dankogai/swift-json)
+ Routing 
    - An AlamoFire Router [:page_facing_up:](https://littlebitesofcocoa.com/93-creating-a-router-for-alamofire)
    - Write Your Own API Clients [:page_facing_up:](https://thatthinginswift.com/write-your-own-api-clients-swift/)
+ Web Services
    + CloudKit Introduction [:page_facing_up:](http://szulctomasz.com/cloudkit-introduction-and-lets-build-an-app/s)
    + Create a Data Access Layer with SQLite.swift and Swift 2 [:page_facing_up:](http://masteringswift.blogspot.com/2015/09/create-data-access-layer-with.html)
    + Using YapDatabase [:page_facing_up:](https://github.com/yapstudios/YapDatabase)
    - MagicalRecord loves Swift [:microphone:](http://gotocon.com/dl/goto-cph-2015/slides/SaulMora_CoreDataIn2015andMagicalRecordMeetsSwift.pdf)
    - Swift-MongoDB [:pencil2:](https://github.com/Danappelxx/SwiftMongoDB)
    - Caramel brings powerful, expressive I/O to Swift [:microphone:](https://realm.io/news/steve-streza-caramel-for-swift/)

[:arrow_up:](#index)

## **Mac Programming with Swift**

## **WatchOS Programming with Swift** 

## **tvOS Programming With Swift**

## **Xcode**
- About
    - Xcode Core Concepts [:page_facing_ups:](https://developer.apple.com/videos/play/wwdc2013/401/)
- Build System
    - The Xcode Build System [:page_facing_up:](https://pewpewthespells.com/blog/xcode_build_system.html)
    - Xcode Build Settings Reference [:page_facing_up:](https://pewpewthespells.com/blog/buildsettings.html)
- Interface Builder
    - Implementing UI Designs in Interface Builder [:pencil:](https://gist.github.com/rbobbins/9e9a478fcd1803acef39)
    - Integrating Designs through IB [:microphone:](https://developer.apple.com/videos/play/wwdc2015/407/)
    - IBInspectable / IBDesignable [:page_facing_up:](http://nshipster.com/ibinspectable-ibdesignable/)

## **Interview Questions**
+ Ray Wenderlich [:clipboard:](http://www.raywenderlich.com/110982/swift-interview-questions-answers)
+ Toptal [:clipboard:](http://www.toptal.com/swift/interview-questions)
+ LeetCode [:clipboard:](https://github.com/diwu/LeetCode-Solutions-in-Swift)
+ Coding Questions [:clipboard:](https://github.com/CameronBanga/iOS-Developer-and-Designer-Interview-Questions#code)
+ :fire: Awesome Swift Interview Questions [:clipboard:](https://github.com/MaximAbramchuck/awesome-interviews#swift)
+ :fire: Awesome iOS Interview Questions [:clipboard:](https://github.com/MaximAbramchuck/awesome-interviews#ios)

[:arrow_up:](#index)

## Emoji Key
- :pencil: = Gist
- :pencil2: = Repository
- :notebook: = Blog
- :page_facing_up: = Blog Post
- :scroll: = Quick Reference
- :books: = Book
- :book: = Guide Book
- :newspaper: = Newsletter
- :floppy_disk: = Slides
- :microphone: = Video Presentation
- :video_camera: = Video
- :link: = Link
- :fire: = Awesome List
- :mortar_board: = Learning Resource
- :clipboard: = Interview Questions
- :radio: = Podcast

[:arrow_up:](#index)

## **Shoutouts**
Shoutout to [@clattner_llvm](https://twitter.com/clattner_llvm?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor), the OG Swift Developer. Shoutout to [@chriseidhof](https://twitter.com/chriseidhof) for encouraging me to promote this idea and for being a huge baller. Shoutout to [@ashfurrow](https://twitter.com/ashfurrow) and [@bennRodri](https://twitter.com/bennRodri) for being so incredibly helpful. Shoutout to [@CodaFi_](https://twitter.com/CodaFi_), the [TypeLift](https://github.com/typelift), and the [AntiTypical](https://github.com/antitypical) teams for promoting FP. Shoutout to [Elm Trailblazers](https://twitter.com/czaplic?lang=en). Shoutout to [Haskell Devs](http://dev.stephendiehl.com/hask/) and [Category Theory legends](https://ncatlab.org/nlab/show/computer+science). Shoutout to [FutureKit](https://github.com/FutureKit/FutureKit). And finally, Shoutout to all the Swift Programmers out there, this project is __by you and for you!__

[:arrow_up:](#index)

 