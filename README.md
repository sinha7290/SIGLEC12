# SIGLEC12

**Human specific polymorphic pseudogenization of SIGLEC12 and its protective role in advanced cancer progression.**

## Overview

This repository contains the computational analysis behind our study on SIGLEC12, a human specific Siglec whose loss of function through polymorphic pseudogenization correlates with reduced advanced cancer risk. We integrate transcriptomic profiles across multiple cancer cohorts and use Boolean implication reasoning to place SIGLEC12 in its regulatory context.

## Contents

* `notebooks/` — analysis notebooks in publication order
* `data/` — public dataset accession list and preprocessing scripts
* `figures/` — publication figure generation code

## Reproducing the analysis

1. Install dependencies (see `requirements.txt` if present, or a Conda environment file if included)
2. Download the public datasets listed in `data/accessions.txt` from GEO and TCGA
3. Run notebooks in the order indicated by their numeric prefix

## Publication

> Sinha S, et al. Human specific polymorphic pseudogenization of SIGLEC12 protects against advanced cancer progression. *FASEB BioAdvances*.

Please cite the manuscript when using this code or its derived signatures.

## Contact

Saptarshi Sinha, Ph.D. · sasinha@health.ucsd.edu · PreCSN, UC San Diego

## License

MIT License.
