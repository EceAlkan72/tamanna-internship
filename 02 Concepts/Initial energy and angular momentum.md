---
tags: [concept, numerics, calibration]
---
# Initial energy $E$ and angular momentum $J$

Constraint violations in the superposed initial data make ADM-integral values unreliable at the needed accuracy.

## Energy (App. A)
$$E(c_V) = \frac{2m}{\sqrt{1-v^2}} + c_V V_N,\qquad V_N = -\frac{Gm^2}{2X}\approx-0.002476M$$
- Naive ADM gives only kinetic energy, 1.027324 M.
- Unphysical energy from Hamiltonian-constraint violation $E_u = \int\rho_u\sqrt\gamma\,d^3x \approx (1.5\pm0.2)V_N$.
- PN estimate: $c_V\approx1+7v^2 = 1.37$ → adopted. $E/M = 1.02394$, $\gamma = 1.09690$.
- $c_V = 1, 1.37, 1.5$ all give δχ within ~2σ → robust.
- Non-Cartesian asymptotic metric only rescales units → dimensionless quantities unaffected.

## Angular momentum
$$J = (1+\epsilon_J)J_{\rm NR},\qquad \epsilon_J = 0.006\pm0.001$$
- **The only fitted parameter.** Fitted on BS–anti-BS runs with $b\le13\,GM$ (BH-like, see [[Point-mass potential w_BH]]), then applied to all 32 runs.
