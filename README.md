## Conflict-Driven SAT Solving Using _XOR-OR-AND Normal Forms_

This repository contains the source code for conflict-driven XNF SAT solver `Xorricane` as well as the benchmark suites used in our paper  
  *J.Danner, *_SAT Solving Using XOR-OR-AND Normal Forms and Cryptographic Fault Attacks_*, Universität Passau, 2025.*

---

##### Xorricane

The conflict-driven XNF SAT Solving Algorithm, **`CDXCL-lite` (Algorithm 6)**, is implemented in *C++* by _J. Danner_ in the submodule `Xorricane`.
It uses the data structures and most optimizations introduced in *Section 5.2*.
Details about its heuristics and options can be found in *Appendix A*.

##### Benchmark Suites

The random and cryptographic benchmark suites of Section 6 are available under the [Releases](../../releases) section.

---

###### Setup

Run `git submodule update --init --recursive` to clone all submodules. Instructions to run and build the tools and solvers can be found in their respective submodules.
