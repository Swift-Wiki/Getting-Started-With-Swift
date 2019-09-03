Learning Swift
================

Swift is a language we use to give a computer instructions. Once you know at least its basics, you can leverage many of the available frameworks and technologies to create incredible things.

**Don't assume just because you've been able to use Swift to develop in the past, that you know everything there is to know.** This guide (while still incomplete) is intended to get you started learning *all* of the aspects of Swift.

**Topics**

The list of resources for each of these topics are never going to be exaustive. Take it upon yourself to do your own research (through a good old-fashioned internet search) on top of the resources we have listed here.

- [High Level Overviews](#high-level-overviews)
- [Constants & Variables](#constants--variables)
- [Collections](#collections)
- [Optionals](#optionals)
- [Functions](#functions)
- [Types – Structs, Classes, and Enums](#types--structs-classes-and-enums)
- [Functional Programming](#functional-programming)
- [Protocols and Generics](#protocols-and-generics)
- [Memory Management](#memory-management)
- [Error Handling](#error-handling)
- [Debugging](#debugging)
- [Design Patterns](#design-patterns)
- [Efficiency](#efficiency)

High Level Overviews
---------------

### Documentation
- [ ] [Swift.org](https://swift.org/getting-started/) – The creators of Swift have put together an enormous amount of great documentation themselves.
    - [Guided Tour](https://docs.swift.org/swift-book/GuidedTour/GuidedTour.html) – A quick tour through the language
    - [The Basics](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html) – A much more detailed look through the vast majority of Swift features.
    - [API Design Guidlines](https://swift.org/documentation/api-design-guidelines/) – Guidlines to write Swift code like everyone else in the community so you can collaborate/ask questions much more easily.

### Books
- [ ] [The Swift Programming Language](https://itunes.apple.com/us/book-series/swift-programming-series/id888896989?mt=11) – A book Apple wrote to learn Swift.
- [ ] [Learning Swift - Second Edition](https://www.amazon.com/Learning-Swift-Second-Andrew-Wagner/dp/1785887513) – A little out dated, but still a valuable introduction into the most important parts of Swift and good programming practices.
- [ ] [Swift Programming: The Big Nerd Ranch Guide](https://www.bignerdranch.com/books/swift-programming-the-big-nerd-ranch-guide-second-edition/) – Whether you’re new to programming or an experienced developer, Swift Programming: The Big Nerd Ranch Guide will teach you what you need to know about Apple’s newest language.

### If you have an iPad
- [ ] [Swift Playgrounds](https://www.apple.com/swift/playgrounds/) – An iPad app full of tutorials for learning Swift

## If you have an iPhone
- [ ] [Unwrap](https://apps.apple.com/us/app/unwrap/id1440611372) – App to learn Swift right on  your iPhone

### Blogs
- [ ] [Getting Started with Swift](https://drewag.me/posts/2014/07/13/getting-started-with-swift) – A quick overview of core concepts you need to learn.

### Videos
- [ ] [Swift WWDC Lectures](https://developer.apple.com/videos/developer-tools/swift/) – Vast amount of lectures directly from Apple developers
- [ ] [Introduction to iOS 11, Xcode 9 and Swift 4](https://www.youtube.com/watch?v=71pyOB4TPRE) – The intro video to the Stanford's beginner video course.

Constants & Variables
-----------

The fundemental way we track information in Swift.

Collections
-----------

There are serverl different standard containers that help organize multiple variables together such as Arrays, Dictionaries, and Tuples.

Control Flow
-----------

The air traffic control of information through our programs. We do this with conditionals, switches, loops, guard statements and more.

Optionals
-----------

Sometimes we want our variables to be able to store the concept of “nothing” instead of “something”.

- [ ] [What is an Optional in Swift](https://drewag.me/posts/2014/07/05/what-is-an-optional-in-swift)
- [ ] [Uses for Implicitly Unwrapped Optionals](https://drewag.me/posts/2014/07/05/uses-for-implicitly-unwrapped-optionals-in-swift)

Functions
-----------

The most basic way to organize code into reusable chunks.

Types – Structs, Classes, and Enums
-----------

A step beyond functions for organizing code into reusable chunks.

Functional Programming
-----------

The use of closures with functions like filter, map, reduce, sort, zip, and more for another way to think about code (imperative v.s. declaritive).

Protocols and Generics
-----------

Make more advanced use of Swift's type system to be more expressive in your code and let the compiler catch more bugs for you.

Memory Management
-----------

Even in the modern age, we need to have a sense of how data is managed the working memory of our programs. Otherwise, our programs will become sluggish and most likely crash eventually.

Error Handling
-----------

We can't only program for the best-case scenario. We must be able to produce and handle errors.

Debugging
-----------

How to fix your own problems by analyzing what is currently happnening in your code.

Design Patterns
-----------

Programming is more than just getting the job done. It is an art and a science. Learn how to write more reliable and maintainable code. These techniques apply to all programming languages.

These are just a tiny fraction of the patterns out there.

### Behavioral
- [Iterator](https://en.wikipedia.org/wiki/Iterator_pattern) – Traverse a container to access its elements.
- [Observer](https://en.wikipedia.org/wiki/Observer_pattern) – Ability for one object to be notified of the changes to another.

### Structural
- [Composite](https://en.wikipedia.org/wiki/Composite_pattern) – Group of objects treated as a single instance of the same object.
- [Model View Controller](https://developer.apple.com/library/archive/documentation/General/Conceptual/CocoaEncyclopedia/Model-View-Controller/Model-View-Controller.html)

### Creational Patterns
- [Singleton](https://en.wikipedia.org/wiki/Singleton_pattern) – Restrict the instanation of a type to a single instance.
- [Factory](https://en.wikipedia.org/wiki/Factory_(object-oriented_programming)) – An object for creating other objects.

Efficiency
-----------

Sometimes at odds with writing maintainable code, it can also be important to write fast and efficient code. Learn about concepts like Big O notation to evaluate the computational complexity of your code.

