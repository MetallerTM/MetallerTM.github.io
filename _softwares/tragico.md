---
title: TrAGICo
url: /_softwares/tragico
gh_url: https://github.com/letiziafiorucci/tragico
description: Collection of function to extract and analyze experimental parameters from series of NMR spectra
logo: /assets/images/tragico_logo.png
---

![image](/assets/images/tragico_logo.png)

TrAGICo (TRends Analysis Guided Interfaces COllection) is a collection of functions for the extraction and analysis of experimental parameters from 1D and pseudo-2D NMR spectra acquired on Bruker instruments, designed to streamline the process of identifying trends in NMR data and facilitate various analytical tasks.

Key features include:

- Versatility: These functions are highly adaptable and can be integrated with external tools to accommodate a wide range of analytical needs.
- Customizability: Easily modify the functions to suit specific analysis requirements, ensuring flexibility and precision.
- User-Friendly: Clear examples and step-by-step instructions guide users through the application of the functions, making the process accessible to users of all levels.

Some routines included in the scripts are derived from the KLASSEZ package for NMR data processing and analysis (available [here](/softwares/klassez)).

The code folder contains three python scripts: main4test.py, with example main codes, ``f_fit.py``, 
containing the functions for spectra modeling and integration, and ``f_functions.py``, a collection of all-purpose functions used by the analysis tools and in the input files generation. 
Additionally, a complete documentation and the results obtained from example codes are saved in dedicated folders.

The functions require python 3.12. The additional dependencies and their versions are: ``numpy`` (version 2.0.2), 
``matplotlib`` (version 3.9.2), ``lmfit`` (version 1.3.2) and ``nmrglue`` (version 0.10). 

---

## Repositories

* _GitHub_: [https://github.com/letiziafiorucci/tragico](https://github.com/letiziafiorucci/tragico)

