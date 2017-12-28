## Title 

Python 2 and 3 compatibility: In a single codebase 

## Duration

30 minutes

## Description 

Although Python 3 is considered the future of Python, Python 2.x will be maintained for several more years, alongside Python 3 which is not backwards compatible with many open source projects and some packages on PYPi still supporting python 2.x because the users of these projects still use python 2.x.

This talk explains clean ways to write code that will run on both Python 2.x and 3.x with examples of how to convert existing Python 2-compatible code to code that will run reliably on both Python 2.x and 3.x.

Developers working on either small, medium, or large projects will appreciate the explanations, detailed examples, and clean techniques to help them extend support for both versions to their existing Python 2-compatible projects.

The talk will give insight into the content in the book Python 2 and 3 Compatibility that will available in October but be released in paper backs in January 2018 by Apress.
 

## Who and why

Professional Python developers and enthusiasts that want to implement Python 3 support for their existing Python 2 compatible code
.From the content in this presentation, participants shall understand the syntactical differences between Python 2 and 3, and how
to use Python packages Python-Future and Six to implement neutral compatibility. Developers working on either small, medium, or 
large projects will appreciate theclear explanations, detailed examples, and clean techniques to help them extend support for 
both versions to their existing Python 2-compatible projects.

Participants will specifically;

    Understand the syntactical differences between Python 2 and 3
    Use the Six and Future Libraries
    Review the new features in Python 3
    Choose which Python versions to support when doing neutral support
    Decide on whether to port or provide support for both versions


## Outline 

This is the outline for the talk.

1. A brief history on python (5 Minutes)

For a clear background, I will give a history on how python has evolved fron python 2 and now 3 with details on what caused the 
incompatibility and why it was needed despite the hickups it came with. I will also point out why we need to support python 3 and the 
given the future where we are approaching the python End of Life. 

2. An overview on compatibility Libraries (5 minutes)

To help in maintaining compatibility, tools like six and future were built to make the transition smooth. I will give a background to 
these tools and their usage.

3. Compatibility concepts (20 Minutes)

 I will share examples on how to write  compatible code on these topics:

    Print
    Numbers
    metaclasses
    package imports
    Strings
    collections
    Files
    HTML processing
    Exceptions and
    Special methods

## Additional notes 

I share my experience working on open source projects. I have authored a book on the subject that was released by Apress in 
December this year

I am a regular speaker at both local (uganda, kenya) and international conferences. I give mostly technical talks on the python 
at conferences like PyconZA in south Africa among others. I have shared a link to some of my recorded talks on youtube

https://www.youtube.com/results?search_query=Joannah+Nanjekye
