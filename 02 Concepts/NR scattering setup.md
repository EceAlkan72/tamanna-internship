---
tags: [concept, numerics]
---
# NR scattering setup

- Code: **LEAN** (Cactus/Carpet), CCZ4 Einstein–Klein–Gordon, 4th-order finite differences, moving-puncture gauge.
- Grid: domain $448\,GM$, 8 refinement levels, $\Delta x = 0.02\,GM$ finest; Sommerfeld boundaries.
- Initial data: improved superposition of two boosted single-BS spacetimes (Helfer et al. 2022); constraint damping $\kappa_1=0.1/M$.
- Kinematics: equal mass ($\nu=1/4$), $|v|=0.2291$, $X=50.49\,GM$, $b = 2Xv_y/|v|$.
- Runs: 4 binary types × 8 $b$ values ($9.9\ldots16\,GM$) = 32.
- Convergence: extra resolutions $0.022$, $0.017\,GM$ → 2nd order, ~0.5° error.
- Extra check (App. C): BS–anti-BS at $b=10.5$, $X/M = 50\ldots100$ → ≤1.8σ.

Angle extraction → [[Scattering angle]]. Energy/AM subtleties → [[Initial energy and angular momentum]].

Observation: at small $b$ both stars **collapse to BHs** after the encounter (not seen in quasi-circular runs at same compactness).
