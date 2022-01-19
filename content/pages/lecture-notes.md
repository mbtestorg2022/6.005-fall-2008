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

| SES # | TOPICS | LECTURE NOTES |
| --- | --- | --- |
| 1 | {{< h 3 >}}Introduction{{< /h >}} {{< br >}}{{< br >}} Basic Java syntax and semantics; overview of objectives and structure of the course {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec01)) |
| 2 | {{< h 3 >}}Classes{{< /h >}} {{< br >}}{{< br >}} More Java: exceptions, input/output, classes, access control, static {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec02)) |
| 3 | {{< h 3 >}}Subclassing and interfaces{{< /h >}} {{< br >}}{{< br >}} Subclassing, inheritance, overriding, interfaces, packages; distinction between declared type and actual type; downcasting; anonymous classes {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec03)) |
| 4 | {{< h 3 >}}Designing state machines{{< /h >}} {{< br >}}{{< br >}} State machine design; graphical and textual notation; state machine semantics; parallel combinations of machines {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec04)) |
| 5 | {{< h 3 >}}Implementing state machines{{< /h >}} {{< br >}}{{< br >}} State machine implementation patterns; concurrency and queues; modularity and interfaces {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec05)) |
| 6 | {{< h 3 >}}State machine invariants{{< /h >}} {{< br >}}{{< br >}} Safety and liveness properties; state properties and invariants; inductive reasoning; computing the product machine of a parallel combination; state explosion; fault tolerance; interlocks and the idea of a trusted base {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec06)) |
| 7 | {{< h 3 >}}Designing stream processors{{< /h >}} {{< br >}}{{< br >}} Stream processing programs; grammars vs. machines; JSP method of program derivation; regular grammars and expressions {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec07)) |
| 8 | {{< h 3 >}}Decoupling and interfaces{{< /h >}} {{< br >}}{{< br >}} Modularity, decoupling, information hiding; module dependence diagrams; using interfaces for decoupling {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec08)) |
| 9 | {{< h 3 >}}Testing and coverage{{< /h >}} {{< br >}}{{< br >}} Why software testing is hard; input space partitioning, boundary testing, state machine coverage, code coverage; test-first development and regression testing {{< br >}}{{< br >}}  | (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF]({{< baseurl >}}/resources/mit6_005f08_lec09)) |
| 10 | {{< h 3 >}}Designing a SAT solver, part 1{{< /h >}} {{< br >}}{{< br >}} The SAT problem and SAT solvers; a new paradigm of functions over immutable types; use datatype productions to model structured values; patterns for implementing datatypes (Variant as Class, Interpreter) {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec10)) |
| 11 | {{< h 3 >}}Designing a SAT solver, part 2{{< /h >}} {{< br >}}{{< br >}} Review of basic datatype patterns; a naive solver with backtracking search; design improvements with Facade, Option types, and a 3-valued logic {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec11)) |
| 12 | {{< h 3 >}}Debugging{{< /h >}} {{< br >}}{{< br >}} Techniques for avoiding debugging: assertions, modular development with unit testing, code reviews; strategies for debugging: reducing test cases, hypothesis-driven debugging, binary search; Heisenbugs {{< br >}}{{< br >}}  | (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF]({{< baseurl >}}/resources/mit6_005f08_lec12)) |
| 13 | {{< h 3 >}}Designing a SAT solver, part 3{{< /h >}} {{< br >}}{{< br >}} Abstract data types; representation independence; characterizing types by operations; encapsulation; examples of types used by DPLL solver; Factory Method pattern {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec13)) |
| 14 | {{< h 3 >}}Rep invariants, equality, visitors{{< /h >}} {{< br >}}{{< br >}} Advice on implementing types; rep invariants and abstraction functions; equality for immutable types; Iterator and Visitor patterns {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec14)) |
| 15 | {{< h 3 >}}Little languages{{< /h >}} {{< br >}}{{< br >}} Representing behavior using data structures; language datatypes, visitors, functional objects, higher-order functions; solving a problem by creating a domain-specific language {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec15)) |
| 16 | {{< h 3 >}}Basics of mutable types{{< /h >}} {{< br >}}{{< br >}} Heap semantics (aliasing, assignment, field setting); reachability and conceptual storage leaks; the Object Contract and equality properties; hash maps and their representation invariant; problems caused by mutation of keys {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec16)) |
| 17 | {{< h 3 >}}Event-based programming{{< /h >}} {{< br >}}{{< br >}} Fundamentals of programming graphical user interfaces; view hierarchy, Composite pattern, Publish-Subscribe pattern, Model-View-Controller (MVC); pitfalls of event-based programming {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec17)) |
| 18 | {{< h 3 >}}Designing a photo organizer{{< /h >}} {{< br >}}{{< br >}} The relational paradigm; conceptual modeling; object model syntax and semantics; Mitchell and Webb on "unity of purpose" {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec18)) |
| 19 | {{< h 3 >}}Implementing a photo organizer{{< /h >}} {{< br >}}{{< br >}} Implementation as object model transformation; key issue of where state resides; standard patterns; navigation, immutability and encapsulation; MVC considerations {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec19)) |
| 20 | {{< h 3 >}}Concurrency{{< /h >}} {{< br >}}{{< br >}} Shared-memory and message-passing paradigms; race conditions and deadlock; using threads and blocking queues in Java; concurrency issues in graphical user interfaces {{< br >}}{{< br >}}  | (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF]({{< baseurl >}}/resources/mit6_005f08_lec20)) |
| 21 | {{< h 3 >}}Usability{{< /h >}} {{< br >}}{{< br >}} User interface design principles: learnability, visibility, efficiency, errors, simplicity; iterative design; sketching and paper prototyping; user testing {{< br >}}{{< br >}}  | &nbsp; |
| 22 | {{< h 3 >}}Relational databases{{< /h >}} {{< br >}}{{< br >}} Using a database to represent an object model; relational algebra and SQL; transactions {{< br >}}{{< br >}}  | (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF]({{< baseurl >}}/resources/mit6_005f08_lec22)) |
| 23 | {{< h 3 >}}Conclusion{{< /h >}} {{< br >}}{{< br >}} Final words; courses and internships that might follow 6.005; winners of Project 3 awards; 6.005 quiz game {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/mit6_005f08_lec23))