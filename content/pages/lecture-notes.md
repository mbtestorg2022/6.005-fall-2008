---
content_type: page
title: Lecture Notes
uid: 3a88398d-2539-09b4-c278-7feefc951a95
---

Review Handouts
---------------

State machine syntax and semantics ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec_state_machine))

Graphical object model notation ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec_object_model))

Topics by Session
-----------------

Notes for lecture 21 are not available.

### Abbreviations

JSP = Jackson Structured Programming

DPLL = Davis-Putnam-Logemann-Loveland (algorithm)

SQL = Structured Query Language

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
SES #
{{< thclose >}}
{{< thopen >}}
TOPICS
{{< thclose >}}
{{< thopen >}}
LECTURE NOTES
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}


### Introduction

Basic Java syntax and semantics; overview of objectives and structure of the course


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec01))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}


### Classes

More Java: exceptions, input/output, classes, access control, static


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec02))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
3
{{< tdclose >}}
{{< tdopen >}}


### Subclassing and interfaces

Subclassing, inheritance, overriding, interfaces, packages; distinction between declared type and actual type; downcasting; anonymous classes


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec03))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4
{{< tdclose >}}
{{< tdopen >}}


### Designing state machines

State machine design; graphical and textual notation; state machine semantics; parallel combinations of machines


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec04))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
5
{{< tdclose >}}
{{< tdopen >}}


### Implementing state machines

State machine implementation patterns; concurrency and queues; modularity and interfaces


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec05))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
6
{{< tdclose >}}
{{< tdopen >}}


### State machine invariants

Safety and liveness properties; state properties and invariants; inductive reasoning; computing the product machine of a parallel combination; state explosion; fault tolerance; interlocks and the idea of a trusted base


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec06))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
7
{{< tdclose >}}
{{< tdopen >}}


### Designing stream processors

Stream processing programs; grammars vs. machines; JSP method of program derivation; regular grammars and expressions


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec07))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
8
{{< tdclose >}}
{{< tdopen >}}


### Decoupling and interfaces

Modularity, decoupling, information hiding; module dependence diagrams; using interfaces for decoupling


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec08))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
9
{{< tdclose >}}
{{< tdopen >}}


### Testing and coverage

Why software testing is hard; input space partitioning, boundary testing, state machine coverage, code coverage; test-first development and regression testing


{{< tdclose >}}
{{< tdopen >}}
(![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF]({{< baseurl >}}/resources/mit6_005f08_lec09))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
10
{{< tdclose >}}
{{< tdopen >}}


### Designing a SAT solver, part 1

The SAT problem and SAT solvers; a new paradigm of functions over immutable types; use datatype productions to model structured values; patterns for implementing datatypes (Variant as Class, Interpreter)


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec10))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11
{{< tdclose >}}
{{< tdopen >}}


### Designing a SAT solver, part 2

Review of basic datatype patterns; a naive solver with backtracking search; design improvements with Facade, Option types, and a 3-valued logic


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec11))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
12
{{< tdclose >}}
{{< tdopen >}}


### Debugging

Techniques for avoiding debugging: assertions, modular development with unit testing, code reviews; strategies for debugging: reducing test cases, hypothesis-driven debugging, binary search; Heisenbugs


{{< tdclose >}}
{{< tdopen >}}
(![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF]({{< baseurl >}}/resources/mit6_005f08_lec12))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13
{{< tdclose >}}
{{< tdopen >}}


### Designing a SAT solver, part 3

Abstract data types; representation independence; characterizing types by operations; encapsulation; examples of types used by DPLL solver; Factory Method pattern


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec13))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
14
{{< tdclose >}}
{{< tdopen >}}


### Rep invariants, equality, visitors

Advice on implementing types; rep invariants and abstraction functions; equality for immutable types; Iterator and Visitor patterns


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec14))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
15
{{< tdclose >}}
{{< tdopen >}}


### Little languages

Representing behavior using data structures; language datatypes, visitors, functional objects, higher-order functions; solving a problem by creating a domain-specific language


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec15))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
16
{{< tdclose >}}
{{< tdopen >}}


### Basics of mutable types

Heap semantics (aliasing, assignment, field setting); reachability and conceptual storage leaks; the Object Contract and equality properties; hash maps and their representation invariant; problems caused by mutation of keys


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec16))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
17
{{< tdclose >}}
{{< tdopen >}}


### Event-based programming

Fundamentals of programming graphical user interfaces; view hierarchy, Composite pattern, Publish-Subscribe pattern, Model-View-Controller (MVC); pitfalls of event-based programming


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec17))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
18
{{< tdclose >}}
{{< tdopen >}}


### Designing a photo organizer

The relational paradigm; conceptual modeling; object model syntax and semantics; Mitchell and Webb on "unity of purpose"


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec18))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
19
{{< tdclose >}}
{{< tdopen >}}


### Implementing a photo organizer

Implementation as object model transformation; key issue of where state resides; standard patterns; navigation, immutability and encapsulation; MVC considerations


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec19))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
20
{{< tdclose >}}
{{< tdopen >}}


### Concurrency

Shared-memory and message-passing paradigms; race conditions and deadlock; using threads and blocking queues in Java; concurrency issues in graphical user interfaces


{{< tdclose >}}
{{< tdopen >}}
(![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF]({{< baseurl >}}/resources/mit6_005f08_lec20))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
21
{{< tdclose >}}
{{< tdopen >}}


### Usability

User interface design principles: learnability, visibility, efficiency, errors, simplicity; iterative design; sketching and paper prototyping; user testing


{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
22
{{< tdclose >}}
{{< tdopen >}}


### Relational databases

Using a database to represent an object model; relational algebra and SQL; transactions


{{< tdclose >}}
{{< tdopen >}}
(![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF]({{< baseurl >}}/resources/mit6_005f08_lec22))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
23
{{< tdclose >}}
{{< tdopen >}}


### Conclusion

Final words; courses and internships that might follow 6.005; winners of Project 3 awards; 6.005 quiz game


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit6_005f08_lec23))
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}