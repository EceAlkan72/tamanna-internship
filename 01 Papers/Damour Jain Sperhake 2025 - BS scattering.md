---
title: "Gravitational scattering of solitonic boson stars: Analytics vs Numerics"
authors: [Thibault Damour, Tamanna Jain, Ulrich Sperhake]
year: 2025
arxiv: "2512.00945"
url: https://arxiv.org/abs/2512.00945
status: read
tags: [paper, core, boson-stars, EOB, scattering]
---
# Damour, Jain, Sperhake (2025) — BS scattering: analytics vs numerics

## One-paragraph summary
Two [[Boson star|boson stars]] are scattered on hyperbolic orbits. The [[Scattering angle]] $\chi$ is computed (1) with full numerical relativity ([[NR scattering setup]]) and (2) analytically with an [[Effective-one-body]] potential
$$w = w^{\rm BH} + w^{\rm tid} + w^{\rm scalar}.$$
The new piece is [[Scalar potential w_scalar]]: a short-range Yukawa force whose sign is set by $\cos(\Phi_2-\Phi_1)$. Agreement is ~1σ of NR error over 32 runs with essentially one fitted parameter. → first EOB potential for BS binaries, a building block for GW templates.

## Method — step by step
1. **Stars**: solitonic BSs, $\sqrt{G}\sigma_0 = 0.2$, $\sqrt{G}A_{\rm ctr}=0.17$, $r_{99}=5.58\,Gm$. See [[Boson star]].
2. **Four binaries** (secondary varies): BSBS ($\Phi_{21}=0$), BSBS$^{\pi/2}$, BSBS$^{\pi}$, BS–anti-BS ($\epsilon=-1$).
3. **NR**: 8 impact parameters $b/GM = 9.9\ldots16$, fixed $E/M = 1.02394$ → 32 runs. See [[NR scattering setup]].
4. **Extract $\chi_{\rm NR}$**: fit $\theta(1/r)$ polynomials, extrapolate $r\to\infty$; error ≲ 1.6°.
5. **Analytic potential**:
   - [[Point-mass potential w_BH]] — 4PM exact + NR-fitted 5PM, $w_5^{\rm BH}=-1.03\pm0.03$
   - [[Tidal potential w_tid]] — 6PM, 7PM terms with $\Lambda\approx7$
   - [[Scalar potential w_scalar]] — LO from [[EFT with oscillating scalar sources]], HO via [[Gravitational dressing]]
6. **Predict $\chi_{\rm AR}$** by inserting $w$ into the exact integral → [[Chi to w map (EOB resummation)]].
7. **Fix inputs**: $E$ via $c_V=1.37$, $J=(1+0.006)J_{\rm NR}$ (only fit, on BS–anti-BS runs), [[Scalar charge]] $\sqrt{G}\mu c_A = 1.608$. See [[Initial energy and angular momentum]].
8. **Compare**: $\delta_\chi = (\chi_{\rm AR}-\chi_{\rm NR})/\Delta\chi_{\rm NR}$.

## Key equations
- Solitonic potential: $V = \mu^2|\varphi|^2(1-2|\varphi|^2/\sigma_0^2)^2$
- $\chi \leftrightarrow w$ map (Eq. 6):
$$\pi+\chi = 2j\int_0^{\bar u_{\max}}\frac{d\bar u}{\sqrt{p_\infty^2 + w(\bar u,\gamma) - j^2\bar u^2}}$$
- LO scalar potential (Eq. 8):
$$w^{\rm scalar}_{\rm LO} = \frac{8\pi c_1c_2}{Gm_1m_2}\,\frac{e^{-\bar m\bar r}}{\bar r}\cos\Phi_{21}$$
- Energy variable: $\gamma = 2(E/M)^2-1$ (equal mass), $p_\infty^2=\gamma^2-1$, $j = J/(Gm_1m_2)$

## Results
- Percent-level agreement for all four sequences; worst at $b=9.9\,GM$ ($\chi>200°$).
- Scalar force dominates at small $b$: BSBS $\chi\approx259°$ vs BBH $\approx212°$.
- LO scalar alone fails badly → HO dressing essential.
- Tides small but real: BS–anti-BS at $b=9.9$ goes 3σ → 1σ with $w_6+w_7$.
- PM-expanded angles would be ~10× worse than EOB-resummed.
- Surprise: at small $b$ both stars **collapse to BHs** after the encounter.

## Limitations / where I could contribute
- HO scalar term is a factorised **ansatz**, not a computed $O(Gc_Ac_B)$ result.
- $\Phi=\pi/2$ "no force" only at LO.
- Only even-parity quadrupole $\Lambda$ known; odd-parity & octupole missing.
- One energy, equal masses, no spin, one stellar model.
- Non-conservative (longitudinal) scalar impulse identified but not modelled.

## My notes
- Explained for supervisor: see [[Why scattering not inspirals]], [[Chi to w map (EOB resummation)]].
- Questions → [[Open questions]]
