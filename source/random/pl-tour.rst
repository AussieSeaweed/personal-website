Tour of PLs
===========

In the coming summer of 2025, I plan on undertaking a major software project to develop a computer algebra system (and maybe an entirely new programming language). In my past attempts as far back as when I was in high school, I found that the programming languages I tried out were inadequate in addressing my needs and therefore hindered the development process.

I feel like the set of programming languages I am familiar with or have used in the past is limited in scope and not representative of the broad options that are available for use.

As such, I plan on undertaking a search for the perfect programming language. For each language I explore, I aim to do a short tour of the language to get my toes wet. My goal is not a mastery of the language but rather a survey of it. In my tours, I aim to use the reference implementations when available. When there exists no reference implementation (or such a concept does not apply) for a particular language, I will use the most popular implementation available for the language.

The selections listed below, sourced from `DMOJ <https://dmoj.ca/runtimes/>`_ and the `TIOBE Index <https://www.tiobe.com/tiobe-index/>`_, contain a diverse range of both widely-used and esoteric programming languages. Some of these are languages I am already very familiar with, but I will re-explore them anyway. Empty tour entries indicates that the corresponding language has not yet been explored.

January 16, 2025

Notes
-----

`Ada <https://www.adaic.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Ada is a language I've been interested in a long time, considering that it powers safety-critical use cases like fighter jets and space shuttles. Only now have I given it a proper look. The language's extremely strong typing system and design-by-contract features are very intriguing. Indeed, numeric types that can be constrained to a range of values and unsigned "modulus" types that wraps around an arbitrary value are simply unheard of in other more mainstream languages, and they would be quite convenient for some competitive programming tasks I am used to. In addition, the ability to derive separate numeric types (e.g., different units, IDs) seems useful for domain-specific use cases (e.g., scientific). One major drawback is that its prose syntax is very verbose and unaesthetic, at least for me. Regardless, Ada is a memerable language that I might return to. I would like to see some of Ada's features implemented to type systems of other languages (even Python!).

`January 28, 2025 <https://learn.adacore.com/courses/intro-to-ada/>`_

`ALGOL 68 <https://en.wikipedia.org/wiki/ALGOL_68>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`AWK <https://en.wikipedia.org/wiki/AWK>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`C <https://www.iso.org/standard/82075.html>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`C# <https://learn.microsoft.com/en-us/dotnet/csharp/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`C++ <https://isocpp.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`COBOL <https://en.wikipedia.org/wiki/COBOL>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Chez Scheme <https://www.scheme.com/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Chicken <https://www.call-cc.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Clojure <https://clojure.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Common Lisp <https://www.sbcl.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`D <https://dlang.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Dart <https://dart.dev/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Elixir <https://elixir-lang.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Erlang <https://www.erlang.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`F# <https://learn.microsoft.com/en-us/dotnet/fsharp/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Forth <https://forth-standard.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Fortran <https://fortran-lang.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Who'd have known I would get a taste of punch card programming by learning Fortran (``.f`` files)? Fortran's array mechanism feels impressively modern, considering its age. Still, as a whole, the language feels old and clunky, with many strange design decisions. To me, it feels like a relic of the past, and definitely unsuited for writing an entirely new project with.

Speaking of, why on earth is Fortran ranked tenth on the `TIOBE index <https://www.tiobe.com/tiobe-index/>`_, ahead of languages like PHP, Rust, MATLAB, Ruby, R, and Swift?

`January 19, 2025 <https://fortran-lang.org/learn/quickstart/>`_

`Go <https://go.dev/>`_
^^^^^^^^^^^^^^^^^^^^^^^

Essentially, a modern C, featuring garbage collection, larger standard libraries, easier parallelism, and saner design. Perfect for most concurrent programming tasks.

`January 18, 2025 <https://go.dev/tour/list>`_

`Groovy <https://groovy-lang.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Haskell <https://www.haskell.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

A skilled programmer, after looking at my Python code, once asked me whether or not I know Haskell. Back then, I have never done any functional programming. So, I said no, and he seemed intrigued. I wasn't sure, but I had a feeling he meant that as a compliment!

After getting familiar with functional programming (previously OCaml and now Haskell), I am quite certain it was indeed a compliment! However, the short 5-minute tutorial I tried on their website doesn't seem to do justice to the language. Overall, it seems more or less similar to OCaml which I just learned. I have yet to learn some concepts I know exist in Haskell like Monads. I might come back to this to learn more.

`January 19, 2025 <https://www.haskell.org/>`_

`Java <https://www.java.com/en/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`JavaScript <https://ecma-international.org/publications-and-standards/standards/ecma-262/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Julia <https://julialang.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Kotlin <https://kotlinlang.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Kotlin has a beautiful design that surpasses even that of Scala. It also represents one of the rare cases where builtins actually follow their own naming conventions and style guides (unlike, say, Python). JVM compatibility and compilation to JavaScript are great. However, the platform-dependent standard library support is a bit confusing.

`January 18, 2025 <https://kotlinlang.org/docs/kotlin-tour-welcome.html>`_

