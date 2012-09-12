enjoyable-ios-testing
=====================

Enjoyable unit testing is still a bit elusive for me on iOS.

I also like modularization.

This project is a journey toward creating reusable Objective-C modules that are well tested.

I'm seeking:

* good integration with Xcode

* a strong community

* headless runner is a plus

* unit testing now, functional and automated UI testing later

* create stand-alone modules which include tests

## Creating a new module with unit tests

Using Xcode version 4.4.1

### Creating a static library

In Xcode, create a new library to house your code and tests:

        File > New Project > iOS > Framework & Library > Cocoa Touch Static Library

### Unit tests

OCUnit tests are created by default.

## Research

* The [Test-Driven iOS Development](http://itunes.apple.com/us/book/test-driven-ios-development/id516930513?mt=11) book by Graham Lee has been recommended.

* After reading through a recent [review of some of the frameworks](http://paulsolt.com/2010/11/iphone-unit-testing-explained-part-1/) it seems like giving the built-in OCUnit a try is a way to go. GHUnit is also popular, but takes a bit more to integrate in.

* If you're a mockist, [OCMock](http://ocmock.org) seems like the only choice to make there. A recent article: [Adding OCMock to Xcode 4 Projects](http://def.reyssi.net/blog/2012/03/23/using-ocmock-with-xcode4). A bit older, but also a good resources: [Making Fun of Things with OCMock](http://alexvollmer.com/posts/2010/06/28/making-fun-of-things-with-ocmock/) and links to [Mocks Aren't Stubs](http://martinfowler.com/articles/mocksArentStubs.html)

* There are also some useful frameworks by [The Omni Group](http://www.omnigroup.com/company/developer/).

* Videos on [ideveloper.tv](http://ideveloper.tv)

