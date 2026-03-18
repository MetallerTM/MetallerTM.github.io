---
title: pyIHM
url: /_softwares/pyihm
gh_url: https://github.com/MetallerTM/pyihm
description: Interface for Indirect Hard Modelling of NMR spectra.
logo: /assets/images/pyihm_logo.png
---

![image](/assets/images/pyihm_logo.png)

*pyIHM* is a python software designed in order to offer a comprehensive interface to perform quantitative analyses on NMR spectra of mixtures, using the Indirect Hard Modelling approach.

The Indirect Hard Modelling consists into performing a deconvolution of the spectrum of the mixture using the spectra of the individual components as basis set. Conceptually, the algorithm is made of four steps:
1. fit the spectra of the components of the mixture with a hard model (e.g. Voigt);
2. read and process the spectrum of the mixture;
3. make the initial guess using the set of peaks generated at point 1;
4. get the relative concentrations of the components in the mixture.

The routines for reading and processing of the spectra and for the generation of the models rely on the *KLASSEZ* package.

---

## Repositories

* _GitHub_: [https://github.com/MetallerTM/pyihm](https://github.com/MetallerTM/pyihm)
* _PyPI_: [https://pypi.org/project/pyihm/](https://pypi.org/project/pyihm/)


## Related works

* Bruno, Francesco, et al. "pyIHM: Indirect Hard Modeling, in Python." _Analytical Chemistry_ 97.8 (2025): 4598-4605.  
  [ACS Publications](https://pubs.acs.org/doi/10.1021/acs.analchem.4c06484)

