---
layout: page
title: Projects
permalink: /projects/
description: My research interests and what I have been working on. 
nav: true
---

### Current

<div class="accordion" id="current">
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingOne">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="false" aria-controls="collapseOne">
        Cartesius and PolyJoin
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse" aria-labelledby="headingOne" data-bs-parent="#current">
      <div class="accordion-body">
<p><strong>Cartesius</strong> is a semantic model for defining expressive n-way joins/merges over asynchronous event sequences/streams.
Joins exists in different domains, e.g., stream-relational algebra, complex event patterns, (functional) reactive programming and 
concurrent programming (join calculus). With Cartesius, we can define join variants in a uniform and structured manner.
We may think of Cartesius as solving an instance of Wadler's "expression problem" in the realm of big data.
The workhorse are algebraic effects and handlers, which we employ to interpret declarative join pattern specifications in different ways.</p>
<p><strong>PolyJoin</strong> complements Cartesius with a pragmatic, type-safe, and purely combinator-based programming language embedding
of comprehension syntax for joins. It permits more liberal notions of computations than LINQ, respectively monadic
"do" and "for" comprehensions.</p>
<hr>
<b>Code:</b>&nbsp;<a href="https://github.com/bracevac/corrl">github</a>&nbsp;&nbsp;&nbsp;&nbsp;<b>References:</b>&nbsp; {% cite dissertation %} {% cite icfp18 %} {% cite polyjoins %} 
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingTwo">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
       Dotter 
      </button>
    </h2>
    <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#current">
      <div class="accordion-body">
      <p>Coq and Agda developments on the dependent object types (DOT) family of calculi,
the foundation of the Scala programming language. I explore pathways to bring richer forms of dependent types into the language.
Occasionally, I also contribute to Tiark Rompf's <a href="https://github.com/tiarkrompf/minidot">minidot</a> repository.</p>
<hr>
<b>Code:</b>&nbsp;<a href="https://github.com/bracevac/dotter">github</a>
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingThree">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
       Staged Symbolic Execution (SSE) 
      </button>
    </h2>
    <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#current">
      <div class="accordion-body">
       <p>A principled and performant approach to constructing symbolic
execution engines and symbolic compilers, which has been considered hard -- until now! 
We combine programming language's vanilla definitional interpreter, algebraic effects and handlers, multi-stage programming, and the first Futamura projection.</p>
<hr>
      <b>Code:</b>&nbsp;<a href="https://github.com/Kraks/sai">github</a>&nbsp;&nbsp;&nbsp;&nbsp;<b>References:</b>&nbsp;{% cite oopsla20 %} 
      </div>
    </div>
  </div>
</div>
<br/>

### Past

<div class="accordion" id="past">
  <div class="accordion-item">
    <h2 class="accordion-header" id="hpastOne">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#pastOne" aria-expanded="false" aria-controls="pastOne">
        Incremental Type Checkers
      </button>
    </h2>
    <div id="pastOne" class="accordion-collapse collapse" aria-labelledby="hpastOne" data-bs-parent="#past">
      <div class="accordion-body">
<p> Explores how we may systematically
obtain an *incremental* type checker for a given programming language. Incrementalization avoids expensive re-computation
of type checking and other program analyses in large-scale software projects and thus may lower the latency in IDEs
and decrease compilation times overall. The project is based on the notion of *co-contextual* typing rules.</p>
<hr>
<b>Code:</b>&nbsp;<a href="https://github.com/bracevac/incremental">github</a>&nbsp;&nbsp;&nbsp;&nbsp;<b>References:</b>&nbsp; {% cite oopsla15 %} {% cite ecoop17 %} 
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="hpastTwo">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#pastTwo" aria-expanded="false" aria-controls="pastTwo">
      Cloud Platform Language (CPL) 
      </button>
    </h2>
    <div id="pastTwo" class="accordion-collapse collapse" aria-labelledby="hpastTwo" data-bs-parent="#past">
      <div class="accordion-body">
      <p>
Explores foundations of typed distributed programming
with first-class server abstractions, join patterns for synchronization, and transparent placement. Server configurations, deployments,
and cloud/middleware services can be programmed as libraries of combinators in CPL. These tasks usually require a multitude of 
unsafe configuration languages with no safety net. Comes with an interpreter in  <a href="https://www.scala-lang.org">Scala</a> and a <a href="https://redex.racket-lang.org">PLT Redex</a> mechanization. 
      </p>
      <hr>
<b>Code:</b>&nbsp;<a href="https://github.com/bracevac/djc-lang">github</a>&nbsp;&nbsp;&nbsp;&nbsp;<b>References:</b>&nbsp; {% cite modularity %}  
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="hpastThree">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#pastThree" aria-expanded="false" aria-controls="pastThree">
       Modular Assembly Kit for Security Properties (MAKS) 
      </button>
    </h2>
    <div id="pastThree" class="accordion-collapse collapse" aria-labelledby="hpastThree" data-bs-parent="#past">
      <div class="accordion-body">
       <p>A mechanization of Heiko Mantel's *Modular Assembly Kit for Security Properties*
          in the proof assistant <a href="http://isabelle.in.tum.de">Isabelle/HOL</a>.</p>
          <hr>
      <b>Code:</b>&nbsp;<a href="https://www.isa-afp.org/entries/Modular_Assembly_Kit_Security.html">Archive of Formal Proofs</a>
      </div>
    </div>
  </div>
</div>

