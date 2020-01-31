2019/2020 Compilers Coursework
==============================

There is a single assessed code deliverable, which is due on Tue 24 March at 23:59. This deliverable contains two components:

- [*C-translator*](c_translator.md) (35%): Your compiler will be able to translate a subset of C into equivalent Python. This allows each submission to demonstrate lexing and parsing functionality, even if the code generation is weak.

- [*C-compiler*](c_compiler.md) (55%): This is a compiler from C to MIPS assembly.
  
In all cases, the source language is pre-processed C90. The target environment is Ubuntu 16.04, so the lab Ubuntu distribution, or equivalently an Ubuntu 16.04 VM as configured in the attached Vagrantfile.

Associated with all deliverables is a

- [time-tracking/project management component](management.md) (10%).

which will be assessed orally at the start of Summer term.

Repositories
============

Each group gets a bare private repository. It is up to you if you want to clone the master specification, or to start from scratch.

Submission
==========

Submission will be via GitHub (code) and Blackboard (commit hash), as in the lab.

All submissions will be tested functionally -- there is no expectation for your compiler to *optimise* its input. Moreover, your compiler will only be tested on *valid* inputs, so you do not need to handle faulty inputs in a graceful way.

Changelog
=========

* New for 2019/2020:

    * In previous years, students were additionally required to submit a set of testcases. This deliverable has been removed; instead, a large collection of testcases has been provided for you, as this was judged to be more useful.

    * In previous years, the compiler component counted for 42.8% of the module; it now counts for 55%. It was felt that this weighting more accurately reflects the effort that students put in to building a working compiler.
