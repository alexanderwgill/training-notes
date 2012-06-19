training-notes
==============

Tools:
- git - distributed source control 
- github - most popular web hosting site for git repositories
- R# (resharper) - Extension to visual studio for refactoring, navigation, etc.

Practice:
- bowling kata - http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata
  		   - (C#) http://codernub.blogspot.com/2010/01/c-bowling-kata-as-tdd-exercise.html

People:
Uncle Bob (Robert Martin)

Testing:
- TDD - red/green/refactor
	  - emergent design (Test Drive Design)
- Frameworks
	- xUnit (AAA: arrange, act, assert)
		- C#: MSTEST (in VS), NUnit (http://www.nunit.org/)
		- Java: JUnit
		- Ruby: Test::Unit
	- BDD - Behavior Driven Development: testing one behavior at a time - more like plain english, testing 
		- C#: MSpec, NSpec (neither really used)
		- Ruby: RSpec (everyone uses)
		- JavaScript: Jasmine (most people use)

History of C#:
- assembly - machine/CPU specific code
           - extremely low level
           - fast
           - hard to maintain
- C - compilable to a specific CPU architecture
    - low level
    - fast
    - procedural (harder to maintain)
- C++ - C with object orientation
      - more frameworks/libraries/tools than C
      - fast
      - object oriented
      - "everything is optional" (can be low level) => memory allocation/cleanup => hard to maintain
- Java - object oriented
       - runs on the Java Virtual Machine - portable
       - slower (but fast enough)
       - automatic memory management (garbage collection) => easier to maintain
       - developed by Sun, free/open source
       - Tools: Eclipse
- J++ - Java "owned" by Microsoft
      - propriotary JVM
      - anti-trust lawsuits follow
      - Tools: Visual Studio
- .NET Framework - family of languages that compile down to one common language (IL) and run on the .NET Common Language Runtime (which is like a JVM).
                 - J# replaces J++, but only temporarily
                 - C# is the leading language
                 - Tools: Visual Studio .NET
- C# - very much like Java but on .NET, but separate enough so they don't get sued
     - Acadamia has left Java and moved on to Ruby, Python, Functional Programming, corporations still invest in C#, hence C# is advancing and Java is not.