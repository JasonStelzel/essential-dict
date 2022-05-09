# essential-dict
Glossary of Terms for the Essential Developers Course


COLLABORATOR - 


DEPENDENCY INJECTION (DI) - The means by which we pass the minimally needed object reference (often some parent class object with a group of properties, for convenience) into another context.  Here are 3 examples of Dependency Injection:

    1.  let sut = RemoteFeedLoader(client: client) // Constuctor Injection (setting the client as part of the construction of a sut)

    2.  sut.client = client // Property Injection (setting the client property directly on the sut)

    3.  sut.load(client: client) // Method Injection (passing the client to the method as it is called)
    

FeedItem - 


GLOBAL SHARED INSTANCE - 


HTTPClient - 


MEMORY LEAK (preventing) - https://www.essentialdeveloper.com/articles/the-minimum-you-should-do-to-prevent-memory-leaks-in-swift


MOCKING - Replacing any source of input, process or output with a "faked", or "mocked" version which would then facilitate the testing of code or operation of an app without backend or other necessary services.


RemoteFeedLoader - 


SPY - A type that can be rendered in any of several different forms used to collect or set values in a running app for the purpose of testing and/or verifying code.


STUB - Putting known values in place of run-time or computed values whenever run-time/computed values would be unavailable, timeconsuming to obtain (hence making the testing code slow to run), or otherwise inconvenient to use.


SUT - System Under Test


TEST DOUBLE - 




