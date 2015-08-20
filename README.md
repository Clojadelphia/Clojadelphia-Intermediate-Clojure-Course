# Clojadelphia Intermediate Clojure Course
Curriculum for intermediate-level coursework in Clojure. You got the basics down, right?
Now it's time to take the next step: learn the tooling, ecosystem, idioms,
how to create and work on real-world projects in Clojure!

## Lesson Outline

* Idiomatic Clojure
    - How not to write Blub in Clojure
    - Thinking in Clojure
    - Thinking in Data
        - Combinators,
        - Data Transformations
        - Data > Functions > Macros - Why What does this mean?

* The Clojure REPL
    - Jacking in
    - REPL-driven development, REPL-oriented workflows, e.g. Stuart Sierra's Component
        - Are there others?

* Clojure concurrency
    - Refs
    - Atoms
    - Agents

* Advanced Java Interop
    - Working with Java classes / interfaces in Clojure
    - Implementing interfaces / extending classes for Java consumption
    - Is it a fully two-way street? Is one harder than the other?

* Leiningen
    - What do I need to know to get started?
    - Capabilities
    - Best practices
    - Maven? Clojars? How do they fit in with lein? How much do I need to know about them?

* Libraries
    - I'm about to write some code;
        - Should I, or is there a library for it already written?
        - How do I know?
        - Where do I look?
    - Incorporating libraries into my project

* Structuring your code
    - Understanding namespaces
        - How do I tell the difference between and know when to use:
            - `:use`?
            - `:require`?
            - `:refer`?

* Web Development
    - Tour of the ecosystem. I've heard of so many different clojure libs/frameworks for web development . . .
      Why so much apparent library churn? Which of these do I need to know about today?
      Which ones did I not know about but should be on this list?
        - Noire
        - Ring
        - Compojure
        - Hoplon
        - Pedestal
        - Transit

    - To Clojurescript or not?
        - Isomorphic Clojure?
        - Targetting the JVM vs. JS, how to write shared code
        - Om
        - lein-figwheel

* Interacting with, choosing a data store
    - RDBMS?
    - NOSQL?
    - Datomic?

* Microservices?
