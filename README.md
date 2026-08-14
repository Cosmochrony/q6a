# Gauge Structure from Admissible Non-Injective Projection (Q6a)

This repository contains the source of the **Q6a Cosmochrony paper**
*Gauge Structure from Admissible Non-Injective Projection*.

Starting from the axiomatic foundation of admissible non-injective transitions
(Foundation paper M), the paper derives the structure of gauge theory without
introducing it as a postulate.

## Results

- **Gauge charges** are identified as invariants of equivalence classes in the
  projection fibre: two configurations are gauge-equivalent when they project to the
  same observable state.
- **The gauge group** is the group of fibre-preserving transformations.
- \(\mathrm{SU}(2)\) is identified as the unique minimal non-abelian admissible group
  from the quaternionic structure of the admissible fibre; \(\mathrm{U}(1)\) arises as
  the residual phase symmetry; \(\mathrm{SU}(3)\) is a structurally motivated candidate
  extension whose derivation remains open.
- **The gauge connection** arises as the infinitesimal generator of fibre transport
  under varying projection, and Yang–Mills dynamics emerge from minimising the
  resulting curvature.

No dynamical substrate is required at any step; the derivations rest solely on
Axioms A1–A4 of the Foundation paper and the spectral results of the O-series.
Effective spacetime geometry, requiring the continuum limit of Q5a, is left to the
companion papers of the emergent-geometry sub-programme.

## Position in the programme

Q6a belongs to the **gauge structure sub-programme** (Presentation Note 3).
Its inputs are the Foundation axioms (paper M), the quantum-structure results (Q1, Q2),
and the spectral admissibility results (O12, O27, and O23 conditionally on its supplied
spinor carrier); the capacity bound it references
is the capacity axiom [A-cap] of the companion capacity paper, with the Born–Infeld
action as its saturation candidate.

## Repository contents

```
q6a/
├── tex/          # LaTeX sources (Q6a.tex, bibliographies)
├── compile.sh    # pdflatex -> bibtex -> pdflatex x2, output in out/ (git-ignored)
└── README.md
```

## Citation

> J. Beau, *Gauge Structure from Admissible Non-Injective Projection*, Zenodo, 2026.
> DOI: [10.5281/zenodo.19655294](https://doi.org/10.5281/zenodo.19655294)

## Links

- 🌐 Programme website: https://cosmochrony.org
- 💻 GitHub organization: https://github.com/Cosmochrony

## Acknowledgements

Portions of the editorial refinement benefited from iterative interactions with large
language models, used as analytical assistants. All claims and final formulations
remain the sole responsibility of the author.
