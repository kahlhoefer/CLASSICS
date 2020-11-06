# CLASSICS
**CalcuLAtionS of Self Interaction Cross Sections**

This code provides analytical expressions and tabulated values for the self-scattering cross sections of dark matter particles interacting via a Yukawa potential. For details, see 
B. Colquhoun, S. Heeba, F. Kahlhoefer, L. Sagunski and S. Tulin, *The Semi-Classical Regime for Dark Matter Self-Interactions*, [arXiv:2011.XXXXX](https://arxiv.org/abs/2011.XXXXX).

File format:
* Column 1: beta_0
* Column 2: kappa_0
* Column 3: m_phi^2/pi * sigma_X^Y, where
  * X = T or V for distinguishable particles and X = even, odd, scalar, fermion or vector for identical particles
  * Y = attractive, repulsive

See *cross_sections.py* for example usage.
