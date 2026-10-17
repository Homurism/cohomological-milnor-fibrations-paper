# Cohomological Milnor Fibrations of Landau-Ginzburg Models

**Huijun Fan and Jieran Wang**

**[Read the latest PDF](./Cohomological-Milnor-Fibrations-article.pdf)** | [Version v0.1.0](https://github.com/Homurism/cohomological-milnor-fibrations-paper/releases/tag/v0.1.0) | [Report an error](https://github.com/Homurism/cohomological-milnor-fibrations-paper/issues)

**Status:** working draft, v0.1.0, October 17, 2026. Some mathematical proof details remain under revision.

## About the paper

We study the global topology of fundamentally tame Landau-Ginzburg models on complete Kähler manifolds: surjectivity of the superpotential, fibrations over regular values, relative homology under a finite-critical-point hypothesis, and relative cohomology bundles for uniformly tame deformations on Stein manifolds.

## Reading and versions

- The PDF linked above follows the current `main` branch.
- Tagged releases preserve specific versions together with their PDF and release notes.
- When citing or discussing a statement, please specify the version and theorem or equation number.

Suggested reference: Huijun Fan and Jieran Wang, *Cohomological Milnor Fibrations of Landau-Ginzburg Models*, working draft, v0.1.0, 2026.

## Source and compilation

This repository includes the manuscript source, its bibliography, and a compiled PDF. With TeX Live, XeLaTeX, and Biber installed, run:

```sh
xelatex -interaction=nonstopmode -halt-on-error Cohomological-Milnor-Fibrations-article.tex
biber Cohomological-Milnor-Fibrations-article
xelatex -interaction=nonstopmode -halt-on-error Cohomological-Milnor-Fibrations-article.tex
xelatex -interaction=nonstopmode -halt-on-error Cohomological-Milnor-Fibrations-article.tex
```

The bibliography is included locally; compilation does not depend on files outside this repository.

## Feedback

Questions, corrections, and mathematical comments are welcome through Issues. Please include the version, a precise location, and an explanation of the issue. A pull request can propose a source correction; changes are reviewed before inclusion.

## License

No license has yet been specified.
