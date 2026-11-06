---
tags: [concept, potential, key, new-in-paper]
---
# Scalar potential $w^{\rm scalar}$

Short-range interaction when the two stars' scalar fields overlap. Derived from [[EFT with oscillating scalar sources]].

**Leading order** (Eq. 8) — Yukawa:
$$w^{\rm scalar}_{\rm LO} = \frac{8\pi c_1c_2}{Gm_1m_2}\,\frac{e^{-\bar m\bar r}}{\bar r}\,\cos\Phi_{21}$$
- $\bar m = GMh\tilde\mu$ (inverse range)
- $\tilde\mu^2 = \mu^2 - \dfrac{2\omega_1\omega_2\gamma-\omega_1^2-\omega_2^2}{\gamma^2-1}$ ⚠️ *reconstructed — PDF text was garbled; check Eq. 8 in the original.* Sanity check: equal $\omega$, $\gamma\to1$ gives $\mu^2-\omega^2$ ✓.
- $\Phi_{21}=\Phi_2-\Phi_1$

**The punchline — phase sets the sign**

| Binary | $\Phi_{21}$ | Force |
|---|---|---|
| BSBS | 0 | attractive |
| BSBS$^{\pi/2}$ | $\pi/2$ | zero (LO only!) |
| BSBS$^\pi$ | $\pi$ | repulsive |
| BS–anti-BS | — | fast oscillation, averages to 0 → BH-like |

**Higher order**: $w^{\rm scalar}_{\rm HO} = w^{\rm scalar}_{\rm LO}\times w^{\rm scalar}_{\rm g\text{-}dressing}$ → [[Gravitational dressing]]

**Angle** (Eq. 12):
$$\frac{\chi^{\rm scalar}_{\rm LO}}{h} = \frac{8\pi M\tilde\mu}{m_1m_2}\frac{c_1c_2}{\gamma^2-1}K_1(\tilde\mu b)\cos\Phi_{21}$$

Results: dominates at small $b$; LO alone fails, HO needed. Attractive case reaches $\bar r_{\min}\approx6.8$.
