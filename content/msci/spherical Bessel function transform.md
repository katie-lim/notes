---
title: "spherical Bessel function transform"
tags: ["msci"]
---

$$
f_{\ell m}(k) = \sqrt{ \frac{2}{\pi} } \int  \, d^{3}\mathbf{r}
f(\mathbf{r}) kj_{\ell}(kr)Y_{\ell m}^{*}(\theta,\phi)
$$
## Inverse

$$
f(\mathbf{r}) = \sqrt{ \frac{2}{\pi} } \int k \, dk
\sum_{\ell=0}^{\infty} \sum_{m=-\ell}^{\ell}
f_{\ell m}(k) j_{\ell}(kr) Y_{\ell m}(\theta, \phi)
$$

## Conserved quantities
Under this transform, the number of galaxies is conserved, so
$$
f(\mathbf{r}_{0}) d^{3}\mathbf{r}_{0} = f(\mathbf{r})d^{3}\mathbf{r}.
$$
This is the "continuity condition" ([[Heavens & Taylor (1995)]]).