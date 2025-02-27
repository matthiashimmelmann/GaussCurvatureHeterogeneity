# Supplementary Code for the Manuscript "Amorphous bicontinuous minimal surface models and the superior Gaussian curvature uniformity of Diamond, Primitive and Gyroid surfaces"
Authors: Matthias Himmelmann, Martin Cramer Pedersen, Michael A. Klatt, Philipp W.A. Schönhöfer, Myfanwy E. Evans, Gerd. E. Schröder-Turk

## Generation of Punctured Parallel Sheets in the 3-torus

[DisorderedPointClusters.jl](https://github.com/matthiashimmelmann/DisorderedPointClusters.jl) (Julia code)

## Surface Evolver Code

Topology-stabilized curvature optimization (example file): [`amorphous-diamond-50b.fe`](https://github.com/matthiashimmelmann/GaussCurvatureHeterogeneity/blob/main/amorphous-diamond-50b.fe).  The script can be run using the command `algorithm`.

Enforcing Isotropy Algorithm (example file): [`isotropicalize_tD.fe`](https://github.com/matthiashimmelmann/GaussCurvatureHeterogeneity/blob/main/isotropicalize_tD.fe). The script can be run using the command `calc_minkowski_tensors`.

## TPMS curvature and area calculation code

The Python code used for our calculation of TPMS properties can be found at:

https://gitlab.com/mcpe/tpmsweierstrass
