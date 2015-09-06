---
layout: post
title:  "NS_ENUM and Swift"
date:   2015-10-30 20:20:15
comments: true
---

In Swift, enumerations are codified as a first-class language construct as fundamental as a struct or class, and include a number of features that make them even more expressive, like raw types and associated values

#####Objective-C Enum Declaration

	typedef NS_ENUM(NSInteger, UITableViewCellStyle) {
	   UITableViewCellStyleDefault,
	   UITableViewCellStyleValue1,
	   UITableViewCellStyleValue2,
	   UITableViewCellStyleSubtitle
	};

#####The same Swift Enum Declaration

	enum UITableViewCellStyle : Int {
	    case Default
	    case Value1
	    case Value2
	    case Subtitle
	};
