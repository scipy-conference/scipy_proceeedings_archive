---
title: "cphVB: A System for Automated Runtime Optimization and Parallelization
  of Vectorized Applications"
description: Modern processor architectures, in addition to having still more
  cores, also require still more consideration to memory-layout in order to run
  at full capacity. The usefulness of most languages is deprecating as their
  abstractions, structures or objects are hard to map onto modern processor
  architectures efficiently.
abstract: >-
  Modern processor architectures, in addition to having still more cores, also
  require still more consideration to memory-layout in order to run at full
  capacity. The usefulness of most languages is deprecating as their
  abstractions, structures or objects are hard to map onto modern processor
  architectures efficiently.


  The work in this paper introduces a new abstract machine framework, cphVB,
  that enables vector oriented high-level programming languages to map onto a
  broad range of architectures efficiently. The idea is to close the gap between
  high-level languages and hardware optimized low-level implementations. By
  translating high-level vector operations into an intermediate vector bytecode,
  cphVB enables specialized vector engines to efficiently execute the vector
  operations.


  The primary success parameters are to maintain a complete abstraction from
  low-level details and to provide efficient code execution across different,
  modern, processors. We evaluate the presented design through a setup that
  targets multi-core CPU architectures. We evaluate the performance of the
  implementation using Python implementations of well-known algorithms: a jacobi
  solver, a kNN search, a shallow water simulation and a synthetic stencil
  simulation. All demonstrate good performance.
---

