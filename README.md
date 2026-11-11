# Nullity-Preserving-Hadmard-Product

Mathematica code for

A. Singh, *Independent chiral control in theory-space models: a rank-preserving framework and its application to neutrino mass generation*, Eur. Phys. J. C 86, 743 (2026), [arXiv:2409.09033](https://arxiv.org/abs/2409.09033).

`Rank_Preserving_Transformations.nb` reproduces the paper's numerical results:

1. A demonstration that separable element-wise transformations b_ij = a_ij / (gL(i) gR(j)) preserve rank and both nullities.
2. Fig. 1: the Kaluza-Klein spectrum of a deconstructed model before and after a transformation (N = 50, f = 1).
3. Fig. 2: the light-neutrino mass versus the number of sites for the nearest-neighbour chain H and the transformed chain H' (m = 1 TeV, y = 1, f = 1.3).
4. Supporting numbers quoted in the text: the next-lightest chain state, the seesaw cross-check and the endpoint formula.
5. The sensitivity of the light mass to random perturbations of the transformed matrix.

Open the notebook in Mathematica 13 or later and choose Evaluation > Evaluate Notebook. The figures are exported as PDF files next to the notebook. The light-mass calculation uses 80-digit arithmetic because the full mass matrix is badly conditioned.
