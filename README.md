This repository contains a single Python script (analysis.py) that reproduces all numerical results reported in Results Sections 3.1–3.5 of the manuscript.

The script computes:

predictive error as a function of delay and structural non-reciprocity,

the instability boundary and terminal breakdown of reciprocal systems,

restoration of stability through non-reciprocal architectures,

the Agency Index as an informational asymmetry measure,

robustness of the Agency Index under stochastic perturbations.

The code is self-contained, requires only NumPy, and performs no figure generation.
All parameters are fixed as described in the Methods, and no parameter fitting or optimization is performed.

To run the analysis:
python analysis.py

The script prints numerical values corresponding to those reported in the main text and figures.
