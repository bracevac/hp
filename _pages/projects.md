---
layout: page
title: Projects
permalink: /projects/
description: My research interests and what I have been working on. 
nav: true
---

### Current

* [Cartesius and PolyJoin](https://github.com/bracevac/corrl). 
Cartesius is a semantic model for defining expressive n-way joins/merges over asynchronous event sequences/streams.
Joins exists in different domains, e.g., stream-relational algebra, complex event patterns, (functional) reactive programming and 
concurrent programming (join calculus). With Cartesius, we can define join variants in a uniform and structured manner.
We may think of Cartesius as solving an instance of Wadler's "expression problem" in the realm of big data.
The workhorse are algebraic effects and handlers, which we employ to interpret declarative join pattern specifications in different ways.
PolyJoin complements Cartesius with a pragmatic, type-safe, and purely combinator-based programming language embedding
of comprehension syntax for joins. It permits more liberal notions of computations than LINQ, respectively monadic
"do" and "for" comprehensions. 
My PhD thesis {% cite dissertation %} and associated papers {% cite icfp18 %} & {% cite polyjoins %} 
contain more details. 



* [Dotter](https://github.com/bracevac/dotter). [Coq](https://coq.inria.fr) and [Agda](https://wiki.portal.chalmers.se/agda/pmwiki.php) developments on the dependent object types (DOT) family of calculi,
the foundation of the [Scala](https://www.scala-lang.org) programming language. I explore pathways to bring richer forms of dependent types into the language.
Occasionally, I also contribute to Tiark Rompf's [minidot](https://github.com/tiarkrompf/minidot) repository. 

* [Staged Symbolic Execution (SSE)](https://github.com/Kraks/sai). A principled and performant approach to constructing symbolic
execution engines and symbolic compilers, which has been considered hard -- until now! 
We combine programming language's vanilla definitional interpreter, algebraic effects and handlers, multi-stage programming, and the first Futamura projection. 
Read our OOPSLA'20 paper {% cite oopsla20 %} for more details.

### Past

* [Incremental type checkers](https://github.com/bracevac/incremental). Explores how we may systematically
obtain an *incremental* type checker for a given programming language. Incrementalization avoids expensive re-computation
of type checking and other program analyses in large-scale software projects and thus may lower the latency in IDEs
and decrease compilation times overall. The project is based on the notion of *co-contextual* typing rules.
More details in our papers {% cite oopsla15 %} and {% cite ecoop17 %}.

* [Cloud Platform Language (CPL)](https://github.com/bracevac/djc-lang) explores foundations of typed distributed programming
with first-class server abstractions, join patterns for synchronization, and transparent placement. Server configurations, deployments,
and cloud/middleware services can be programmed as libraries of combinators in CPL. These tasks usually require a multitude of 
unsafe configuration languages with no safety net. Comes with a [Scala](https://www.scala-lang.org) interpreter and [PLT Redex](https://redex.racket-lang.org) mechanization. 
The paper {% cite modularity %} contains more details.

* [MAKS](https://www.isa-afp.org/entries/Modular_Assembly_Kit_Security.html). A mechanization of Heiko Mantel's *Modular Assembly Kit for Security Properties*
in the proof assistant [Isabelle/HOL](http://isabelle.in.tum.de). 

