# Domain-Specific Languages of Mathematics

[GitHub repository](https://github.com/DSLsofMath/DSLsofMath/) for open source material related the book "Domain-Specific Languages of Mathematics" [published in 2022 by College Publications](https://www.amazon.co.uk/dp/184890388X).

The book and the repository are used in a BSc-level course at Chalmers
and GU.

The main course homepage is in the Canvas LMS:
* [Main course page](https://chalmers.instructure.com/courses/17542) including links to zoom lectures and other media
* [Lecture media](https://chalmers.instructure.com/courses/17542/pages/lecture-media)

Course codes: [DAT326](https://www.student.chalmers.se/sp/course?course_id=29865) / [DIT982](http://kursplaner.gu.se/english/DIT982.pdf)

## News

* Tuesday 2022-01-18: First lecture of the 2022 course instance ([zoom links, etc](https://chalmers.instructure.com/courses/17542/pages/lecture-media))
* 2022: book available from [Amazon](https://www.amazon.co.uk/dp/184890388X).
* [Lecture note snapshots](L/snapshots/) with drafts of the full course book
* [YouTube playlist](https://www.youtube.com/playlist?list=PLf5C73P7ab-4kc8Z4S7adKdm-nTkn-ND-) with the recorded lectures from the 2021 course instance (most in Swedish, some in English)

## Contributors

* Main author, examiner, lecturer: Patrik Jansson (patrikj AT)
* First version (and continued support): Cezar Ionescu (cezar AT)
* Book co-author: Jean-Philippe Bernardy
* Teaching assistants:
  * 2022: Sólrún Einarsdóttir (slrn AT), David Wärn (warnd AT), and Felix Cherubini (felixche AT)
  * 2021: Maximilian Algehed (algehed AT) and Víctor López Juan (lopezv AT)
  * 2020: Sólrún Einarsdóttir (slrn AT) and Víctor López Juan (lopezv AT)
  * 2019: Maximilian Algehed (algehed AT) and Abhiroop Sarkar (sarkara AT)
  * 2018: Daniel Schoepe (schoepe AT)
  * 2017: Frederik Hanghøj Iversen (hanghj AT student) and Daniel Schoepe (schoepe AT)
  * 2016: Irene Lobo Valbuena (lobo AT)
* Project assistants: Daniel Heurlin, Sólrún Einarsdóttir, Adam Sandberg Ericsson (saadam AT)

where AT = @chalmers.se

## Course material

This repository is mainly the home of the DSLsofMath book (originating
from the course lecture notes), also available in print from
[Amazon](https://www.amazon.co.uk/dp/184890388X).

Comments and contributions are always welcome – especially in the form
of pull requests.

The main references are listed below.

## Objectives

The course presents classical mathematical topics from a computing
science perspective: giving specifications of the concepts introduced,
paying attention to syntax and types, and ultimately constructing DSLs
of some mathematical areas mentioned below.

Learning outcomes as in the
[course syllabus](https://www.student.chalmers.se/sp/course?course_id=32245).

* Knowledge and understanding
    * design and implement a DSL (Domain-Specific Language) for a new domain
    * organize areas of mathematics in DSL terms
    * explain main concepts of elementary real and complex analysis, algebra, and linear algebra
* Skills and abilities
    * develop adequate notation for mathematical concepts
    * perform calculational proofs
    * use power series for solving differential equations
    * use Laplace transforms for solving differential equations
* Judgement and approach
    * discuss and compare different software implementations of mathematical concepts

The course is elective for both computer science and mathematics
students at both Chalmers and GU.

## Course setup

* Lectures
    * Introduction: Haskell, complex numbers, syntax, semantics, evaluation, approximation
    * Basic concepts of analysis: sequences, limits, convergence, ...
    * Types and mathematics: logic, quantifiers, proofs and programs, Curry–Howard, ...
        * Type classes, derivatives, differentiation, calculational proofs
    * Domain-Specific Languages and algebraic structures, algebras, homomorphisms
    * Polynomials, series, power series
    * Power series and differential equations, exp, sin, log, Taylor series, ...
    * Linear algebra: vectors, matrices, functions, bases, dynamical systems as matrices and graphs
    * Laplace transform: exp, powers series cont., solving PDEs with Laplace
* Weekly exercise sessions
    * Half time helping students solve problems in small groups
    * Half time joint problem solving at the whiteboard

## Lectures

The latest PDF snapshot of the book can be found in
[L/snapshots](L/snapshots/) but please also consider buying the ["real
thing"](https://www.amazon.co.uk/dp/184890388X).

The "source code" for the chapters are in subdirectories of L/:
[L/01/](L/01), [L/02/](L/02/), etc. where chapter N is approximately
course week N.

## Exercises

Most chapters end with weekly exercises.

(TODO: update the list to handle some reordering during 2021: In
[L/RecEx.md](L/RecEx.md) you will find a list of recommended exercises
for each chapter of the lecture notes.)

## References

Some important references:

### Functional programming

- **Thinking Functionally with Haskell**, Richard Bird, Cambridge
  University Press, 2014
  [URL](http://www.cs.ox.ac.uk/publications/books/functional/)
- **Introduction to Functional Programming Using Haskell**, Richard
  Bird, Prentice Hall, 1998.  A previous (but clearly different)
  version of the above.
- **An Introduction to Functional Programming**, Richard Bird and Phil
  Wadler, Prentice Hall, 1988. A previous (but clearly different)
  version of *both* of the above.

### DSLs

- **Functional Programming for Domain-Specific Languages**, Jeremy
  Gibbons.  In *Central European Functional Programming School 2015*,
  LNCS 8606, 2015.
  [URL](http://link.springer.com/chapter/10.1007%2F978-3-319-15940-9_1)

  This is currently *the* standard reference to DSLs for the
  functional programmer.

- **Folding Domain-Specific Languages: Deep and Shallow Embeddings**,
  Jeremy Gibbons and Nicolas Wu,
  ICFP 2014. [URL](http://www.cs.ox.ac.uk/publications/publication7584-abstract.html)

  Available at the same link: a highly recommended
  [short version](http://www.cs.ox.ac.uk/people/jeremy.gibbons/publications/embedding-short.pdf)
  and the two videos of Jeremy presenting the most important ideas
  of DSLs in a very accessible way.

- **Programming Languages**, Mike Spivey.  Lecture notes of a course
  given at the CS Department in Oxford.  Useful material for
  understanding the design and implementation of embedded DSLs.
  [URL](http://spivey.oriel.ox.ac.uk/corner/Programming_languages)

- **Domain-Specific Languages**, Martin Fowler, 2011.
  [URL](http://martinfowler.com/books/dsl.html)

  The view from the object-oriented programming perspective.

### The computer science perspective

- **Communicating Mathematics: Useful Ideas from Computer Science**,
  Charles Wells, *American Mathematical Monthly*, May 1995.  [URL](http://www.cwru.edu/artsci/math/wells/pub/pdf/commath.pdf)

  This article was one of the main triggers of this course.

  [Short summary of the recommendations](PedProj/CommunicatingMathematics_Wells.md)

### Mathematics

- **The Language of First-Order Logic, 3rd Edition**, Jon Barwise and John
  Etchemendy, 1993.  Out of print, but you can get it for one penny
  from Amazon UK.  A vast improvement over its successors (as Tony
  Hoare said about Algol 60).

- **Mathematics: Form and Function**, Saunders Mac Lane, Springer 1986.
  An overview of the relationships between the many mathematical
  domains.  Entertaining, challenging, rewarding.
  [Fulltext from the library](http://chalmers.summon.serialssolutions.com/sv-SE/search?ho=t&q=Mathematics%3A%20Form%20and%20Function)

- **Functional Differential Geometry**, Gerald Jay Sussman and Jack
  Wisdom, 2013, MIT.  A book about using programming as a means of
  understanding differential geometry.  Similar in spirit to the course,
  but more advanced and very different in form.  An earlier version
  appeared as an [AIM report](http://web.mit.edu/wisdom/www/AIM-2005-003.pdf).

# License: CC-BY-NC-SA 4.0

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
