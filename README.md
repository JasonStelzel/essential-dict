# essential-dict
Glossary of Terms for the Essential Developers Course


CLASS METHOD - See TYPE METHOD


COLLABORATOR - 


DEPENDENCY INJECTION (DI) - The means by which we pass the minimally needed object reference (often some class/struct object with a group of properties/methods or functions, for convenience) into another context.  Here are 3 examples of Dependency Injection:

    1.  let sut = RemoteFeedLoader(client: client) // Constuctor Injection (setting the client as part of the construction of a sut)

    2.  sut.client = client // Property Injection (setting the client property directly on the sut)

    3.  sut.load(client: client) // Method Injection (passing the client to the method as it is called)
    

FeedItem - 


GLOBAL SHARED INSTANCE - 


HTTPClient - 


MEMORY LEAK (preventing) - https://www.essentialdeveloper.com/articles/the-minimum-you-should-do-to-prevent-memory-leaks-in-swift


MOCKING - Replacing any source of input, process or output with a "faked", or "mocked" version which would then facilitate the testing of code or operation of an app without backend or other necessary services.


MVC -> MVVM (refactor) - https://academy.essentialdeveloper.com/courses/1112681/lectures/34676373


RemoteFeedLoader - 


SPY - A type that can be rendered in any of several different forms used to collect or set values in a running app for the purpose of testing and/or verifying code.


STATIC METHOD - See TYPE METHOD


STUB - Putting known values in place of run-time or computed values whenever run-time/computed values would be unavailable, timeconsuming to obtain (hence making the testing code slow to run), or otherwise inconvenient to use.


SUT - System Under Test


TEST DOUBLE - 


TEST TYPES - UI Testing, Unit Tests, Integration Tests and End-to-End Tests. Apple WWDC Videos on testing:
https://developer.apple.com/videos/play/wwdc2015/406
https://developer.apple.com/videos/play/wwdc2017/409
https://developer.apple.com/videos/play/wwdc2018/417


TYPE METHOD - static and class methods are *type methods* that can be called on the type itself (instead of an instance of that type). The difference between these two is that class methods can be overridden by subclasses while static methods cannot. Both of these kinds of methods are called type methods. You indicate type methods by writing the static keyword before the method’s func keyword. Classes can use the class keyword instead, to allow subclasses to override the superclass’s implementation of that method. In contrast, Instance methods are methods that you call on an *instance* of a particular type. https://docs.swift.org/swift-book/LanguageGuide/Methods.html