`Lean <https://lean-lang.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Lua <https://www.lua.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`OCaml <https://ocaml.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The language of Jane Street! This is also the first time I've ever tried out a functional programming language, and boy was I in for a treat... Everything feels elegant and without waste. It overcomes so many of the issues I encountered with traditional imperative programming languages. I am concerned about its (and functional programming languages') performance however, given that (almost) everything is to be implemented recursively.

`January 19, 2025 <https://ocaml.org/docs/tour-of-ocaml>`_

`Objective C <https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Perl <https://www.perl.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`PHP <https://www.php.net/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Pascal <https://www.freepascal.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Pike <https://pike.lysator.liu.se/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Prolog <https://www.iso.org/standard/21413.html>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Python <https://www.python.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`R <https://www.r-project.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Raku <https://raku.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Racket <https://racket-lang.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Ruby <https://www.ruby-lang.org/en/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

I heard that a skilled web developer can set up a website with Ruby on Rails in just five minutes. There is no question that Ruby is widely used for web applications (e.g., Rails and Jekyll). But, is Ruby used for anything other than the web? I genuinely don't know.

As a programming language, however, I do admire Matz's steadfast defense of dynamic typing, especially when strict programming practices have become such a norm. With that said, I would choose to use Python over Ruby for most tasks.

`January 19, 2025 <https://www.ruby-lang.org/en/documentation/quickstart/>`_

`Rust <https://www.rust-lang.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Scala <https://www.scala-lang.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Swift <https://developer.apple.com/swift/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Tcl <https://www.tcl-lang.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Visual Basic <https://learn.microsoft.com/en-us/dotnet/visual-basic/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

`Zig <https://ziglang.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

I was quite surprised to find that Vim has an excellent built-in plugin for Zig. Their brief but extremely technical overview sure convinced me of its overwhelming advantages over C (built-in error handling, null safety, reflection, tracing, etc.) and its unbelievable interoperability with C. What is particularly ambitious is that Zig seeks to be an alternative to even C compilers and make systems, allowing an easy and gradual transition from C to Zig for legacy projects. I have to confess that I was unable to fully understand every single part of the overview. This is definitely a language I will keep an eye on.

`January 20, 2025 <https://ziglang.org/learn/overview/>`_

Projects
--------

My goal is to write a meaningful family of software tools, application programs, or infrastructures dedicated to a single topic for each programming language explored. It will certainly take a long time to finish this table.

+----------------------+-------------------------+
| Programming Language | Topic(s)                |
+======================+=========================+
| Ada                  |                         |
+----------------------+-------------------------+
| ALGOL 68             |                         |
+----------------------+-------------------------+
| AWK                  |                         |
+----------------------+-------------------------+
| C                    |                         |
+----------------------+-------------------------+
| C#                   |                         |
+----------------------+-------------------------+
| C++                  |                         |
+----------------------+-------------------------+
| COBOL                |                         |
+----------------------+-------------------------+
| Chez Scheme          |                         |
+----------------------+-------------------------+
| Chicken              |                         |
+----------------------+-------------------------+
| Clojure              |                         |
+----------------------+-------------------------+
| Common Lisp          |                         |
+----------------------+-------------------------+
| D                    |                         |
+----------------------+-------------------------+
| Dart                 |                         |
+----------------------+-------------------------+
| Elixir               |                         |
+----------------------+-------------------------+
| Erlang               |                         |
+----------------------+-------------------------+
| F#                   |                         |
+----------------------+-------------------------+
| Forth                |                         |
+----------------------+-------------------------+
| Fortran              |                         |
+----------------------+-------------------------+
| Go                   |                         |
+----------------------+-------------------------+
| Groovy               |                         |
+----------------------+-------------------------+
| Haskell              |                         |
+----------------------+-------------------------+
| Java                 |                         |
+----------------------+-------------------------+
| JavaScript           |                         |
+----------------------+-------------------------+
| Julia                |                         |
+----------------------+-------------------------+
| Kotlin               |                         |
+----------------------+-------------------------+
| Lean                 |                         |
+----------------------+-------------------------+
| Lua                  |                         |
+----------------------+-------------------------+
| OCaml                | Computer Algebra System |
+----------------------+-------------------------+
| Objective C          |                         |
+----------------------+-------------------------+
| Perl                 |                         |
+----------------------+-------------------------+
| PHP                  |                         |
+----------------------+-------------------------+
| Pascal               |                         |
+----------------------+-------------------------+
| Pike                 |                         |
+----------------------+-------------------------+
| Prolog               |                         |
+----------------------+-------------------------+
| Python               | Poker Programming       |
+----------------------+-------------------------+
| R                    |                         |
+----------------------+-------------------------+
| Raku                 |                         |
+----------------------+-------------------------+
| Racket               |                         |
+----------------------+-------------------------+
| Ruby                 |                         |
+----------------------+-------------------------+
| Rust                 |                         |
+----------------------+-------------------------+
| Scala                |                         |
+----------------------+-------------------------+
| Swift                |                         |
+----------------------+-------------------------+
| Tcl                  |                         |
+----------------------+-------------------------+
| Visual Basic         |                         |
+----------------------+-------------------------+
| Zig                  |                         |
+----------------------+-------------------------+
