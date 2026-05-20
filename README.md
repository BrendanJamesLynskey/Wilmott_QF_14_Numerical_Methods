# Numerical Methods

Deck 14 of the [Paul Wilmott Introduces Quantitative Finance &mdash; Companion Series](https://github.com/BrendanJamesLynskey/Wilmott_QF_Hub).

**Live presentation:** https://brendanjameslynskey.github.io/Wilmott_QF_14_Numerical_Methods/

A guided tour of chapters 27, 28, 29 and 30 of *Paul Wilmott Introduces Quantitative Finance*
(2nd edition, Wiley, 2007) &mdash; the three families of numerical methods that price
every derivative for which a closed form doesn't exist.

## What's inside

- The three families &mdash; finite differences, Monte Carlo, numerical integration &mdash; and when each applies
- The $(S, t)$ grid: explicit, implicit and Crank&ndash;Nicolson time-stepping; stability constraints
- Forward, backward and central differences for $\Delta$, $\Gamma$, $\Theta$
- Explicit FD for the Black&ndash;Scholes PDE; the $\delta t \le 1/(\sigma^2 I^2 + r)$ stability bound
- American options on a finite-difference grid via the $\max(V, \text{intrinsic})$ override
- Monte Carlo simulation under risk-neutral GBM; $1/\sqrt{N}$ convergence and standard error
- Generating normals (Box&ndash;Muller); antithetic and control variates for variance reduction
- American Monte Carlo via Longstaff&ndash;Schwartz regression
- Low-discrepancy sequences (Halton, Sobol); quasi-Monte Carlo for higher-dimensional problems
- **Interactive Monte Carlo vs finite-difference pricer** &mdash; toggle the method, slide $S_0, K, T, \sigma, r, N$; watch ~30 simulated paths and a payoff histogram for MC, or the $V(S, t)$ value-surface heatmap for FD, with the BS closed-form price for comparison

Companion to chapters 27&ndash;30 of:

> Wilmott, P. (2007). *Paul Wilmott Introduces Quantitative Finance,
> Second Edition.* John Wiley &amp; Sons. ISBN 978-0-470-31958-1.

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
