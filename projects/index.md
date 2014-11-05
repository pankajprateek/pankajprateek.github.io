---
layout: page
title: Projects
modified: 2014-07-31T13:23:02.362000-04:00
excerpt: ""
---

<section id="table-of-contents" class="toc">
  <header>
    <h3>Overview</h3>
  </header>
<div id="drawer" markdown="1">
*  Auto generated table of contents
{:toc}
</div>
</section><!-- /#table-of-contents -->

### INTERNSHIP

[**Hunting Compiler Concurrency bugs using x86-tso memory model**](https://raweb.inria.fr/rapportsactivite/RA2013/parkas/uid30.html) **_(May '13 – July '13)_**

Mentor: [Dr. Francesco Zappa Nardelli](http://www.di.ens.fr/~zappa/)

Team [Parkas](http://www.di.ens.fr/ParkasTeam.html.en), [INRIA](http://inria.fr/en), Paris-Rocquencourt

- Aimed at hunting concurrency bugs in GCC and CLANG to improve compiler optimizations for multi-processor applications
- Added global memory trace to study effect of compiler optimizations on global memory accesses, and replay instrumentation to
study the manner in which a load instruction affects subsequent instructions
- Added support for control dependency analysis to study effects of conditional statements, and MMX/SSE (128 bit SIMD) instructions
- Project Link: (http://raweb.inria.fr/rapportsactivite/RA2013/parkas/uid30.html)

---

### M.TECH THESIS

**Approximation Algorithms for common subtree & related problems _(Dec '13 – now)_**

Mentor: [Prof. S. K. Mehta](http://cse.iitk.ac.in/users/skmehta)

- Investigating approximation algorithms and parameterization techniques for the common sub-tree problem and trying to apply them
to specialized classes of graphs and related problems like tree edit distance

---

### RESEARCH PROJECTS

**Anaphora Without Syntax _(Aug '13 - now)_**

Mentor: [Dr. Sumit Gulwani](http://research.microsoft.com/en-us/um/people/sumitg/), [Prof. Amitabha Mukerjee](http://cse.iitk.ac.in/~amit), [Dr. Amey Karkare](http://cse.iitk.ac.in/~karkare)

- Designed a language-independent system for high-school geometry construction problems
- Achieved an accuracy of more than 90% for English and Hindi using cross lingual mapping (probabilistically mapping constructs/words
in different languages), heuristic based parsing and context based semantic analysis to handle anaphora
- The corpus, code and report are available at [http://cse.iitk.ac.in/users/pratikkr/btp/index.html](http://cse.iitk.ac.in/users/pratikkr/btp/index.html)

**Multi-Lingual word learning for containment situations _(Mar '13 – Apr '13)_**

Mentor: [Prof. Amitabha Mukerjee](http://cse.iitk.ac.in/~amit)

- Attempted to learn synonymous words in multiple languages for a given context using common ground semantics & label association
- Learned design specifications in the given context (peg-in-a-hole) and then tried to learn linguistic semantics for them
- The code and report is available at [http://home.iitk.ac.in/~pratikkr/se367/project/](http://home.iitk.ac.in/~pratikkr/se367/project/)

**Using Progressive Stochastic Search to solve Sudoku CSP _(Jan '12 – Apr '12)_**

Mentor: [Prof. Amitabha Mukerjee](http://cse.iitk.ac.in/~amit)

- Modelled Sudoku as a constraint satisfaction problem and implemented PSS and iterative PSS to solve a given Sudoku puzzle
- Observed that PSS and IPSS are better than other stochastic algorithms like Simulated Annealing and Cultural Genetic Algorithm
- The code and report is available at [http://home.iitk.ac.in/~pratikkr/cs365/projects/](http://home.iitk.ac.in/~pratikkr/cs365/projects/)

**C++ Compiler Design**

Mentor: [Prof. Sanjeev Kumar Aggarwal](http://cse.iitk.ac.in/users/ska/)

- Implemented a working compiler for a subset of C++ language features using C++, Lex/Yacc for MIPS architecture
- Built all compiler modules - lexer, parser (with error checking grammar), symbol table and code generator - from scratch

**Extensions to PintOS System**

Mentor: [Prof. Subhajit Roy](http://www.cse.iitk.ac.in/users/subhajit/)

- Extended barebones operating system to add features for system calls, inter-process communication using shared memory model, virtual memory with pure demand paging and buffer caching for efficient I/O
- Programmed PintOS file system on the lines of ext2 file system to support sub-directories and 3-level indexed inodes
