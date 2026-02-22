# Geomechanics Notebooks

A structured computational portfolio in analytical rock mechanics and
subsurface engineering.

This repository presents a curated series of Jupyter notebooks developed
to demonstrate theoretical understanding, numerical implementation, and
engineering interpretation of core geomechanical problems. Each notebook
combines analytical formulations, transparent assumptions, and
reproducible Python workflows.

The objective is not software distribution, but technical clarity ---
transforming classical rock mechanics formulations into structured
computational insight.

------------------------------------------------------------------------

## Concept

Rock mechanics is often taught theoretically and applied numerically,
but rarely documented in a reproducible computational format.

This repository bridges that gap.

Each notebook is designed as a self-contained technical study:

1.  Problem definition\
2.  Governing equations\
3.  Implementation in Python\
4.  Visualisation of results\
5.  Engineering interpretation

The emphasis is on understanding stress redistribution, failure
initiation, and stability margins under simplified but rigorous
analytical conditions.

------------------------------------------------------------------------

## Core Topics

The notebooks progressively cover:

-   Analytical stress solutions around openings (Kirsch-type
    formulations)
-   Stress transformation and principal stress evaluation
-   Rock mass strength modelling (Hoek--Brown and Mohr--Coulomb
    criteria)
-   Failure envelope construction and comparison
-   Stability factor concepts under varying confinement
-   Parametric and sensitivity analyses
-   Interpretation of stress--strength interaction

Applications include underground excavations, wellbore stability, and
subsurface energy systems --- treated from a mechanics-first
perspective.

------------------------------------------------------------------------

## Philosophy

The approach follows a clear progression:

Stress → Strength → Stability → Interpretation

The goal is not only to compute results, but to understand the mechanics
governing them.

All examples use generic parameter sets for demonstration purposes.\
The repository is intentionally theory-focused and independent of
proprietary or project-specific data.

------------------------------------------------------------------------

## Repository Structure

notebooks/ → Structured computational studies\
figures/ → Exported visualisations

Each notebook is versioned and written to maintain reproducibility and
clarity.

------------------------------------------------------------------------

## Technical Stack

-   Python
-   NumPy
-   Pandas
-   Matplotlib
-   Jupyter Notebook

The computational environment can be reproduced using:

``` bash
pip install -r requirements.txt
```

or

``` bash
conda env create -f environment.yml
```

------------------------------------------------------------------------

## About the Author

Josip Vincek\
Computational Subsurface Engineering \| Rock Mechanics, Energy &
Infrastructure\
PhD Researcher

This repository reflects ongoing work in analytical modelling,
computational geomechanics, and engineering-oriented stability
assessment.

------------------------------------------------------------------------

## License

MIT License -- see LICENSE file for details.
