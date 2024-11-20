The LaTeX source for my honours thesis, as well as all talks I gave related to it.

## Abstract

A celebrated theorem of Beilinson in the short note [[Bei78](https://api.semanticscholar.org/CorpusID:122566865)] establishes an equivalence of derived categories between the coherent sheaves on projective $n$-space and modules over certain finite dimensional algebras.
We give a gentle introduction to this result in the case of the projective line using the more modern machinery of tilting theory.
In particular, we ultimately show that this derived equivalence links the geometry of the projective line to the representation theory of the Kronecker quiver, demonstrating a fruitful connection between the fields of algebraic geometry and representation theory.


## Compilation

Ensure you have a TeX distribution (e.g. [TeX Live](https://tug.org/texlive/)) installed, as well as the `latexmk` utility.

Now, to generate a PDF copy of this thesis, run

```bash
latexmk -pdf
```

To clean up build artefacts afterwards, run

```bash
latexmk -c
```
