# Toward Gauge Structure from Non-Injective Projection (Q6a)

This repository contains the source of the **Q6a Cosmochrony paper**
*Toward Gauge Structure from Non-Injective Projection: Fibre-Invariant Charges, a Supplied SU(2)
Carrier, and a Conditional Connection*.

Starting from the axioms of admissible non-injective transitions (Foundation paper M),
the paper sets out the gauge-theoretic structures that the fibres of a non-injective
projection carry, and states which of them are defined, which are conditional, and which
remain open. It determines neither the gauge group nor Yang–Mills dynamics.

## Results

- **Gauge charges** are defined as functions constant on the projection fibres. Such a
  function factors through the projection, so it is a function of the observable state; its
  identification with a conserved physical charge is open.
- **The gauge group** is the group of fibre-preserving transformations.
- \(\mathrm{U}(1)\) arises as the residual global phase symmetry when the projection is
  defined through span-based observables.
- On the spinor carrier \(V_\rho \cong \mathbb{C}^2\) supplied conditionally by O23, and
  under the neutral-sector hypothesis \(\mathrm{Im}\,\Pi_{\mathrm{adm}} = \mathrm{Ntrl}\) of
  O27, the non-abelian sector is \(\mathfrak{su}(2)\) and the group acting faithfully on
  the carrier is \(\mathrm{SU}(2)\) (Proposition 2.5). This is a consistency statement
  about a supplied carrier, not a selection: the paper does not establish that
  \(\mathrm{SU}(2)\) is the unique or minimal non-abelian group compatible with admissible
  projection, and the carrier selection is open.
- \(\mathrm{SU}(3)\) is a structural hypothesis whose identification is open.
- **The gauge connection** is not derived. Two continuum hypotheses that the paper does
  not prove (a smooth fibre bundle and a differentiable base, the second the open spatial
  continuum question left by Q5a) do not determine a connection, so a structure group, its
  representation and a connection are supplied. On these data the connection generates
  parallel transport, and its curvature measures the path dependence of transport around
  infinitesimal loops; flatness gives a path-independent identification of fibres only
  locally.
- **The Yang–Mills action** is a structural motivation on this curvature, not a
  derivation from the axioms; its uniqueness is the standard result under an explicit
  truncation (total mass dimension at most four, fixed background).

*Interpretive outlook (a reading, not a result).* Gauge redundancy is read as the symmetry
of a fibre that the observables do not resolve. The paper locates where a gauge group, a
comparison of fibres and a dynamics would enter, and supplies none of them from
non-injectivity: it is a dictionary and a list of missing inputs, not a derivation of gauge
fields.

Effective spacetime geometry is not addressed.

## Position in the programme

Q6a belongs to the **gauge structure sub-programme** (Presentation Note 3).
Its inputs are the Foundation axioms (paper M), the spectral admissibility results O12,
O23 (conditionally on its supplied spinor carrier) and O27 (under its neutral-sector
hypothesis), and Q5a for the status of the spatial continuum. It cites Q2 only to state
that a spectral degeneracy carries no selection content. The capacity bound it references
is the capacity axiom [A-cap] of the companion capacity paper, with the Born–Infeld
action as its saturation candidate; that paper leaves the relational construction of a
gauge curvature open.

## Repository contents

```
q6a/
├── tex/          # LaTeX sources (Q6a.tex, bibliographies)
├── compile.sh    # pdflatex -> bibtex -> pdflatex x2, output in out/ (git-ignored)
└── README.md
```

## Citation

> J. Beau, *Toward Gauge Structure from Non-Injective Projection: Fibre-Invariant Charges, a
> Supplied SU(2) Carrier, and a Conditional Connection*, Zenodo, 2026.
> DOI: [10.5281/zenodo.19655294](https://doi.org/10.5281/zenodo.19655294)

## Links

- 🌐 Programme website: https://cosmochrony.org
- 💻 GitHub organization: https://github.com/Cosmochrony

## Acknowledgements

Portions of the editorial refinement benefited from iterative interactions with large
language models, used as analytical assistants. All claims and final formulations
remain the sole responsibility of the author.
