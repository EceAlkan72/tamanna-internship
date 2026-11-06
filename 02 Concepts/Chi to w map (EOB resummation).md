---
tags: [concept, analytic, key]
---
# $\chi \leftrightarrow w$ map (EOB resummation)

$$\pi+\chi(\gamma,j) = 2j\int_0^{\bar u_{\max}(\gamma,j)}\frac{d\bar u}{\sqrt{p_\infty^2 + w(\bar u,\gamma) - j^2\bar u^2}},\qquad \bar u = 1/\bar r$$

Read the root as radial momentum: energy ($p_\infty^2$) + attraction ($w$) − centrifugal barrier ($j^2\bar u^2$). Same logic as a comet around the Sun.

**Idea**
1. PM gives coefficients $\chi_1,\chi_2,\ldots$ ([[Post-Minkowskian expansion]]).
2. Translate one-to-one into $w_1,w_2,\ldots$ — no information gained or lost.
3. Don't sum the $\chi$ series; insert $w$ into the **exact** integral.

**Why better**: the integral is nonlinear in $w$ → generates all orders in $1/j$ (resummation). Captures the "whirl" near capture where $\chi$ blows up; a polynomial in $1/j$ cannot.

**Newtonian toy**: $w\propto1/r$ exactly, $\chi=2\arctan x$, $x=GM/(bv^2)$. Truncated $\chi = 2x-\tfrac23x^3$:

| $x$ | true | truncated |
|---|---|---|
| 0.2 | 22.6° | 22.6° |
| 1 | 90° | 76° |
| 2 | 127° | −76° |

**Linearised version** (used for the scalar piece, Eq. 13):
$$\chi^{\rm scalar}(j) = -\frac{\partial}{\partial j}\int_{\bar r_{\min}}^\infty d\bar r\,\frac{w^{\rm scalar}(\bar r)}{\sqrt{p_\infty^2-j^2/\bar r^2}}$$

**Tidal coefficients** (Eq. 7): $\chi_6^{\rm tid}=\tfrac{15\pi}{32}p_\infty^4 w_6^{\rm tid}$, $\chi_7^{\rm tid}=4p_\infty^3w_1w_6^{\rm tid}+\tfrac85p_\infty^5w_7^{\rm tid}$
