# qmc_ho

Quantum Monte Carlo for the harmonic oscillator

Jupyter python notebooks highlighting two ground state (T=0) methods:

1. Variational Monte Carlo (VMC)
2. Path Integral Ground State Monte Carlo (PIGS)

The code was written in an attempt to be pedagogical at the expense of any and
all efficiency.  These should be treated as *toy* codes.  Statistical
uncertainties are approximated via the standard error and ignore all
correlations between measurements.  These are likely to underestimate the error
in the data.

For more information on PIGS please see:
- 9D. M. Ceperley, *Path Integrals in the Theory of Condensed Helium*, Rev. Mod.
  Phys. **67**, 279 (1995).
  http://link.aps.org/doi/10.1103/RevModPhys.67.279
- A. Sarsa, K. E. Schmidt, and W. R. Magro, *A Path Integral Ground State
  Method*, J. Chem. Phys. **113**, 1366 (2000).
  http://link.aip.org/link/JCPSA6/v113/i4/p1366/s1&Agg=doi
- Y. Yan and D. Blume, *Path Integral Monte Carlo Ground State Approach:
  Formalism, Implementation, and Applications*, J. Phys. B: Atom., Mol.,
  and Opt. **50**, 223001 (2017).
  https://doi.org/10.1088/1361-6455/aa8d7f
