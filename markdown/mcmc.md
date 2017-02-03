### Sketch Metropolis-Hastings MCMC algorithm

1. Start with a 'random tree' tree with topology 'T', substitution parameters 'mu' and coalescenct parameter 'lambda'.
2. Propose a change to either of the 3 parameters.
   * Topology can be changed using NNI, SPR or TBR.
   * Coalesence can be changed subjext to conditions.
3. If posterior probability is higher accept change. else, go to step 2.

