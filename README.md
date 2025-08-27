## Conflict-Driven SAT Solving Using _XOR-OR-AND Normal Forms_

This repository contains the source code for the conflict-driven XNF SAT solver `Xorricane` as well as the benchmark suites presented in
> *J.Danner, M.Kreuzer, *_Conflict-Driven SAT Solving Using XOR-OR-AND Normal Forms_*, _submitted_, 2025.*

---

#### Xorricane

The conflict-driven XNF SAT Solving Algorithm, **`CDXCL-lite` (Algorithm 6)**, is implemented in *C++* by _J. Danner_ in the submodule `Xorricane`.
It uses the data structures and most optimizations introduced in *Section 5.2*.
Details on heuristics and command line options can be found in *Appendix A*.

###### Setup

Run `git submodule update --init` to clone the submodule. Instructions to run and build the solver can be found in the respective subfolder.


#### Benchmark Suites

The random and cryptographic benchmark suites used in *Section 6* are available under the [Releases](../../releases) section.


---

#### Related Tools / Solvers
 - Conversion tool from ANF to XNF, [`anf_to_2xnf`](https://github.com/Wrazlmumfp/anf_to_2xnf.git); used for benchmark creation.
 - Graph-based DPLL-SAT 2-XNF solver, [`2-Xornado`](https://github.com/j-danner/2-Xornado.git); used as preprocessor in `Xorricane`.

